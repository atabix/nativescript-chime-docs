---
layout: default
parent: Interfaces
grand_parent: API
title: "ChimeActiveSpeakerObserverContract"
---

# Interface: ChimeActiveSpeakerObserverContract

[Observers/ActiveSpeaker/ActiveSpeakerObserver.common](../modules/observers_activespeaker_activespeakerobserver_common.md).ChimeActiveSpeakerObserverContract

## Implemented by

* [*ChimeActiveSpeakerObserver*](../classes/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobserver.md)

## Table of contents

### Properties

- [getScoreCallbackIntervalMs](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md#getscorecallbackintervalms)
- [onDetected](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md#ondetected)
- [onScoreChanged](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md#onscorechanged)

## Properties

### getScoreCallbackIntervalMs

• `Optional` **getScoreCallbackIntervalMs**: () => *number*

#### Type declaration:

▸ (): *number*

**Returns:** *number*

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:28](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L28)

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:28](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L28)

___

### onDetected

• `Optional` **onDetected**: (`attendee`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)) => *void*

#### Type declaration:

▸ (`attendee`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendee` | [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md) |

**Returns:** *void*

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:30](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L30)

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:30](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L30)

___

### onScoreChanged

• `Optional` **onScoreChanged**: (`attendee`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md), `score`: *number*) => *void*

#### Type declaration:

▸ (`attendee`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md), `score`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`attendee` | [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md) |
`score` | *number* |

**Returns:** *void*

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:29](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L29)

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:29](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L29)
