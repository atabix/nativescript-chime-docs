---
layout: default
parent: Classes
grand_parent: API
title: "ChimeDevice"
---

# Class: ChimeDevice

[Device/Device.common](../modules/device_device_common.md).ChimeDevice

## Hierarchy

* **ChimeDevice**

  ↳ [*ChimeAudio*](audio_audio_common.chimeaudio.md)

  ↳ [*ChimeVideo*](video_video_common.chimevideo.md)

## Table of contents

### Constructors

- [constructor](device_device_common.chimedevice.md#constructor)

### Properties

- [android](device_device_common.chimedevice.md#android)
- [ios](device_device_common.chimedevice.md#ios)

### Methods

- [fromNative](device_device_common.chimedevice.md#fromnative)
- [isAudioDevice](device_device_common.chimedevice.md#isaudiodevice)
- [isVideoDevice](device_device_common.chimedevice.md#isvideodevice)

## Constructors

### constructor

\+ **new ChimeDevice**(`audioVideo`: *AudioVideoFacade* \| AudioVideoFacade): [*ChimeDevice*](device_device_common.chimedevice.md)

#### Parameters:

Name | Type |
:------ | :------ |
`audioVideo` | *AudioVideoFacade* \| AudioVideoFacade |

**Returns:** [*ChimeDevice*](device_device_common.chimedevice.md)

Defined in: [Device/Device.common.ts:3](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L3)

## Properties

### android

• **android**: *AudioVideoFacade*

Defined in: [Device/Device.common.ts:2](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L2)

___

### ios

• **ios**: AudioVideoFacade

Defined in: [Device/Device.common.ts:3](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L3)

## Methods

### fromNative

▸ `Static`**fromNative**(`device`: *MediaDevice* \| *MediaDevice*): [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)

#### Parameters:

Name | Type |
:------ | :------ |
`device` | *MediaDevice* \| *MediaDevice* |

**Returns:** [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)

Defined in: [Device/Device.common.ts:9](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L9)

___

### isAudioDevice

▸ `Static`**isAudioDevice**(`device`: [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`device` | [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md) |

**Returns:** *boolean*

Defined in: [Device/Device.common.ts:13](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L13)

___

### isVideoDevice

▸ `Static`**isVideoDevice**(`device`: [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`device` | [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md) |

**Returns:** *boolean*

Defined in: [Device/Device.common.ts:23](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Device/Device.common.ts#L23)
