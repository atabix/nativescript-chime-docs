---
layout: default
title: api documentation
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

