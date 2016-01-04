---
layout: wiki
title: DirectSound API
---

> This page is automatically generated from the assembly documentation.
> 
> It provides links between managed types and methods in the `SharpDX.DirectSound` assembly and the original documentation of the [`DirectSound`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee416960.aspx) API on MSDN.

DirectSound API (deprecated)

- <a href='#api-Enumerations'>Enumerations</a>
- <a href='#api-Structures'>Structures</a>
- <a href='#api-Interfaces'>Interfaces</a>

# <a id="api-Enumerations">Enumerations</a>

Managed | Native
----- | --------------------------------
`AcousticEchoCancelMode` | [`DSCFX_AEC_MODE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dscfxaec.aspx)<p>The </p>
`AcousticEchoCancelStatus` | [`DSCFX_AEC_STATUS`](https://msdn.microsoft.com/en-us/library/windows/desktop/ff537230.aspx)<p>The KSPROPERTY_AEC_STATUS property is used to monitor the status of an AEC node (KSNODETYPE_ACOUSTIC_ECHO_CANCEL).</p>
`BufferFlags` | `DSBCAPS_FLAGS`<p>No documentation.</p>
`BufferStatus` | `DSBSTATUS_FLAGS`<p>No documentation.</p>
`CapabilitiesFlags` | [`DSCAPS_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dscaps.aspx)<p>The </p>
`CaptureBufferCapabilitiesFlags` | `DSCBCAPS_FLAGS`<p>No documentation.</p>
`CaptureBufferStatusFlags` | `DSCBSTATUS_FLAGS`<p>No documentation.</p>
`CaptureCapabilitiesFlags` | [`DSCCAPS_FLAGS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsccaps.aspx)<p>The </p>
`CaptureEffectResult` | [`DSCFX_ENUM`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsceffectdesc.aspx)<p>The </p>
`CooperativeLevel` | `DSSCL_ENUM`<p>No documentation.</p>
`I3DL2MaterialPreset` | `DSOUND_ENUM_1`<p>No documentation.</p>
`I3DL2ReverbPreset` | `DSOUND_ENUM_2`<p>No documentation.</p>
`LockFlags` | `DSBLOCK_ENUM`<p>No documentation.</p>
`Mode3D` | [`DS3DMODE`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsound3dbuffer8.idirectsound3dbuffer8.getmode.aspx)<p>The GetMode method retrieves the operation mode for 3D sound processing.</p>
`PlayFlags` | `DSBPLAY_FLAGS`<p>No documentation.</p>
`SoundEffectResult` | `DSOUND_ENUM_0`<p>No documentation.</p>
`SpeakerConfiguration` | `DSSPEAKER_ENUM`<p>No documentation.</p>
`SpeakerGeometry` | `DSSPEAKER_GEOMETRY_ENUM`<p>No documentation.</p>

# <a id="api-Structures">Structures</a>

Managed | Native
----- | --------------------------------
`AcousticEchoCancelSettings` | [`DSCFXAec`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dscfxaec.aspx)<p>The </p>
`Buffer3DSettings` | [`DS3DBUFFER`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.ds3dbuffer.aspx)<p>The </p>
`BufferCapabilities` | `DSBCAPS`<p>No documentation.</p>
`Capabilities` | [`DSCAPS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dscaps.aspx)<p>The </p>
`CaptureBufferCapabilities` | [`DSCBCAPS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dscbcaps.aspx)<p>The </p>
`CaptureBufferDescription` | [`DSCBUFFERDESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dscbufferdesc.aspx)<p>The </p>
`CaptureCapabilities` | [`DSCCAPS`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsccaps.aspx)<p>The </p>
`CaptureEffectDescription` | [`DSCEFFECTDESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsceffectdesc.aspx)<p>The </p>
`ChorusSettings` | [`DSFXChorus`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsfxchorus.aspx)<p>The </p>
`CompressorSettings` | [`DSFXCompressor`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsfxcompressor.aspx)<p>The </p>
`DistortionSettings` | [`DSFXDistortion`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsfxdistortion.aspx)<p>The </p>
`EchoSettings` | [`DSFXEcho`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsfxecho.aspx)<p>The </p>
`FlangerSettings` | [`DSFXFlanger`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsfxflanger.aspx)<p>The </p>
`GargleSettings` | [`DSFXGargle`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsfxgargle.aspx)<p>The </p>
`I3DL2ReverbSettings` | [`DSFXI3DL2Reverb`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsfxi3dl2reverb.aspx)<p>The </p>
`Listener3DSettings` | [`DS3DLISTENER`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.ds3dlistener.aspx)<p>The </p>
`NoiseSuppressSettings` | [`DSCFXNoiseSuppress`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dscfxnoisesuppress.aspx)<p>The </p>
`NotificationPosition` | `DSBPOSITIONNOTIFY`<p>No documentation.</p>
`ParametricEqualizerSettings` | [`DSFXParamEq`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsfxparameq.aspx)<p>The </p>
`SoundBufferDescription` | [`DSBUFFERDESC`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsbufferdesc.aspx)<p>The </p>
`WavesReverbSettings` | [`DSFXWavesReverb`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.reference.dsfxwavesreverb.aspx)<p>The </p>

# <a id="api-Interfaces">Interfaces</a>

Managed | Native
----- | --------------------------------
`AcousticEchoCancel`<ul><li>`AllParameters`</li><li>`Reset`</li><li>`Status`</li></ul> | [`IDirectSoundCaptureFXAec`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418187.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundcapturefxaec8.idirectsoundcapturefxaec8.getallparameters.aspx)</li><li>[`Reset`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundcapturefxaec8.idirectsoundcapturefxaec8.reset.aspx)</li><li>[`GetStatus`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundcapturefxaec8.idirectsoundcapturefxaec8.getstatus.aspx)</li></ul><p>The IDirectSoundCaptureFXAec8 interface is used to set and retrieve parameters on a capture buffer that supports acoustic echo cancellation.</p>
`CaptureBuffer`<ul><li>`.ctor`</li><li>`GetEffect`</li></ul> | [`IDirectSoundCaptureBuffer8`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418162.aspx)<ul><li>`???`</li><li>`???`</li></ul><p>The  interface is used to manipulate sound capture buffers.</p>
`CaptureBufferBase`<ul><li>`Capabilities`</li><li>`Lock`</li><li>`Start`</li><li>`Stop`</li><li>`Unlock`</li></ul> | [`IDirectSoundCaptureBuffer`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418162.aspx)<ul><li>[`GetCaps`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundcapturebuffer8.idirectsoundcapturebuffer8.getcaps.aspx)</li><li>`???`</li><li>[`Start`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundcapturebuffer8.idirectsoundcapturebuffer8.start.aspx)</li><li>[`Stop`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundcapturebuffer8.idirectsoundcapturebuffer8.stop.aspx)</li><li>`???`</li></ul><p>The  interface is used to manipulate sound capture buffers.</p>
`Chorus`<ul><li>`AllParameters`</li></ul> | [`IDirectSoundFXChorus`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418208.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundfxchorus8.idirectsoundfxchorus8.getallparameters.aspx)</li></ul><p>The IDirectSoundFXChorus8 interface is used to set and retrieve effect parameters on a buffer that supports chorus.</p>
`Compressor`<ul><li>`AllParameters`</li></ul> | [`IDirectSoundFXCompressor`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418215.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundfxcompressor8.idirectsoundfxcompressor8.getallparameters.aspx)</li></ul><p>The IDirectSoundFXCompressor8 interface is used to set and retrieve effect parameters on a buffer that supports compression.</p>
`DirectSound`<ul><li>`DuplicateSoundBuffer`</li></ul> | [`IDirectSound8`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418035.aspx)<ul><li>`DuplicateSoundBuffer`</li></ul><p>The  interface is used to create buffer objects, manage devices, and set up the environment.</p>
`DirectSoundBase`<ul><li>`Capabilities`</li><li>`Compact`</li><li>`SetCooperativeLevel`</li></ul> | [`IDirectSound`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418035.aspx)<ul><li>[`GetCaps`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsound8.idirectsound8.getcaps.aspx)</li><li>[`Compact`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsound8.idirectsound8.compact.aspx)</li><li>[`SetCooperativeLevel`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsound8.idirectsound8.setcooperativelevel.aspx)</li></ul><p>The  interface is used to create buffer objects, manage devices, and set up the environment.</p>
`DirectSoundCapture`<ul><li>`Capabilities`</li></ul> | [`IDirectSoundCapture`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418154.aspx)<ul><li>[`GetCaps`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundcapture8.idirectsoundcapture8.getcaps.aspx)</li></ul><p>The IDirectSoundCapture8 interface is used to create sound capture buffers.</p>
`Distortion`<ul><li>`AllParameters`</li></ul> | [`IDirectSoundFXDistortion`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418218.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundfxdistortion8.idirectsoundfxdistortion8.getallparameters.aspx)</li></ul><p>The IDirectSoundFXDistortion8 interface is used to set and retrieve effect parameters on a buffer that supports distortion.</p>
`Echo`<ul><li>`AllParameters`</li></ul> | [`IDirectSoundFXEcho`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418221.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundfxecho8.idirectsoundfxecho8.getallparameters.aspx)</li></ul><p>The IDirectSoundFXEcho8 interface is used to set and retrieve effect parameters on a buffer that supports echo.</p>
`Flanger`<ul><li>`AllParameters`</li></ul> | [`IDirectSoundFXFlanger`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418225.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundfxflanger8.idirectsoundfxflanger8.getallparameters.aspx)</li></ul><p>The IDirectSoundFXFlanger8 interface is used to set and retrieve effect parameters on a buffer that supports flange.</p>
`FullDuplex` | [`IDirectSoundFullDuplex`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418204.aspx)<p>The IDirectSoundFullDuplex8 interface represents a full-duplex stream.</p>
`Gargle`<ul><li>`AllParameters`</li></ul> | [`IDirectSoundFXGargle`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418228.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundfxgargle8.idirectsoundfxgargle8.getallparameters.aspx)</li></ul><p>The IDirectSoundFXGargle8 interface is used to set and retrieve effect parameters on a buffer that supports amplitude modulation.</p>
`I3DL2Reverb`<ul><li>`AllParameters`</li><li>`Preset`</li><li>`Quality`</li></ul> | [`IDirectSoundFXI3DL2Reverb`](https://msdn.microsoft.com/en-us/library/windows/desktop/bb280379.aspx)<ul><li>`GetAllParameters`</li><li>`GetPreset`</li><li>`GetQuality`</li></ul><p>No documentation.</p>
`NoiseSuppress`<ul><li>`AllParameters`</li><li>`Reset`</li></ul> | [`IDirectSoundCaptureFXNoiseSuppress`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418197.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundcapturefxnoisesuppress8.idirectsoundcapturefxnoisesuppress8.getallparameters.aspx)</li><li>[`Reset`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundcapturefxnoisesuppress8.idirectsoundcapturefxnoisesuppress8.reset.aspx)</li></ul><p>The IDirectSoundCaptureFXNoiseSuppress8 interface is used to set and retrieve parameters on a capture buffer that supports noise suppression.</p>
`ParametricEqualizer`<ul><li>`AllParameters`</li></ul> | [`IDirectSoundFXParamEq`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418238.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundfxparameq8.idirectsoundfxparameq8.getallparameters.aspx)</li></ul><p>The IDirectSoundFXParamEq8 interface is used to set and retrieve effect parameters on a buffer that supports parametric equalizer effects.</p>
`SecondarySoundBuffer`<ul><li>`AcquireResources`</li><li>`GetEffect`</li><li>`SetEffect`</li></ul> | [`IDirectSoundBuffer8`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418055.aspx)<ul><li>[`AcquireResources`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.acquireresources.aspx)</li><li>`???`</li><li>`???`</li></ul><p>The  interface is used to manage sound buffers.</p>
`SoundBuffer`<ul><li>`Capabilities`</li><li>`CurrentPosition`</li><li>`Format`</li><li>`Frequency`</li><li>`GetCurrentPosition`</li><li>`GetFormat`</li><li>`Initialize`</li><li>`Lock`</li><li>`Pan`</li><li>`Play`</li><li>`Restore`</li><li>`Status`</li><li>`Stop`</li><li>`Unlock`</li><li>`Volume`</li></ul> | [`IDirectSoundBuffer`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418055.aspx)<ul><li>[`GetCaps`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.getcaps.aspx)</li><li>[`SetCurrentPosition`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.setcurrentposition.aspx)</li><li>`???`</li><li>[`GetFrequency`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.getfrequency.aspx)</li><li>[`GetCurrentPosition`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.getcurrentposition.aspx)</li><li>[`GetFormat`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.getformat.aspx)</li><li>[`Initialize`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.initialize.aspx)</li><li>`???`</li><li>[`GetPan`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.getpan.aspx)</li><li>`???`</li><li>[`Restore`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.restore.aspx)</li><li>[`GetStatus`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.getstatus.aspx)</li><li>[`Stop`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.stop.aspx)</li><li>`???`</li><li>[`GetVolume`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundbuffer8.idirectsoundbuffer8.getvolume.aspx)</li></ul><p>The  interface is used to manage sound buffers.</p>
`SoundBuffer3D` | [`IDirectSound3DBuffer`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee417960.aspx)<p>The IDirectSound3DBuffer8 interface is used to retrieve and set parameters that describe the position, orientation, and environment of a sound buffer in 3D space.</p>
`SoundListener3D`<ul><li>`CommitDeferredSettings`</li></ul> | [`IDirectSound3DListener`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418003.aspx)<ul><li>[`CommitDeferredSettings`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsound3dlistener8.idirectsound3dlistener8.commitdeferredsettings.aspx)</li></ul><p>The IDirectSound3DListener8 interface is used to retrieve and set parameters that describe a listener's position, orientation, and listening environment in 3D space.</p>
`WavesReverb`<ul><li>`AllParameters`</li></ul> | [`IDirectSoundFXWavesReverb`](https://msdn.microsoft.com/en-us/library/windows/desktop/ee418241.aspx)<ul><li>[`GetAllParameters`](https://msdn.microsoft.com/en-us/library/windows/desktop/microsoft.directx_sdk.idirectsoundfxwavesreverb8.idirectsoundfxwavesreverb8.getallparameters.aspx)</li></ul><p>The IDirectSoundFXWavesReverb8 interface is used to set and retrieve effect parameters on a buffer that supports Waves reverberation.</p>

