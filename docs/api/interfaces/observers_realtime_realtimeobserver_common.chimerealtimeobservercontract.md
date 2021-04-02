---
layout: default
parent: Interfaces
grand_parent: API
title: "ChimeRealtimeObserverContract"
---

# Interface: ChimeRealtimeObserverContract

[Observers/Realtime/RealtimeObserver.common](../modules/observers_realtime_realtimeobserver_common.md).ChimeRealtimeObserverContract

## Implemented by

* [*ChimeRealtimeObserver*](../classes/observers_realtime_realtimeobserver_common.chimerealtimeobserver.md)

## Table of contents

### Properties

- [onAttendeesDropped](observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesdropped)
- [onAttendeesJoined](observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesjoined)
- [onAttendeesLeft](observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesleft)
- [onAttendeesMuted](observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesmuted)
- [onAttendeesUnmuted](observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onattendeesunmuted)
- [onSignalStrengthChanged](observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onsignalstrengthchanged)
- [onVolumeChanged](observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md#onvolumechanged)

## Properties

### onAttendeesDropped

• `Optional` **onAttendeesDropped**: (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:35](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L35)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:35](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L35)

___

### onAttendeesJoined

• `Optional` **onAttendeesJoined**: (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:33](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L33)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:33](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L33)

___

### onAttendeesLeft

• `Optional` **onAttendeesLeft**: (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:34](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L34)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:34](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L34)

___

### onAttendeesMuted

• `Optional` **onAttendeesMuted**: (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:36](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L36)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:36](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L36)

___

### onAttendeesUnmuted

• `Optional` **onAttendeesUnmuted**: (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]) => *void*

#### Type declaration:

▸ (`attendees`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendees` | [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:37](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L37)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:37](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L37)

___

### onSignalStrengthChanged

• `Optional` **onSignalStrengthChanged**: (`signalUpdate`: [*ChimeSignal*](../classes/signal_signal_common.chimesignal.md)[]) => *void*

#### Type declaration:

▸ (`signalUpdate`: [*ChimeSignal*](../classes/signal_signal_common.chimesignal.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`signalUpdate` | [*ChimeSignal*](../classes/signal_signal_common.chimesignal.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:32](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L32)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:32](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L32)

___

### onVolumeChanged

• `Optional` **onVolumeChanged**: (`volumeUpdate`: [*ChimeVolume*](../classes/volume_volume_common.chimevolume.md)[]) => *void*

#### Type declaration:

▸ (`volumeUpdate`: [*ChimeVolume*](../classes/volume_volume_common.chimevolume.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`volumeUpdate` | [*ChimeVolume*](../classes/volume_volume_common.chimevolume.md)[] |

**Returns:** *void*

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:31](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L31)

Defined in: [Observers/Realtime/RealtimeObserver.common.ts:31](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Realtime/RealtimeObserver.common.ts#L31)
