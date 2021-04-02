---
layout: default
parent: Classes
grand_parent: API
title: "ChimeActiveSpeakerObserver"
---

# Class: ChimeActiveSpeakerObserver

[Observers/ActiveSpeaker/ActiveSpeakerObserver.common](../modules/observers_activespeaker_activespeakerobserver_common.md).ChimeActiveSpeakerObserver

## Implements

* [*ChimeActiveSpeakerObserverContract*](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md)

## Table of contents

### Constructors

- [constructor](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md#constructor)

### Properties

- [android](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md#android)
- [getScoreCallbackIntervalMs](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md#getscorecallbackintervalms)
- [ios](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md#ios)
- [onDetected](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md#ondetected)
- [onScoreChanged](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md#onscorechanged)
- [policy](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md#policy)

## Constructors

### constructor

\+ **new ChimeActiveSpeakerObserver**(`listeners`: [*ChimeActiveSpeakerObserverContract*](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md)): [*ChimeActiveSpeakerObserver*](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md)

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeActiveSpeakerObserverContract*](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md) |

**Returns:** [*ChimeActiveSpeakerObserver*](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md)

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:16](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L16)

## Properties

### android

• **android**: *ActiveSpeakerObserver*

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:4](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L4)

___

### getScoreCallbackIntervalMs

• **getScoreCallbackIntervalMs**: () => *number*

#### Type declaration:

▸ (): *number*

**Returns:** *number*

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:14](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L14)

Implementation of: [ChimeActiveSpeakerObserverContract](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md).[getScoreCallbackIntervalMs](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md#getscorecallbackintervalms)

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:14](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L14)

___

### ios

• **ios**: ActiveSpeakerObserver

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L5)

___

### onDetected

• **onDetected**: (`attendee`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)) => *void*

#### Type declaration:

▸ (`attendee`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendee` | [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md) |

**Returns:** *void*

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:16](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L16)

Implementation of: [ChimeActiveSpeakerObserverContract](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md).[onDetected](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md#ondetected)

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:16](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L16)

___

### onScoreChanged

• **onScoreChanged**: (`attendee`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md), `score`: *number*) => *void*

#### Type declaration:

▸ (`attendee`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md), `score`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendee` | [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md) |
`score` | *number* |

**Returns:** *void*

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:15](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L15)

Implementation of: [ChimeActiveSpeakerObserverContract](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md).[onScoreChanged](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md#onscorechanged)

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:15](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L15)

___

### policy

• **policy**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`android` | *ActiveSpeakerPolicy* |
`ios` | ActiveSpeakerPolicy |

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:6](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L6)
