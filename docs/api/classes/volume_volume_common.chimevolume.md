---
layout: default
parent: Classes
grand_parent: API
title: "ChimeVolume"
---

# Class: ChimeVolume

[Volume/Volume.common](../modules/volume_volume_common.md).ChimeVolume

## Table of contents

### Constructors

- [constructor](volume_volume_common.chimevolume.md#constructor)

### Properties

- [android](volume_volume_common.chimevolume.md#android)
- [ios](volume_volume_common.chimevolume.md#ios)

### Accessors

- [attendee](volume_volume_common.chimevolume.md#attendee)
- [level](volume_volume_common.chimevolume.md#level)

### Methods

- [fromNative](volume_volume_common.chimevolume.md#fromnative)

## Constructors

### constructor

\+ **new ChimeVolume**(): [*ChimeVolume*](volume_volume_common.chimevolume.md)

**Returns:** [*ChimeVolume*](volume_volume_common.chimevolume.md)

Defined in: [Volume/Volume.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Volume/Volume.common.ts#L5)

## Properties

### android

• **android**: *VolumeUpdate*

Defined in: [Volume/Volume.common.ts:4](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Volume/Volume.common.ts#L4)

___

### ios

• **ios**: *VolumeUpdate*

Defined in: [Volume/Volume.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Volume/Volume.common.ts#L5)

## Accessors

### attendee

• get **attendee**(): [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)

**Returns:** [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)

Defined in: [Volume/Volume.common.ts:11](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Volume/Volume.common.ts#L11)

___

### level

• get **level**(): [*ChimeVolumeLevel*](../modules/volume_volume_common.md#chimevolumelevel)

**Returns:** [*ChimeVolumeLevel*](../modules/volume_volume_common.md#chimevolumelevel)

Defined in: [Volume/Volume.common.ts:18](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Volume/Volume.common.ts#L18)

## Methods

### fromNative

▸ `Static`**fromNative**(`volume`: *VolumeUpdate* \| *VolumeUpdate*): [*ChimeVolume*](volume_volume_common.chimevolume.md)

#### Parameters:

Name | Type |
:------ | :------ |
`volume` | *VolumeUpdate* \| *VolumeUpdate* |

**Returns:** [*ChimeVolume*](volume_volume_common.chimevolume.md)

Defined in: [Volume/Volume.common.ts:22](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Volume/Volume.common.ts#L22)
