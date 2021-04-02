---
layout: default
parent: Classes
grand_parent: API
title: "ChimeAudio"
---

# Class: ChimeAudio

[Audio/Audio.common](../modules/audio_audio_common.md).ChimeAudio

## Hierarchy

* [*ChimeDevice*](device_device_common.chimedevice.md)

  ↳ **ChimeAudio**

## Implements

* [*ChimeAudioContract*](../interfaces/audio_audio_common.chimeaudiocontract.md)

## Table of contents

### Constructors

- [constructor](audio_audio_common.chimeaudio.md#constructor)

### Properties

- [android](audio_audio_common.chimeaudio.md#android)
- [ios](audio_audio_common.chimeaudio.md#ios)

### Methods

- [getDevices](audio_audio_common.chimeaudio.md#getdevices)
- [mute](audio_audio_common.chimeaudio.md#mute)
- [setDevice](audio_audio_common.chimeaudio.md#setdevice)
- [unmute](audio_audio_common.chimeaudio.md#unmute)
- [fromNative](audio_audio_common.chimeaudio.md#fromnative)
- [isAudioDevice](audio_audio_common.chimeaudio.md#isaudiodevice)
- [isVideoDevice](audio_audio_common.chimeaudio.md#isvideodevice)

## Constructors

### constructor

\+ **new ChimeAudio**(`audioVideo`: *AudioVideoFacade* \| AudioVideoFacade): [*ChimeAudio*](audio_audio_common.chimeaudio.md)

#### Parameters:

Name | Type |
:------ | :------ |
`audioVideo` | *AudioVideoFacade* \| AudioVideoFacade |

**Returns:** [*ChimeAudio*](audio_audio_common.chimeaudio.md)

Inherited from: [ChimeDevice](device_device_common.chimedevice.md)

Defined in: [Device/Device.common.ts:3](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L3)

## Properties

### android

• **android**: *AudioVideoFacade*

Inherited from: [ChimeDevice](device_device_common.chimedevice.md).[android](device_device_common.chimedevice.md#android)

Defined in: [Device/Device.common.ts:2](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L2)

___

### ios

• **ios**: AudioVideoFacade

Inherited from: [ChimeDevice](device_device_common.chimedevice.md).[ios](device_device_common.chimedevice.md#ios)

Defined in: [Device/Device.common.ts:3](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L3)

## Methods

### getDevices

▸ **getDevices**(): [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)[]

**Returns:** [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)[]

Implementation of: [ChimeAudioContract](../interfaces/audio_audio_common.chimeaudiocontract.md)

Defined in: [Audio/Audio.common.ts:12](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Audio/Audio.common.ts#L12)

___

### mute

▸ **mute**(): *void*

**Returns:** *void*

Implementation of: [ChimeAudioContract](../interfaces/audio_audio_common.chimeaudiocontract.md)

Defined in: [Audio/Audio.common.ts:4](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Audio/Audio.common.ts#L4)

___

### setDevice

▸ **setDevice**(`device`: [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`device` | [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md) |

**Returns:** *void*

Implementation of: [ChimeAudioContract](../interfaces/audio_audio_common.chimeaudiocontract.md)

Defined in: [Audio/Audio.common.ts:16](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Audio/Audio.common.ts#L16)

___

### unmute

▸ **unmute**(): *void*

**Returns:** *void*

Implementation of: [ChimeAudioContract](../interfaces/audio_audio_common.chimeaudiocontract.md)

Defined in: [Audio/Audio.common.ts:8](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Audio/Audio.common.ts#L8)

___

### fromNative

▸ `Static`**fromNative**(`device`: *MediaDevice* \| *MediaDevice*): [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)

#### Parameters:

Name | Type |
:------ | :------ |
`device` | *MediaDevice* \| *MediaDevice* |

**Returns:** [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)

Inherited from: [ChimeDevice](device_device_common.chimedevice.md)

Defined in: [Device/Device.common.ts:9](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L9)

___

### isAudioDevice

▸ `Static`**isAudioDevice**(`device`: [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`device` | [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md) |

**Returns:** *boolean*

Inherited from: [ChimeDevice](device_device_common.chimedevice.md)

Defined in: [Device/Device.common.ts:13](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L13)

___

### isVideoDevice

▸ `Static`**isVideoDevice**(`device`: [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`device` | [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md) |

**Returns:** *boolean*

Inherited from: [ChimeDevice](device_device_common.chimedevice.md)

Defined in: [Device/Device.common.ts:23](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L23)
