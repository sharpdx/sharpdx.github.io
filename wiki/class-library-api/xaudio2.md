---
layout: wiki
title: XAudio2 API
---

> This page is automatically generated from the assembly documentation.
> 
> It provides links between managed types and methods in the `SharpDX.XAudio2` assembly and the original documentation of the [`XAudio2`](https://msdn.microsoft.com/en-us/library/windows/desktop/hh405049.aspx) API on MSDN.

XAudio2 is a low-level audio API that provides signal processing and mixing foundation for developing high performance audio engines for games.

- <a href='#api-Enumerations'>Enumerations</a>
- <a href='#api-Structures'>Structures</a>
- <a href='#api-Interfaces'>Interfaces</a>

# <a id="api-Enumerations">Enumerations</a>

Managed | Native
----- | --------------------------------
`BufferFlags` | [`XAUDIO2_BUFFER_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee419230.aspx)<p>XAudio2 constants that specify default parameters, maximum values, and flags.</p>
`DeviceRole` | `XAUDIO2_DEVICE_ROLE`<p>Device role, only valid for XAudio27.</p>
`FilterType` | [`XAUDIO2_FILTER_TYPE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_filter_type.aspx)<p>Indicates the filter type.</p>
`LogType` | `XAUDIO2_LOG_TYPE`<p>No documentation.</p>
`PlayFlags` | [`XAUDIO2_PLAY_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2sourcevoice.ixaudio2sourcevoice.stop.aspx)<p>Stops consumption of audio by the current voice.</p>
`ProcessorSpecifier` | `XAUDIO2_WINDOWS_PROCESSOR_SPECIFIER`<p>No documentation.</p>
`VoiceFlags` | [`XAUDIO2_VOICE_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2.ixaudio2.createsourcevoice.aspx)<p>Creates and configures a source voice.</p>
`VoiceSendFlags` | [`XAUDIO2_VOICE_SEND_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_send_descriptor.aspx)<p>Defines a destination voice that is the target of a send from another voice and specifies whether a filter should be used.</p>
`XAudio2Flags` | [`XAUDIO2_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee419230.aspx)<p>XAudio2 constants that specify default parameters, maximum values, and flags.</p>

# <a id="api-Structures">Structures</a>

Managed | Native
----- | --------------------------------
`AudioBuffer` | [`XAUDIO2_BUFFER`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_buffer.aspx)<p>Represents an audio data buffer, used with .</p>
`DebugConfiguration` | [`XAUDIO2_DEBUG_CONFIGURATION`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_debug_configuration.aspx)<p>Contains the new global debug configuration for XAudio2.</p>
`DeviceDetails` | `XAUDIO2_DEVICE_DETAILS`<p>Details of the device, only valid for XAudio27.</p>
`EffectDescriptor` | [`XAUDIO2_EFFECT_DESCRIPTOR`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_effect_descriptor.aspx)<p>Contains information about an XAPO for use in an effect chain.</p>
`FilterParameters` | [`XAUDIO2_FILTER_PARAMETERS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_filter_parameters.aspx)<p>Defines filter parameters for a source voice.</p>
`MasteringVoice` | [`IXAudio2MasteringVoice`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2masteringvoice.ixaudio2masteringvoice.aspx)<p>A mastering voice is used to represent the audio output device.</p>
`PerformanceData` | [`XAUDIO2_PERFORMANCE_DATA`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_performance_data.aspx)<p>Contains performance information.</p>
`SourceVoice` | [`IXAudio2SourceVoice`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2sourcevoice.ixaudio2sourcevoice.aspx)<p>Use a source voice to submit audio data to the XAudio2 processing pipeline.</p>
`SubmixVoice` | [`IXAudio2SubmixVoice`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2submixvoice.ixaudio2submixvoice.aspx)<p>A submix voice is used primarily for performance improvements and effects processing.</p>
`Voice` | [`IXAudio2Voice`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2voice.ixaudio2voice.setoutputfilterparameters.aspx)<p>Sets the filter parameters on one of this voice's sends.</p>
`VoiceCallback` | [`IXAudio2VoiceCallback`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2voicecallback.ixaudio2voicecallback.aspx)<p>The  interface contains methods that notify the client when certain events happen in a given .</p>
`VoiceDetails` | [`XAUDIO2_VOICE_DETAILS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_voice_details.aspx)<p>Contains information about the creation flags, input channels, and sample rate of a voice.</p>
`VoiceSendDescriptor` | [`XAUDIO2_SEND_DESCRIPTOR`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_send_descriptor.aspx)<p>Defines a destination voice that is the target of a send from another voice and specifies whether a filter should be used.</p>
`VoiceState` | [`XAUDIO2_VOICE_STATE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.xaudio2.xaudio2_voice_state.aspx)<p>Returns the voice's current state and cursor position data.</p>

# <a id="api-Interfaces">Interfaces</a>

Managed | Native
----- | --------------------------------
`XAudio2`<ul><li>`CommitChanges`</li><li>`CommitChanges`</li><li>`DeviceCount`</li><li>`GetDeviceDetails`</li><li>`PerformanceData`</li><li>`SetDebugConfiguration`</li><li>`StartEngine`</li><li>`StopEngine`</li></ul> | [`IXAudio2`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2.ixaudio2.aspx)<ul><li>[`CommitChanges`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2.ixaudio2.commitchanges.aspx)</li><li>`???`</li><li>`GetDeviceCount`</li><li>`???`</li><li>[`GetPerformanceData`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2.ixaudio2.getperformancedata.aspx)</li><li>[`SetDebugConfiguration`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2.ixaudio2.setdebugconfiguration.aspx)</li><li>[`StartEngine`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2.ixaudio2.startengine.aspx)</li><li>[`StopEngine`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.ixaudio2.ixaudio2.stopengine.aspx)</li></ul><p> is the interface for the XAudio2 object that manages all audio engine states, the audio processing thread, the voice graph, and so forth.</p>

