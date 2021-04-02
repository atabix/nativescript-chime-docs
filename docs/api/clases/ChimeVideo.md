---
layout: default
title: ChimeVideo
parent: Classes
grand_parent: API
nav_order: 5
---

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
