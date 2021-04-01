---
layout: default
title: Classes
parent: API
nav_order: 1
---


# ChimeSession
```js
configuration: ChimeSessionConfiguration;
```

```js    
credentials: ChimeSessionCredentials;
```

```js    
audio: ChimeAudio;
```

```js    
video: ChimeVideo;
```

```js    
dataMessageTopic: string;
```

```js    
observers: ChimeSessionObservers;
```

```js    
constructor(meeting: ChimeMeeting, attendee: ChimeAttendee);
```

### create
```js    
static create(meeting: ChimeMeetingOptions, attendee: ChimeAttendeeOptions): ChimeSession;
```

@Params   
[ChimeMeetingOptions](/docs/api/interfaces/#chimemeetingoptions)  
[ChimeAttendeeOptions](/docs/api/interfaces/#chimeattendeeoptions)

@Return  
[ChimeSession](/docs/api/chime-session/#chimesession)  



```js    
start(): void;
```

```js    
stop(): void;
```

```js    
sendMessage(message: object): void;
```

```js    
get meetingId(): string;
```

```js    
get attendeeId(): string;
```

```js    
addActiveSpeakerObserver(listeners: ChimeActiveSpeakerObserverContract): void;
```

```js    
addAudioVideoObserver(listeners: ChimeAudioVideoObserverContract): void;
```

```js    
addDataMessageObserver(listeners: ChimeDataMessageObserverContract): void;
```

```js    
addDeviceObserver(listeners: ChimeDeviceObserverContract): void;
```

```js    
addRealtimeObserver(listeners: ChimeRealtimeObserverContract): void;
```

```js    
addTileObserver(listeners: ChimeTileObserverContract): void;
```

```js    
removeObservers(): void;
```

```js    
removeAudioVideoObserver(): void;
```

```js    
removeDataMessageObserver(): void;
```

```js    
removeDeviceObserver(): void;
```

```js    
removeRealtimeObserver(): void;
```

```js    
removeTileObserver(): void;
```

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

