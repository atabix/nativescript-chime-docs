---
layout: default
parent: Classes
grand_parent: API
title: "ChimeVideo"
---

# Class: ChimeVideo

[Video/Video.common](../modules/video_video_common.md).ChimeVideo

## Hierarchy

* [*ChimeDevice*](device_device_common.chimedevice.md)

  ↳ **ChimeVideo**

## Implements

* [*ChimeVideoContract*](../interfaces/video_video_common.chimevideocontract.md)

## Table of contents

### Constructors

- [constructor](video_video_common.chimevideo.md#constructor)

### Properties

- [android](video_video_common.chimevideo.md#android)
- [ios](video_video_common.chimevideo.md#ios)

### Methods

- [bindView](video_video_common.chimevideo.md#bindview)
- [getActiveCamera](video_video_common.chimevideo.md#getactivecamera)
- [getDevices](video_video_common.chimevideo.md#getdevices)
- [startLocal](video_video_common.chimevideo.md#startlocal)
- [startRemote](video_video_common.chimevideo.md#startremote)
- [stopLocal](video_video_common.chimevideo.md#stoplocal)
- [stopRemote](video_video_common.chimevideo.md#stopremote)
- [switchCamera](video_video_common.chimevideo.md#switchcamera)
- [unbindView](video_video_common.chimevideo.md#unbindview)
- [fromNative](video_video_common.chimevideo.md#fromnative)
- [isAudioDevice](video_video_common.chimevideo.md#isaudiodevice)
- [isVideoDevice](video_video_common.chimevideo.md#isvideodevice)

## Constructors

### constructor

\+ **new ChimeVideo**(`audioVideo`: *AudioVideoFacade* \| AudioVideoFacade): [*ChimeVideo*](video_video_common.chimevideo.md)

#### Parameters:

Name | Type |
:------ | :------ |
`audioVideo` | *AudioVideoFacade* \| AudioVideoFacade |

**Returns:** [*ChimeVideo*](video_video_common.chimevideo.md)

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

### bindView

▸ **bindView**(`view`: *VideoView*, `tile`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`view` | *VideoView* |
`tile` | *number* |

**Returns:** *void*

Implementation of: [ChimeVideoContract](../interfaces/video_video_common.chimevideocontract.md)

Defined in: [Video/Video.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Video/Video.common.ts#L5)

___

### getActiveCamera

▸ **getActiveCamera**(): [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)

**Returns:** [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)

Implementation of: [ChimeVideoContract](../interfaces/video_video_common.chimevideocontract.md)

Defined in: [Video/Video.common.ts:13](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Video/Video.common.ts#L13)

___

### getDevices

▸ **getDevices**(): [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)[]

**Returns:** [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)[]

Defined in: [Video/Video.common.ts:37](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Video/Video.common.ts#L37)

___

### startLocal

▸ **startLocal**(): *void*

**Returns:** *void*

Implementation of: [ChimeVideoContract](../interfaces/video_video_common.chimevideocontract.md)

Defined in: [Video/Video.common.ts:25](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Video/Video.common.ts#L25)

___

### startRemote

▸ **startRemote**(): *void*

**Returns:** *void*

Implementation of: [ChimeVideoContract](../interfaces/video_video_common.chimevideocontract.md)

Defined in: [Video/Video.common.ts:21](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Video/Video.common.ts#L21)

___

### stopLocal

▸ **stopLocal**(): *void*

**Returns:** *void*

Implementation of: [ChimeVideoContract](../interfaces/video_video_common.chimevideocontract.md)

Defined in: [Video/Video.common.ts:33](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Video/Video.common.ts#L33)

___

### stopRemote

▸ **stopRemote**(): *void*

**Returns:** *void*

Implementation of: [ChimeVideoContract](../interfaces/video_video_common.chimevideocontract.md)

Defined in: [Video/Video.common.ts:29](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Video/Video.common.ts#L29)

___

### switchCamera

▸ **switchCamera**(): *void*

**Returns:** *void*

Defined in: [Video/Video.common.ts:17](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Video/Video.common.ts#L17)

___

### unbindView

▸ **unbindView**(`tileId`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileId` | *number* |

**Returns:** *void*

Implementation of: [ChimeVideoContract](../interfaces/video_video_common.chimevideocontract.md)

Defined in: [Video/Video.common.ts:9](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Video/Video.common.ts#L9)

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
