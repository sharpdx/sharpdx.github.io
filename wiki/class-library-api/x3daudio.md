---
layout: wiki
title: X3DAudio API
---

> This page is automatically generated from the assembly documentation.
> 
> It provides links between managed types and methods in the `SharpDX.XAudio2` assembly and the original documentation of the [`X3DAudio`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee415714.aspx) API on MSDN.

X3DAudio is an API used in conjunction with XAudio2 to create the illusion of a sound coming from a point in 3D space.

- <a href='#api-Enumerations'>Enumerations</a>
- <a href='#api-Structures'>Structures</a>
- <a href='#api-Interfaces'>Interfaces</a>

# <a id="api-Enumerations">Enumerations</a>

Managed | Native
----- | --------------------------------
`CalculateFlags` | `X3DAudioCalculateFlags`<p>No documentation.</p>

# <a id="api-Structures">Structures</a>

Managed | Native
----- | --------------------------------
`Cone` | [`X3DAUDIO_CONE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.x3daudio.x3daudio_cone.aspx)<p>Specifies directionality for a single-channel non-LFE emitter by scaling DSP behavior with respect to the emitter's orientation.</p>
`CurvePoint` | [`X3DAUDIO_DISTANCE_CURVE_POINT`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.x3daudio.x3daudio_distance_curve_point.aspx)<p>Defines a DSP setting at a given normalized distance.</p>
`DspSettings` | [`X3DAUDIO_DSP_SETTINGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.x3daudio.x3daudio_dsp_settings.aspx)<p>Receives the results from a call to X3DAudioCalculate.</p>
`Emitter` | [`X3DAUDIO_EMITTER`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.x3daudio.x3daudio_emitter.aspx)<p>Defines a single-point or multiple-point 3D audio source that is used with an arbitrary number of sound channels.</p>
`Listener` | [`X3DAUDIO_LISTENER`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.x3daudio.x3daudio_listener.aspx)<p>Defines a point of 3D audio reception.</p>

# <a id="api-Interfaces">Interfaces</a>

Managed | Native
----- | --------------------------------

