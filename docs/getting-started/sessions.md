---
layout: default
title: Sessions
parent: Getting Started
nav_order: 2
---


## What is a session?

A session The root object of the Amazon Chime SDK for JavaScript that represents each user’s session in a meeting. The web applications start by instantiating MeetingSession and configuring it with the correct meeting and attendee information. You can think of it as a conference room. In order to create one we need to call the class method [create](/docs/api/chime-session/#create)

<div class="note">
<b class="label">Note</b> You can read more about the basics concepts by going <a href="https://docs.aws.amazon.com/chime/latest/dg/meetings-sdk.html" target="_blank">here</a></div>
---

## Creating a session
now that we now what a session is we need two things in order to create it:

[**meeting**](/docs/api/interfaces/#chimemeetingoptions)  
`An ephemeral resource identified by a unique MeetingId. The MeetingId is placed onto a group of media services that host the active meeting.`

[**attendee**](/docs/api/interfaces/#chimeattendeeoptions)  
`A meeting participant that is identified by a unique AttendeeId. Attendees may freely join and leave meetings using a client application built with an Amazon Chime SDK client library.`
  

We can after call the create method and we now have a session.
  
```js
const meetingSession = ChimeSession.create(meeting, attendee);
```
---
## Starting or stopping a meeting

Finnaly we can start or stop a meeting with the following methods  

```js
meetingSession.start();
```

```js
meetingSession.stop();
```



---
<div class="note">
<b class="label">Note</b> If you want to know more about how to create an attende follow <a href="https://docs.aws.amazon.com/chime/latest/dg/creating-a-meeting.html" target="_blank">this link</a> or to create a meeting follow <a href="https://docs.aws.amazon.com/chime/latest/dg/creating-a-meeting.html" target="_blank">this one</a></div>