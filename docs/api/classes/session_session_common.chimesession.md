---
layout: default
parent: Classes
grand_parent: API
title: "ChimeSession"
---

# Class: ChimeSession

[Session/Session.common](../modules/session_session_common.md).ChimeSession

## Table of contents

### Constructors

- [constructor](session_session_common.chimesession.md#constructor)

### Properties

- [android](session_session_common.chimesession.md#android)
- [audio](session_session_common.chimesession.md#audio)
- [configuration](session_session_common.chimesession.md#configuration)
- [credentials](session_session_common.chimesession.md#credentials)
- [dataMessageTopic](session_session_common.chimesession.md#datamessagetopic)
- [ios](session_session_common.chimesession.md#ios)
- [observers](session_session_common.chimesession.md#observers)
- [video](session_session_common.chimesession.md#video)

### Accessors

- [attendeeId](session_session_common.chimesession.md#attendeeid)
- [meetingId](session_session_common.chimesession.md#meetingid)

### Methods

- [addActiveSpeakerObserver](session_session_common.chimesession.md#addactivespeakerobserver)
- [addAudioVideoObserver](session_session_common.chimesession.md#addaudiovideoobserver)
- [addDataMessageObserver](session_session_common.chimesession.md#adddatamessageobserver)
- [addDeviceObserver](session_session_common.chimesession.md#adddeviceobserver)
- [addRealtimeObserver](session_session_common.chimesession.md#addrealtimeobserver)
- [addTileObserver](session_session_common.chimesession.md#addtileobserver)
- [removeAudioVideoObserver](session_session_common.chimesession.md#removeaudiovideoobserver)
- [removeDataMessageObserver](session_session_common.chimesession.md#removedatamessageobserver)
- [removeDeviceObserver](session_session_common.chimesession.md#removedeviceobserver)
- [removeObservers](session_session_common.chimesession.md#removeobservers)
- [removeRealtimeObserver](session_session_common.chimesession.md#removerealtimeobserver)
- [removeTileObserver](session_session_common.chimesession.md#removetileobserver)
- [sendMessage](session_session_common.chimesession.md#sendmessage)
- [start](session_session_common.chimesession.md#start)
- [stop](session_session_common.chimesession.md#stop)
- [create](session_session_common.chimesession.md#create)

## Constructors

### constructor

\+ **new ChimeSession**(`meeting`: [*ChimeMeeting*](meeting_meeting_common.chimemeeting.md), `attendee`: [*ChimeAttendee*](attendee_attendee_common.chimeattendee.md)): [*ChimeSession*](session_session_common.chimesession.md)

#### Parameters:

Name | Type |
:------ | :------ |
`meeting` | [*ChimeMeeting*](meeting_meeting_common.chimemeeting.md) |
`attendee` | [*ChimeAttendee*](attendee_attendee_common.chimeattendee.md) |

**Returns:** [*ChimeSession*](session_session_common.chimesession.md)

Defined in: [Session/Session.common.ts:22](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L22)

## Properties

### android

• **android**: *DefaultMeetingSession*

Defined in: [Session/Session.common.ts:13](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L13)

___

### audio

• **audio**: [*ChimeAudio*](audio_audio_common.chimeaudio.md)

Defined in: [Session/Session.common.ts:18](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L18)

___

### configuration

• **configuration**: [*ChimeSessionConfiguration*](session_session_common.chimesessionconfiguration.md)

Defined in: [Session/Session.common.ts:16](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L16)

___

### credentials

• **credentials**: [*ChimeSessionCredentials*](session_session_common.chimesessioncredentials.md)

Defined in: [Session/Session.common.ts:17](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L17)

___

### dataMessageTopic

• **dataMessageTopic**: *string*= 'default'

Defined in: [Session/Session.common.ts:21](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L21)

___

### ios

• **ios**: *DefaultMeetingSession*

Defined in: [Session/Session.common.ts:14](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L14)

___

### observers

• **observers**: [*ChimeSessionObservers*](../interfaces/observers_index_common.chimesessionobservers.md)

Defined in: [Session/Session.common.ts:22](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L22)

___

### video

• **video**: [*ChimeVideo*](video_video_common.chimevideo.md)

Defined in: [Session/Session.common.ts:19](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L19)

## Accessors

### attendeeId

• get **attendeeId**(): *string*

The attendee id for the active session.

**Returns:** *string*

Defined in: [Session/Session.common.ts:55](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L55)

___

### meetingId

• get **meetingId**(): *string*

The meeting id for the active session.

**Returns:** *string*

Defined in: [Session/Session.common.ts:48](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L48)

## Methods

### addActiveSpeakerObserver

▸ **addActiveSpeakerObserver**(`listeners`: [*ChimeActiveSpeakerObserverContract*](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeActiveSpeakerObserverContract*](../interfaces/observers_activespeaker_activespeakerobserver_common.chimeactivespeakerobservercontract.md) |

**Returns:** *void*

Defined in: [Session/Session.common.ts:59](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L59)

___

### addAudioVideoObserver

▸ **addAudioVideoObserver**(`listeners`: [*ChimeAudioVideoObserverContract*](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeAudioVideoObserverContract*](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md) |

**Returns:** *void*

Defined in: [Session/Session.common.ts:63](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L63)

___

### addDataMessageObserver

▸ **addDataMessageObserver**(`listeners`: [*ChimeDataMessageObserverContract*](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessageobservercontract.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeDataMessageObserverContract*](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessageobservercontract.md) |

**Returns:** *void*

Defined in: [Session/Session.common.ts:67](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L67)

___

### addDeviceObserver

▸ **addDeviceObserver**(`listeners`: [*ChimeDeviceObserverContract*](../interfaces/observers_device_deviceobserver_common.chimedeviceobservercontract.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeDeviceObserverContract*](../interfaces/observers_device_deviceobserver_common.chimedeviceobservercontract.md) |

**Returns:** *void*

Defined in: [Session/Session.common.ts:71](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L71)

___

### addRealtimeObserver

▸ **addRealtimeObserver**(`listeners`: [*ChimeRealtimeObserverContract*](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeRealtimeObserverContract*](../interfaces/observers_realtime_realtimeobserver_common.chimerealtimeobservercontract.md) |

**Returns:** *void*

Defined in: [Session/Session.common.ts:75](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L75)

___

### addTileObserver

▸ **addTileObserver**(`listeners`: [*ChimeTileObserverContract*](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeTileObserverContract*](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md) |

**Returns:** *void*

Defined in: [Session/Session.common.ts:79](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L79)

___

### removeAudioVideoObserver

▸ **removeAudioVideoObserver**(): *void*

**Returns:** *void*

Defined in: [Session/Session.common.ts:91](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L91)

___

### removeDataMessageObserver

▸ **removeDataMessageObserver**(): *void*

**Returns:** *void*

Defined in: [Session/Session.common.ts:95](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L95)

___

### removeDeviceObserver

▸ **removeDeviceObserver**(): *void*

**Returns:** *void*

Defined in: [Session/Session.common.ts:99](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L99)

___

### removeObservers

▸ **removeObservers**(): *void*

**Returns:** *void*

Defined in: [Session/Session.common.ts:83](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L83)

___

### removeRealtimeObserver

▸ **removeRealtimeObserver**(): *void*

**Returns:** *void*

Defined in: [Session/Session.common.ts:103](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L103)

___

### removeTileObserver

▸ **removeTileObserver**(): *void*

**Returns:** *void*

Defined in: [Session/Session.common.ts:107](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L107)

___

### sendMessage

▸ **sendMessage**(`message`: *object*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`message` | *object* |

**Returns:** *void*

Defined in: [Session/Session.common.ts:41](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L41)

___

### start

▸ **start**(): *void*

**Returns:** *void*

Defined in: [Session/Session.common.ts:32](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L32)

___

### stop

▸ **stop**(): *void*

**Returns:** *void*

Defined in: [Session/Session.common.ts:36](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L36)

___

### create

▸ `Static`**create**(`meeting`: [*ChimeMeetingOptions*](../interfaces/meeting_meeting_common.chimemeetingoptions.md), `attendee`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)): [*ChimeSession*](session_session_common.chimesession.md)

#### Parameters:

Name | Type |
:------ | :------ |
`meeting` | [*ChimeMeetingOptions*](../interfaces/meeting_meeting_common.chimemeetingoptions.md) |
`attendee` | [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md) |

**Returns:** [*ChimeSession*](session_session_common.chimesession.md)

Defined in: [Session/Session.common.ts:28](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Session/Session.common.ts#L28)
