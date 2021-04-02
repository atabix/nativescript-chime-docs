---
layout: default
parent: Classes
grand_parent: API
title: "ChimeRealtimeObserver"
---

# Class: ChimeRealtimeObserver

[Observers/Realtime/RealtimeObserver.common](../modules/observers_realtime_realtimeobserver_common.md).ChimeRealtimeObserver

## Implements

* [*ChimeRealtimeObserverContract*](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md)

## Table of contents

### Constructors

- [constructor](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#constructor)

### Properties

- [android](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#android)
- [ios](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#ios)
- [onAttendeesDropped](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#onattendeesdropped)
- [onAttendeesJoined](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#onattendeesjoined)
- [onAttendeesLeft](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#onattendeesleft)
- [onAttendeesMuted](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#onattendeesmuted)
- [onAttendeesUnmuted](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#onattendeesunmuted)
- [onSignalStrengthChanged](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#onsignalstrengthchanged)
- [onVolumeChanged](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md#onvolumechanged)

## Constructors

### constructor

\+ **new ChimeRealtimeObserver**(`listeners`: [*ChimeRealtimeObserverContract*](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md)): [*ChimeRealtimeObserver*](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md)

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeRealtimeObserverContract*](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md) |

**Returns:** [*ChimeRealtimeObserver*](observers_realtime_realtimeobserver_common.chimerealtimeobserver.md)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:15](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L15)

## Properties

### android

• **android**: *RealtimeObserver*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:6](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L6)

___

### ios

• **ios**: RealtimeObserver

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:7](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L7)

___

### onAttendeesDropped

• **onAttendeesDropped**: (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:13](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L13)

Implementation of: [ChimeRealtimeObserverContract](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md).[onAttendeesDropped](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesdropped)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:13](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L13)

___

### onAttendeesJoined

• **onAttendeesJoined**: (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:11](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L11)

Implementation of: [ChimeRealtimeObserverContract](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md).[onAttendeesJoined](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesjoined)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:11](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L11)

___

### onAttendeesLeft

• **onAttendeesLeft**: (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:12](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L12)

Implementation of: [ChimeRealtimeObserverContract](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md).[onAttendeesLeft](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesleft)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:12](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L12)

___

### onAttendeesMuted

• **onAttendeesMuted**: (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:14](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L14)

Implementation of: [ChimeRealtimeObserverContract](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md).[onAttendeesMuted](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesmuted)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:14](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L14)

___

### onAttendeesUnmuted

• **onAttendeesUnmuted**: (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:15](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L15)

Implementation of: [ChimeRealtimeObserverContract](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md).[onAttendeesUnmuted](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesunmuted)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:15](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L15)

___

### onSignalStrengthChanged

• **onSignalStrengthChanged**: (`signalUpdate`: [*ChimeSignal*](signal_signal_common.chimesignal.md)[]) => *void*

#### Type declaration:

▸ (`signalUpdate`: [*ChimeSignal*](signal_signal_common.chimesignal.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`signalUpdate` | [*ChimeSignal*](signal_signal_common.chimesignal.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:10](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L10)

Implementation of: [ChimeRealtimeObserverContract](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md).[onSignalStrengthChanged](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onsignalstrengthchanged)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:10](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L10)

___

### onVolumeChanged

• **onVolumeChanged**: (`volumeUpdate`: [*ChimeVolume*](volume_volume_common.chimevolume.md)[]) => *void*

#### Type declaration:

▸ (`volumeUpdate`: [*ChimeVolume*](volume_volume_common.chimevolume.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`volumeUpdate` | [*ChimeVolume*](volume_volume_common.chimevolume.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:9](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L9)

Implementation of: [ChimeRealtimeObserverContract](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md).[onVolumeChanged](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onvolumechanged)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:9](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L9)
