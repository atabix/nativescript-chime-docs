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

# ChimeTileObserverContract
```js
export interface ChimeTileObserverContract {
    /**
     * Called whenever an attendee starts sharing the video.
     *
     * Note: this callback will be called on main thread.
     *
     * @param tileState: [ChimeTileState] - Video tile state associated with new attendee.
     */
    onVideoTileAdded: (tileState: ChimeTileState) => void;
    /**
     * Called whenever any attendee stops sharing the video.
     *
     * Note: this callback will be called on main thread.
     *
     * @param tileState: [ChimeTileState] - Video tile state associated with attendee who is removed.
     */
    onVideoTileRemoved?: (tileState: ChimeTileState) => void;
    /**
     * Called whenever an attendee tile pauseState changes from [VideoPauseState.Unpaused].
     *
     * Note: this callback will be called on main thread.
     *
     * @param tileState: [ChimeTileState] - Video tile state associated with attendee who is paused.
     */
    onVideoTilePaused?: (tileState: ChimeTileState) => void;
    /**
     * Called whenever an attendee tile pauseState changes to [VideoPauseState.Unpaused].
     *
     * Note: this callback will be called on main thread.
     *
     * @param tileState: [ChimeTileState] - Video tile state associated with attendee who is resumed.
     */
    onVideoTileResumed?: (tileState: ChimeTileState) => void;
    /**
     * Called whenever a video steam content size is changed
     *
     * Note: this callback will be called on main thread.
     *
     * @param tileState: [ChimeTileState] - Video tile state associated with attendee who is resumed.
     */
    onVideoTileSizeChanged?: (tileState: ChimeTileState) => void;
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