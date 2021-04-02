---
layout: default
parent: Classes
grand_parent: API
title: "ChimeAudioVideoObserver"
---

# Class: ChimeAudioVideoObserver

[Observers/AudioVideo/AudioVideoObserver.common](../modules/observers_audiovideo_audiovideoobserver_common.md).ChimeAudioVideoObserver

## Implements

* [*ChimeAudioVideoObserverContract*](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md)

## Table of contents

### Constructors

- [constructor](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#constructor)

### Properties

- [android](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#android)
- [ios](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#ios)
- [onAudioSessionCancelledReconnect](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onaudiosessioncancelledreconnect)
- [onAudioSessionDropped](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onaudiosessiondropped)
- [onAudioSessionStarted](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onaudiosessionstarted)
- [onAudioSessionStartedConnecting](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onaudiosessionstartedconnecting)
- [onAudioSessionStopped](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onaudiosessionstopped)
- [onConnectionBecamePoor](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onconnectionbecamepoor)
- [onConnectionRecovered](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onconnectionrecovered)
- [onVideoSessionStarted](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onvideosessionstarted)
- [onVideoSessionStartedConnecting](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onvideosessionstartedconnecting)
- [onVideoSessionStopped](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md#onvideosessionstopped)

## Constructors

### constructor

\+ **new ChimeAudioVideoObserver**(`listeners`: [*ChimeAudioVideoObserverContract*](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md)): [*ChimeAudioVideoObserver*](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md)

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeAudioVideoObserverContract*](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md) |

**Returns:** [*ChimeAudioVideoObserver*](observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobserver.md)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:18](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L18)

## Properties

### android

• **android**: *AudioVideoObserver*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:6](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L6)

___

### ios

• **ios**: AudioVideoObserver

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:7](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L7)

___

### onAudioSessionCancelledReconnect

• **onAudioSessionCancelledReconnect**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:13](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L13)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onAudioSessionCancelledReconnect](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessioncancelledreconnect)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:13](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L13)

___

### onAudioSessionDropped

• **onAudioSessionDropped**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:11](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L11)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onAudioSessionDropped](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessiondropped)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:11](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L11)

___

### onAudioSessionStarted

• **onAudioSessionStarted**: (`reconnecting`: *boolean*) => *void*

#### Type declaration:

▸ (`reconnecting`: *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`reconnecting` | *boolean* |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:10](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L10)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onAudioSessionStarted](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessionstarted)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:10](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L10)

___

### onAudioSessionStartedConnecting

• **onAudioSessionStartedConnecting**: (`reconnecting`: *boolean*) => *void*

#### Type declaration:

▸ (`reconnecting`: *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`reconnecting` | *boolean* |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:9](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L9)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onAudioSessionStartedConnecting](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessionstartedconnecting)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:9](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L9)

___

### onAudioSessionStopped

• **onAudioSessionStopped**: (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)) => *void*

#### Type declaration:

▸ (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`status` | [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md) |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:12](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L12)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onAudioSessionStopped](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onaudiosessionstopped)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:12](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L12)

___

### onConnectionBecamePoor

• **onConnectionBecamePoor**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:15](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L15)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onConnectionBecamePoor](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onconnectionbecamepoor)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:15](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L15)

___

### onConnectionRecovered

• **onConnectionRecovered**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:14](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L14)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onConnectionRecovered](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onconnectionrecovered)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:14](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L14)

___

### onVideoSessionStarted

• **onVideoSessionStarted**: (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)) => *void*

#### Type declaration:

▸ (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`status` | [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md) |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:17](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L17)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onVideoSessionStarted](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onvideosessionstarted)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:17](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L17)

___

### onVideoSessionStartedConnecting

• **onVideoSessionStartedConnecting**: () => *void*

#### Type declaration:

▸ (): *void*

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:16](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L16)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onVideoSessionStartedConnecting](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onvideosessionstartedconnecting)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:16](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L16)

___

### onVideoSessionStopped

• **onVideoSessionStopped**: (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)) => *void*

#### Type declaration:

▸ (`status`: [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`status` | [*ChimeSessionStatus*](../enums/observers_audiovideo_audiovideoobserver_common.chimesessionstatus.md) |

**Returns:** *void*

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:18](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L18)

Implementation of: [ChimeAudioVideoObserverContract](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md).[onVideoSessionStopped](../interfaces/observers_audiovideo_audiovideoobserver_common.chimeaudiovideoobservercontract.md#onvideosessionstopped)

Defined in: [Observers/AudioVideo/AudioVideoObserver.common.ts:18](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/AudioVideo/AudioVideoObserver.common.ts#L18)
