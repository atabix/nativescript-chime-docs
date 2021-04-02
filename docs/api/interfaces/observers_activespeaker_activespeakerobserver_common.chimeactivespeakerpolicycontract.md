---
layout: default
parent: Interfaces
grand_parent: API
title: "ChimeActiveSpeakerPolicyContract"
---

# Interface: ChimeActiveSpeakerPolicyContract

[Observers/ActiveSpeaker/ActiveSpeakerObserver.common](../modules/observers_activespeaker_activespeakerobserver_common.md).ChimeActiveSpeakerPolicyContract

## Table of contents

### Properties

- [calculateScoreWithVolume](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerpolicycontract.md#calculatescorewithvolume)
- [prioritizeVideoSendBandwidthForActiveSpeaker](observers_activespeaker_activespeakerobserver_common.chimeactivespeakerpolicycontract.md#prioritizevideosendbandwidthforactivespeaker)

## Properties

### calculateScoreWithVolume

• `Optional` **calculateScoreWithVolume**: (`attendee`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md), `volume`: *any*) => *number*

#### Type declaration:

▸ (`attendee`: [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md), `volume`: *any*): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`attendee` | [*ChimeAttendeeOptions*](attendee_attendee_common.chimeattendeeoptions.md) |
`volume` | *any* |

**Returns:** *number*

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:34](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L34)

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:34](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L34)

___

### prioritizeVideoSendBandwidthForActiveSpeaker

• `Optional` **prioritizeVideoSendBandwidthForActiveSpeaker**: () => *boolean*

#### Type declaration:

▸ (): *boolean*

**Returns:** *boolean*

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:35](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L35)

Defined in: [Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts:35](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/ActiveSpeaker/ActiveSpeakerObserver.common.ts#L35)
