---
layout: default
parent: Classes
grand_parent: API
title: "ChimeDeviceObserver"
---

# Class: ChimeDeviceObserver

[Observers/Device/DeviceObserver.common](../modules/observers_device_deviceobserver_common.md).ChimeDeviceObserver

## Implements

* [*ChimeDeviceObserverContract*](../interfaces/observers_device_deviceobserver_common.chimedeviceobservercontract.md)

## Table of contents

### Constructors

- [constructor](observers_device_deviceobserver_common.chimedeviceobserver.md#constructor)

### Properties

- [android](observers_device_deviceobserver_common.chimedeviceobserver.md#android)
- [ios](observers_device_deviceobserver_common.chimedeviceobserver.md#ios)
- [onAudioDeviceChanged](observers_device_deviceobserver_common.chimedeviceobserver.md#onaudiodevicechanged)

## Constructors

### constructor

\+ **new ChimeDeviceObserver**(`listeners`: [*ChimeDeviceObserverContract*](../interfaces/observers_device_deviceobserver_common.chimedeviceobservercontract.md)): [*ChimeDeviceObserver*](observers_device_deviceobserver_common.chimedeviceobserver.md)

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeDeviceObserverContract*](../interfaces/observers_device_deviceobserver_common.chimedeviceobservercontract.md) |

**Returns:** [*ChimeDeviceObserver*](observers_device_deviceobserver_common.chimedeviceobserver.md)

Defined in: [Observers/Device/DeviceObserver.common.ts:8](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Device/DeviceObserver.common.ts#L8)

## Properties

### android

• **android**: *DeviceChangeObserver*

Defined in: [Observers/Device/DeviceObserver.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Device/DeviceObserver.common.ts#L5)

___

### ios

• **ios**: DeviceChangeObserver

Defined in: [Observers/Device/DeviceObserver.common.ts:6](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Device/DeviceObserver.common.ts#L6)

___

### onAudioDeviceChanged

• **onAudioDeviceChanged**: (`devices`: [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)[]) => *void*

#### Type declaration:

▸ (`devices`: [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`devices` | [*ChimeMediaDevice*](../interfaces/device_device_common.chimemediadevice.md)[] |

**Returns:** *void*

Defined in: [Observers/Device/DeviceObserver.common.ts:8](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Device/DeviceObserver.common.ts#L8)

Implementation of: [ChimeDeviceObserverContract](../interfaces/observers_device_deviceobserver_common.chimedeviceobservercontract.md).[onAudioDeviceChanged](../interfaces/observers_device_deviceobserver_common.chimedeviceobservercontract.md#onaudiodevicechanged)

Defined in: [Observers/Device/DeviceObserver.common.ts:8](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Device/DeviceObserver.common.ts#L8)
