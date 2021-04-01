---
layout: default
title: Observers
nav_order: 3
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
---

## What are observers?
We call Oservers, in the most basic form, to functions that are excecuted when an event is trigger or a state changes. In our case we can use them to get information about whether someone joined or left the meeting, who is speaking or even start a live chat between participants.

---
## What observers are there available?
**addActiveSpeakerObserver**  
Use to detect who is speaking

**addAudioVideoObserver**  
Use to check the status of a session and whether or not it has started, if the connection is poor. This apply for both audio and video.

**addDataMessageObserver**  
????????????

**addDeviceObserver**  
Use to check when an audio device is changed (eg: internal speaker to bluetooth headphone)

**addRealtimeObserver**  
One of the most essencial observers since it allows you to execute code when an attendee joins, leaves, becomes muted, etc.

**addTileObserver**  
use to execute code when an attendee starts, stop, stops sharing the video.

---
## Removing Observers
You can remove this observers anythime by calling `removeActiveSpeakerObserver` `removeAudioVideoObserver` `removeDataMessageObserver` `removeDeviceObserver` `removeRealtimeObserver` `removeTileObserver`

---
## Examples

**ADD SOME REAL WORLD USEFULL EXAMPLES**

---
<div class="note">
<b class="label">Note</b> To know more in depth about observers <a href="/docs/api/interfaces" target="_blank">check our api</a>
</div>

to know more in depth you can go to out api documentaiton (**ADD LINK**)
