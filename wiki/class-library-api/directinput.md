---
layout: wiki
title: DirectInput API
---

> This page is automatically generated from the assembly documentation.
> 
> It provides links between managed types and methods in the `SharpDX.DirectInput` assembly and the original documentation of the [`DirectInput`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee416842.aspx) API on MSDN.

The DirectInput API is used to process data from a joystick, or other game controller.

- <a href='#api-Enumerations'>Enumerations</a>
- <a href='#api-Structures'>Structures</a>
- <a href='#api-Interfaces'>Interfaces</a>

# <a id="api-Enumerations">Enumerations</a>

Managed | Native
----- | --------------------------------
`CooperativeLevel` | [`DISCL`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee416848.aspx)<p>Flags that specify the cooperative level to associate with the input device.</p>
`DataFormatFlag` | `DIDF`<p>Flags describing other attributes of the </p>
`DeviceAxisMode` | `DIPROPAXISMODE`<p>Device Axis mode.</p>
`DeviceClass` | [`DI8DEVCLASS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinput8.idirectinput8.enumdevices.aspx)<p>Device class filter used by </p>
`DeviceEnumerationFlags` | [`DIEDFL`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinput8.idirectinput8.enumdevices.aspx)<p>Flags that refine the scope of the enumeration used by </p>
`DeviceFlags` | `DIDC`<p>Flags associated with the device.</p>
`DeviceObjectTypeFlags` | [`DIDFT_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/bb152032.aspx)<p>No documentation.</p>
`DeviceType` | [`DI8DEVTYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff538513.aspx)<p>The DIJOYTYPEINFO structure contains information about a joystick type.</p>
`EffectFileFlags` | [`DIFEF`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418645.aspx)<p>To load effects, call the  method.</p>
`EffectFlags` | [`DIEFF`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dieffect.aspx)<p>Used by theIDirectInputDevice8::CreateEffectmethod to initialize a newIDirectInputEffect Interfaceobject.</p>
`EffectParameterFlags` | [`DIEP`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee417546.aspx)<p>You can modify the basic magnitude of some effects by applying an envelope and an offset.</p>
`EffectPlayFlags` | `DIES`<p>No documentation.</p>
`EffectStatus` | [`DIEGES`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputeffect.idirectinputeffect.geteffectstatus.aspx)<p>Retrieves the status of an effect.</p>
`EffectType` | [`DIEFT`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff542434.aspx)<p>No documentation.</p>
`ForceFeedbackCommand` | [`DISFFC`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.sendforcefeedbackcommand.aspx)<p>Sends a command to the device's force-feedback system.</p>
`ForceFeedbackState` | [`DIGFFS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.getforcefeedbackstate.aspx)<p>Retrieves the state of the device's force-feedback system.</p>
`ImageUsage` | [`DIDIFT`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dideviceimageinfo.aspx)<p>Carries information required to display a device image or an overlay image with a callout.</p>
`Key` | [`DIK`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418641.aspx)<p>Keyboard device constants, defined in Dinput.</p>
`ObjectAspect` | [`DIDOI`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee416850.aspx)<p>Before you begin asking for input from a device, you need to know something about its capabilities.</p>
`TextAlignment` | [`DIDAL`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dideviceimageinfo.aspx)<p>Carries information required to display a device image or an overlay image with a callout.</p>

# <a id="api-Structures">Structures</a>

Managed | Native
----- | --------------------------------
`Capabilities` | [`DIDEVCAPS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.didevcaps.aspx)<p>Describes a DirectInput device's capabilities.</p>
`Condition` | [`DICONDITION`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dicondition.aspx)<p>Contains type-specific information for effects that are marked as </p>
`DeviceImage` | [`DIDEVICEIMAGEINFOW`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dideviceimageinfo.aspx)<p>Carries information required to display a device image or an overlay image with a callout.</p>
`DeviceImageHeader` | [`DIDEVICEIMAGEINFOHEADERW`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dideviceimageinfoheader.aspx)<p>Contains information about device images.</p>
`DeviceInstance` | [`DIDEVICEINSTANCEW`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dideviceinstance.aspx)<p>Describes an instance of a DirectInput device.</p>
`DeviceObjectInstance` | [`DIDEVICEOBJECTINSTANCEW`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dideviceobjectinstance.aspx)<p>Describes a device object instance.</p>
`EffectFile` | [`DIFILEEFFECT`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.difileeffect.aspx)<p>Describes data for a force-feedback effect stored in a file.</p>
`EffectInfo` | [`DIEFFECTINFOW`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dieffectinfo.aspx)<p>Used by theIDirectInputDevice8::EnumEffectsandIDirectInputDevice8::GetEffectInfomethods to return information about a particular effect supported by a device.</p>
`EffectParameters` | [`DIEFFECT`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dieffect.aspx)<p>Used by theIDirectInputDevice8::CreateEffectmethod to initialize a newIDirectInputEffect Interfaceobject.</p>
`Envelope` | [`DIENVELOPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dienvelope.aspx)<p>Used by theDIEFFECTstructure to specify the optional envelope parameters for an effect.</p>
`JoystickState` | `???`<p>No documentation.</p>
`MouseState` | `???`<p>No documentation.</p>

# <a id="api-Interfaces">Interfaces</a>

Managed | Native
----- | --------------------------------
`Device`<ul><li>`Acquire`</li><li>`Capabilities`</li><li>`GetEffectInfo`</li><li>`GetForceFeedbackState`</li><li>`Information`</li><li>`Poll`</li><li>`SendForceFeedbackCommand`</li><li>`SetCooperativeLevel`</li><li>`Unacquire`</li><li>`WriteEffectToFile`</li></ul> | [`IDirectInputDevice8W`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee417816.aspx)<ul><li>[`Acquire`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.acquire.aspx)</li><li>[`GetCapabilities`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.getcapabilities.aspx)</li><li>[`GetEffectInfo`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.geteffectinfo.aspx)</li><li>[`GetForceFeedbackState`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.getforcefeedbackstate.aspx)</li><li>[`GetDeviceInfo`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.getdeviceinfo.aspx)</li><li>[`Poll`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.poll.aspx)</li><li>[`SendForceFeedbackCommand`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.sendforcefeedbackcommand.aspx)</li><li>[`SetCooperativeLevel`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.setcooperativelevel.aspx)</li><li>[`Unacquire`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.unacquire.aspx)</li><li>[`WriteEffectToFile`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinputdevice8.idirectinputdevice8.writeeffecttofile.aspx)</li></ul><p>Applications use the methods of the  interface to gain and release access to Microsoft DirectInput devices, manage device properties and information, set behavior, perform initialization, create and play force-feedback effects, and invoke a device's control panel.</p>
`DirectInput`<ul><li>`FindDevice`</li></ul> | [`IDirectInput8W`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee417799.aspx)<ul><li>[`FindDevice`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectinput8.idirectinput8.finddevice.aspx)</li></ul><p>Applications use the methods of the  interface to enumerate, create, and retrieve the status of Microsoft DirectInput devices, initialize the DirectInput object, and invoke an instance of the Microsoft Windows Control Panel.</p>
`Effect`<ul><li>`Download`</li><li>`GetParameters`</li><li>`Guid`</li><li>`SetParameters`</li><li>`Start`</li><li>`Status`</li><li>`Stop`</li><li>`Unload`</li></ul> | `IDirectInputEffect`<ul><li>`Download`</li><li>`GetParameters`</li><li>`GetEffectGuid`</li><li>`SetParameters`</li><li>`Start`</li><li>`GetEffectStatus`</li><li>`Stop`</li><li>`Unload`</li></ul><p>No documentation.</p>

