---
layout: default
title: ChimeSessionConfiguration
parent: Classes
grand_parent: API
nav_order: 3
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