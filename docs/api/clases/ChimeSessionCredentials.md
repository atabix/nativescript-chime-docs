---
layout: default
title: ChimeSessionCredentials
parent: Classes
grand_parent: API
nav_order: 4
---

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