---
layout: default
title: Interfaces
parent: API
nav_order: 2
---

# ChimeMeetingOptions
```js
interface ChimeMeetingOptions {
    MeetingId: string;
    MediaPlacement: ChimeMediaPlacement;
    MediaRegion: string;
}
```


# ChimeAttendeeOptions
```js
interface ChimeAttendeeOptions {
    AttendeeId: string;
    ExternalUserId: string;
    JoinToken?: string;
}
```

# ChimeDataMessage
```js
interface ChimeDataMessage {
    timestampMs: number;
    topic: string;
    data: object;
    senderAttendeeId: string;
    senderExternalUserId: string;
    throttled: boolean;
}
```

# ChimeActiveSpeakerObserverContract
```js
interface ChimeActiveSpeakerObserverContract {
    getScoreCallbackIntervalMs?: () => number;
    onScoreChanged?: (attendee: ChimeAttendeeOptions, score: number) => void;
    onDetected?: (attendee: ChimeAttendeeOptions) => void;
}
```

# ChimeAudioVideoObserverContract
```js
interface ChimeAudioVideoObserverContract {
    onAudioSessionStartedConnecting?: (reconnecting: boolean) => void;
    onAudioSessionStarted?: (reconnecting: boolean) => void;
    onAudioSessionDropped?: () => void;
    onAudioSessionStopped?: (status: ChimeSessionStatus) => void;
    onAudioSessionCancelledReconnect?: () => void;
    onConnectionRecovered?: () => void;
    onConnectionBecamePoor?: () => void;
    onVideoSessionStartedConnecting?: () => void;
    onVideoSessionStarted?: (status: ChimeSessionStatus) => void;
    onVideoSessionStopped?: (status: ChimeSessionStatus) => void;
}
```
# ChimeDataMessageObserverContract
```js
interface ChimeDataMessageObserverContract {
    onDataMessageReceived?: (message: ChimeDataMessage) => void;
}
```
# ChimeDeviceObserverContract
```js
interface ChimeDeviceObserverContract {
    onAudioDeviceChanged?: (devices: ChimeMediaDevice[]) => void;
}
```



# ChimeRealtimeObserverContract
```js
interface ChimeRealtimeObserverContract {
    onVolumeChanged?: (volumeUpdate: ChimeVolume[]) => void;
    onSignalStrengthChanged?: (signalUpdate: ChimeSignal[]) => void;
    onAttendeesJoined?: (attendees: ChimeAttendeeOptions[]) => void;
    onAttendeesLeft?: (attendees: ChimeAttendeeOptions[]) => void;
    onAttendeesDropped?: (attendees: ChimeAttendeeOptions[]) => void;
    onAttendeesMuted?: (attendees: ChimeAttendeeOptions[]) => void;
    onAttendeesUnmuted?: (attendees: ChimeAttendeeOptions[]) => void;
}
```

# ChimeTileObserverContract
```js
export interface ChimeTileObserverContract {
    onVideoTileAdded: (tileState: ChimeTileState) => void;
    onVideoTileRemoved?: (tileState: ChimeTileState) => void;
    onVideoTilePaused?: (tileState: ChimeTileState) => void;
    onVideoTileResumed?: (tileState: ChimeTileState) => void;
    onVideoTileSizeChanged?: (tileState: ChimeTileState) => void;
}
```