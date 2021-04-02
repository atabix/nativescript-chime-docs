---
layout: default
parent: Interfaces
grand_parent: API
title: "ChimeAudioVideoObserverContract"
---

# Interface: ChimeAudioVideoObserverContract

[Observers/AudioVideo/AudioVideoObserver.common](../modules/observers_audiovideo_audiovideoobserver_common.md).ChimeAudioVideoObserverContract

## Implemented by

* [*ChimeAudioVideoObserver*](../classes/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md)

## Table of contents

### Properties

- [onAudioSessionCancelledReconnect](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessioncancelledreconnect)
- [onAudioSessionDropped](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessiondropped)
- [onAudioSessionStarted](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessionstarted)
- [onAudioSessionStartedConnecting](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessionstartedconnecting)
- [onAudioSessionStopped](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessionstopped)
- [onConnectionBecamePoor](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onconnectionbecamepoor)
- [onConnectionRecovered](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onconnectionrecovered)
- [onVideoSessionStarted](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onvideosessionstarted)
- [onVideoSessionStartedConnecting](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onvideosessionstartedconnecting)
- [onVideoSessionStopped](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onvideosessionstopped)

## Properties

### onAudioSessionCancelledReconnect

• `Optional` **onAudioSessionCancelledReconnect**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:41](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L41)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:41](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L41)

___

### onAudioSessionDropped

• `Optional` **onAudioSessionDropped**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:39](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L39)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:39](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L39)

___

### onAudioSessionStarted

• `Optional` **onAudioSessionStarted**: (`reconnecting`: *boolean*) => *void*

#### Type declaration:

▸ (`reconnecting`: *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`reconnecting` | *boolean* |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:38](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L38)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:38](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L38)

___

### onAudioSessionStartedConnecting

• `Optional` **onAudioSessionStartedConnecting**: (`reconnecting`: *boolean*) => *void*

#### Type declaration:

▸ (`reconnecting`: *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`reconnecting` | *boolean* |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:37](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L37)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:37](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L37)

___

### onAudioSessionStopped

• `Optional` **onAudioSessionStopped**: (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)) => *void*

#### Type declaration:

▸ (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`status` | [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md) |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:40](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L40)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:40](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L40)

___

### onConnectionBecamePoor

• `Optional` **onConnectionBecamePoor**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:43](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L43)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:43](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L43)

___

### onConnectionRecovered

• `Optional` **onConnectionRecovered**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:42](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L42)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:42](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L42)

___

### onVideoSessionStarted

• `Optional` **onVideoSessionStarted**: (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)) => *void*

#### Type declaration:

▸ (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`status` | [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md) |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:45](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L45)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:45](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L45)

___

### onVideoSessionStartedConnecting

• `Optional` **onVideoSessionStartedConnecting**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:44](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L44)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:44](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L44)

___

### onVideoSessionStopped

• `Optional` **onVideoSessionStopped**: (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)) => *void*

#### Type declaration:

▸ (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`status` | [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md) |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:46](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L46)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:46](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L46)
