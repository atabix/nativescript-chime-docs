---
layout: default
title: interfaces
parent: API
nav_order: 2
---

### ChimeMeetingOptions
```ts
interface ChimeMeetingOptions {
    MeetingId: string;
    MediaPlacement: ChimeMediaPlacement;
    MediaRegion: string;
}
```


### ChimeAttendeeOptions
```ts
interface ChimeAttendeeOptions {
    AttendeeId: string;
    ExternalUserId: string;
    JoinToken?: string;
}
```