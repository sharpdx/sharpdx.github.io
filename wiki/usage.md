---
layout: wiki
title: Usage
order: 2
parent: /wiki/index.html
---

SharpDX is a low level wrapper for the DirectX API. The main source of documentation is available from [DirectX Graphics and Gaming](https://msdn.microsoft.com/en-us/library/windows/desktop/ee663274%28v=vs.85%29.aspx). Most of the resources available on internet are mostly for C++.

> Note that if SharpDX is too low level for you, you should consider using a higher level engine/APIs like [Xenko](https://xenko.com), or [MonoGame](http://www.monogame.net/) or [Win2D](https://github.com/Microsoft/Win2D) (For Direct2D/DirectWrite/WIC APIs)

## COM, Dispose pattern and Finalizer

Most of the DirectX API expose services through COM interfaces. The base interface of COM objects is called `IUnknown` and provides the following methods:

- `int AddReference()`
- `int ReleaseReference()`
- `HRESULT QueryInterface(ref Guid interfaceGuid, out IntPtr pComObj)`

Each COM object contains an internal reference counter and is destroyed only when the `ReleaseReference()` is called and the counter goes to 0.

All SharpDX COM objects inherit from [ComObject](https://github.com/sharpdx/SharpDX/blob/master/Source/SharpDX/ComObject.cs) which implements the `IDisposable` pattern.

The `Dispose()` method is actually a shorthand to the COM method `ReleaseReference()`.

> Note that `ComObject` in SharpDX are not disposed by .NET finalizer. If a COM object is not released by a call to `Dispose()` or `ReleaseReference()` it will not release the native object and memory attached to it.

A SharpDX `ComObject` expose the underlying COM pointer through the property `NativePointer`. In most situations, you won't have to use this pointer directly. 

Note also that many properties and methods in the DirectX APIs are returning COM objects. In SharpDX, most of the time, if you call these methods to get a COM object, you will get different .NET object instance even if the underlying COM pointer is the same, but calling the COM method has incremented the reference to the returned COM object, and should be disposed/released accordingly.

## `HRESULT` and `SharpDXException`

Almost all Windows APIs are using an integer as a return value for all the methods and functions. It is usually called the `HRESULT`. 

- a value `< 0` means that there was an error
- a value `== 0` is a success
- a value `> 0` is sometimes used to return a non-error status depending on the method

While there are some common HRESULT defined (like for COM `NotImplementedInterface`), most of the DirectX APIs defined their own set of HRESULT/error code (for example: [DXGI error HRESULT](https://msdn.microsoft.com/en-us/library/windows/desktop/bb509553%28v=vs.85%29.aspx))

In SharpDX, most of the methods are automatically throwing a `SharpDXException` if the `HRESULT` is `< 0`. The exception contains the `HRESULT` code.

The `HRESULT` is often not enough to debug a method call. But fortunately, most of the DirectX APIs provide a debug layer that can be activated. For example, you can activate detailed debug logs for Direct3D11:

```C#
d3d11Device = new SharpDX.Direct3D11.Device(DriverType.Hardware, DeviceCreationFlags.Debug);
```
> Note that you can see this log in the Visual Studio Output if you debug your application and that you have enabled `Enable native code debugging` in your .NET project. 

Check the DirectX documentation debug layer specific to the API for more details.








