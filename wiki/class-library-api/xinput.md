---
layout: wiki
title: XInput API
---

> This page is automatically generated from the assembly documentation.
> 
> It provides links between managed types and methods in the `SharpDX.XInput` assembly and the original documentation of the [`XInput`](https://msdn.microsoft.com/en-us/library/windows/desktop/hh405053.aspx) API on MSDN.

XInput Game Controller API enables applications to receive input from the Xbox 360 Controller for Windows.

- <a href='#api-Enumerations'>Enumerations</a>
- <a href='#api-Structures'>Structures</a>
- <a href='#api-Interfaces'>Interfaces</a>

# <a id="api-Enumerations">Enumerations</a>

Managed | Native
----- | --------------------------------
`BatteryDeviceType` | [`BATTERY_DEVTYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinputgetbatteryinformation.aspx)<p>Retrieves the battery type and charge status of a wireless controller.</p>
`BatteryLevel` | `BATTERY_LEVEL`<p>No documentation.</p>
`BatteryType` | [`BATTERY_TYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_battery_information.aspx)<p>Contains information on battery type and charge state.</p>
`CapabilityFlags` | [`XINPUT_CAPS_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_capabilities.aspx)<p>Describes the capabilities of a connected controller.</p>
`DeviceQueryType` | `XINPUT_DEVQUERYTYPE`<p>No documentation.</p>
`DeviceSubType` | [`XINPUT_DEVSUBTYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/hh405050.aspx)<p>A table of controller subtypes available in XInput.</p>
`DeviceType` | [`XINPUT_DEVTYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_capabilities.aspx)<p>Describes the capabilities of a connected controller.</p>
`GamepadButtonFlags` | [`XINPUT_GAMEPAD_BUTTON_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_gamepad.aspx)<p>Describes the current state of the Xbox 360 Controller.</p>
`GamepadKeyCode` | [`XINPUT_GAMEPAD_KEY_CODE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_keystroke.aspx)<p>Specifies keystroke data returned by .</p>
`KeyStrokeFlags` | [`XINPUT_KEYSTROKE_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_keystroke.aspx)<p>Specifies keystroke data returned by .</p>
`UserIndex` | [`XUSER_INDEX`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinputgetkeystroke.aspx)<p>Retrieves a gamepad input event.</p>

# <a id="api-Structures">Structures</a>

Managed | Native
----- | --------------------------------
`BatteryInformation` | [`XINPUT_BATTERY_INFORMATION`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_battery_information.aspx)<p>Contains information on battery type and charge state.</p>
`Capabilities` | [`XINPUT_CAPABILITIES`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_capabilities.aspx)<p>Describes the capabilities of a connected controller.</p>
`Gamepad` | [`XINPUT_GAMEPAD`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_gamepad.aspx)<p>Describes the current state of the Xbox 360 Controller.</p>
`Keystroke` | [`XINPUT_KEYSTROKE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_keystroke.aspx)<p>Specifies keystroke data returned by .</p>
`State` | [`XINPUT_STATE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_state.aspx)<p>Represents the state of a controller.</p>
`Vibration` | [`XINPUT_VIBRATION`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.xinput_vibration.aspx)<p>Specifies motor speed levels for the vibration function of a controller.</p>

# <a id="api-Interfaces">Interfaces</a>

Managed | Native
----- | --------------------------------

