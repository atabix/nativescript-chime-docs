---
layout: default
title: Classes
parent: API
nav_order: 1
---


# ChimeSession

## Constructor

```js    
constructor(meeting: ChimeMeeting, attendee: ChimeAttendee);
```
---
## Class Methods
### create
```js    
static create(meeting: ChimeMeetingOptions, attendee: ChimeAttendeeOptions): ChimeSession;
```

@Params   
[ChimeMeetingOptions](/docs/api/interfaces/#chimemeetingoptions)  
[ChimeAttendeeOptions](/docs/api/interfaces/#chimeattendeeoptions)

@Return  
[ChimeSession](/docs/api/chime-session/#chimesession)  

---
## Properties
### configuration
```js
configuration: ChimeSessionConfiguration;
```
@Type  
[ChimeSessionConfiguration](/)

---
### credentials
```js    
credentials: ChimeSessionCredentials;
```
@Type  
[ChimeSessionCredentials](/)

---
### audio
```js    
audio: ChimeAudio;
```
@Type  
[ChimeAudio](/)

---
### video
```js    
video: ChimeVideo;
```
@Type  
[ChimeVideo](/)

---
### dataMessageTopic
```js    
dataMessageTopic: string;
```
@Type  
[string](/)

---
### observers
```js    
observers: ChimeSessionObservers;
```
@Type  
[ChimeSessionObservers](/)

---

## Methods

### start
```js    
start(): void;
```
---
### stop
```js    
stop(): void;
```
---
### sendMessage
```js    
sendMessage(message: object): void;
```
---
### meetingId
```js    
get meetingId(): string;
```
---
### attendeeId
```js    
get attendeeId(): string;
```
---
### addActiveSpeakerObserver
```js    
addActiveSpeakerObserver(listeners: ChimeActiveSpeakerObserverContract): void;
```

@Params  
[ChimeActiveSpeakerObserverContract](/docs/api/interfaces/#chimeactivespeakerobservercontract)

---
### addAudioVideoObserver
```js    
addAudioVideoObserver(listeners: ChimeAudioVideoObserverContract): void;
```
@Params  
[ChimeAudioVideoObserverContract](/docs/api/interfaces/#chimeaudiovideoobservercontract)

---
### addDataMessageObserver

```js    
addDataMessageObserver(listeners: ChimeDataMessageObserverContract): void;
```

@Params  
[ChimeDataMessageObserverContract](/docs/api/interfaces/#chimedatamessageobservercontract)

---
### addDeviceObserver

```js    
addDeviceObserver(listeners: ChimeDeviceObserverContract): void;
```
@Params  
[ChimeDeviceObserverContract](/docs/api/interfaces/#chimedeviceobservercontract)

---
### addRealtimeObserver

```js    
addRealtimeObserver(listeners: ChimeRealtimeObserverContract): void;
```
@Params  
[ChimeRealtimeObserverContract](/docs/api/interfaces/#chimerealtimeobservercontract)

---
### addTileObserver

```js    
addTileObserver(listeners: ChimeTileObserverContract): void;
```
@Params  
[ChimeTileObserverContract](/docs/api/interfaces/#chimetileobservercontract)

---

### removeObservers
```js    
removeObservers(): void;
```
---
### removeAudioVideoObserver
```js    
removeAudioVideoObserver(): void;
```
---
### removeDataMessageObserver
```js    
removeDataMessageObserver(): void;
```
---
### removeDeviceObserver
```js    
removeDeviceObserver(): void;
```
---
### removeRealtimeObserver
```js    
removeRealtimeObserver(): void;
```
---
### removeTileObserver
```js    
removeTileObserver(): void;
```
---
# ChimeSessionConfiguration
```js
class ChimeSessionConfiguration {
    android: com.amazonaws.services.chime.sdk.meetings.session.MeetingSessionConfiguration;
    ios: MeetingSessionConfiguration;
    readonly meeting: ChimeMeeting;
    readonly attendee: ChimeAttendee;
    constructor(meeting: ChimeMeeting, attendee: ChimeAttendee);
}
```

# ChimeSessionCredentials
```js
class ChimeSessionCredentials {
    android: com.amazonaws.services.chime.sdk.meetings.session.MeetingSessionCredentials;
    ios: MeetingSessionCredentials;
    attendee: ChimeAttendee;
    constructor(attendee: ChimeAttendee);
    get attendeeId(): string;
    get joinToken(): string;
    get externalUserId(): string;
}
```

# ChimeAudio
```js
class ChimeAudio extends CommonDevice {
    mute(): void;
    unmute(): void;
    getDevices(): ChimeMediaDevice[];
    setDevice(device: ChimeMediaDevice): void;
}
```

# ChimeVideo
```js
class ChimeVideo extends CommonDevice {
    bindView(view: VideoView, tile: number): void;
    unbindView(tileId: number): void;
    getActiveCamera(): ChimeMediaDevice;
    switchCamera(): void;
    startRemote(): void;
    startLocal(): void;
    stopRemote(): void;
    stopLocal(): void;
    getDevices(): ChimeMediaDevice[];
}
```

