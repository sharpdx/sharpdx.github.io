---
layout: wiki
title: Installation
order: 1
parent: /wiki/index.html
---
Starting with 3.0.0 version, SharpDX assemblies are compiled into two profiles:

- `.NET 4.5+` for Desktop App.
- `PCL .NET 4.6+` for Store Apps, CoreCLR or PCL libraries.

Note that depending on the compilation profile, some DirectX APIs are not available (see section [Supported DirectX APIs per platform]() for more details)

Binary assemblies are distributed in two forms:

1. **Nuget**: Simply browse the SharpDX component you want to using the menu [Manage Nuget Packages](http://docs.nuget.org/docs/start-here/managing-nuget-packages-using-the-dialog) and nuget will resolve all the assembly dependencies automatically
  - Depending on the type of your project (Desktop, StoreApps, or PCL lib), Nuget will automatically select the correct version (`.NET 4.5` or `PCL .NET 4.6+`)
  - Thanks to nuget, dependencies between assemblies are automatically resolved
2. **Zip**: Download the zip/self-extract `SharpDX-SDK-x.y.z.exe` archive attached to a each `x.y.z` release from the [releases page](https://github.com/sharpdx/SharpDX/releases).
  You need to add the correct assemblies and dependencies to your project manually.
  The archive contains
  - a `Bin\Desktop` folder with assemblies for `.NET 4.5+` Desktop Apps
  - a `Bin\StoreApp` folder with assemblies for `PCL .NET 4.6+` 
  

## Supported DirectX APIs per platform

The following table described which DirectX API is accessible on each platform:


| DirectX API      |    Desktop     |   Store - UWP - PCL   |
|------------------|:--------------:|:-------------:|
|Direct3D9         |      Yes       |      -        |
|Direct3D10.x      |      Yes<sup>1</sup>       |      -        |
|Direct3D11.x      |      Yes       |     Yes       |
|Direct3D12.x      |      Yes       |     Yes       |
|D3DCompiler       |      Yes       |     Yes       |
|Direct2D1.x       |      Yes       |     Yes       |
|DirectWrite.x     |      Yes       |     Yes       |
|DirectComposition |      Yes       |      -        |
|DirectManipulation|      Yes       |      -        |
|DXGI1.x           |      Yes       |     Yes       |
|XAudio2           |      Yes       |     Yes       |
|MediaFoundation   |      Yes       |     Yes*      |
|DirectInput       |      Yes       |      -        |
|DirectSound       |      Yes       |      -        |
|RawInput          |      Yes       |      -        |
|XInput            |      Yes       |     Yes       |
|XAct3             |      Yes<sup>1</sup>       |      -        |
|WIC               |      Yes       |     Yes       |

<sub><sup>1</sup> Available only on [previous 2.6.3](https://github.com/sharpdx/SharpDX/releases/tag/2.6.3) release</sub>
