---
layout: default
parent: Classes
grand_parent: API
title: "ChimeTileObserver"
---

# Class: ChimeTileObserver

[Observers/Tile/TileObserver.common](../modules/observers_tile_tileobserver_common.md).ChimeTileObserver

## Implements

* [*ChimeTileObserverContract*](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md)

## Table of contents

### Constructors

- [constructor](observers_tile_tileobserver_common.chimetileobserver.md#constructor)

### Properties

- [android](observers_tile_tileobserver_common.chimetileobserver.md#android)
- [ios](observers_tile_tileobserver_common.chimetileobserver.md#ios)
- [onVideoTileAdded](observers_tile_tileobserver_common.chimetileobserver.md#onvideotileadded)
- [onVideoTilePaused](observers_tile_tileobserver_common.chimetileobserver.md#onvideotilepaused)
- [onVideoTileRemoved](observers_tile_tileobserver_common.chimetileobserver.md#onvideotileremoved)
- [onVideoTileResumed](observers_tile_tileobserver_common.chimetileobserver.md#onvideotileresumed)
- [onVideoTileSizeChanged](observers_tile_tileobserver_common.chimetileobserver.md#onvideotilesizechanged)

## Constructors

### constructor

\+ **new ChimeTileObserver**(`listeners`: [*ChimeTileObserverContract*](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md)): [*ChimeTileObserver*](observers_tile_tileobserver_common.chimetileobserver.md)

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeTileObserverContract*](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md) |

**Returns:** [*ChimeTileObserver*](observers_tile_tileobserver_common.chimetileobserver.md)

Defined in: [Observers/Tile/TileObserver.common.ts:11](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L11)

## Properties

### android

• **android**: *VideoTileObserver*

Defined in: [Observers/Tile/TileObserver.common.ts:4](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L4)

___

### ios

• **ios**: VideoTileObserver

Defined in: [Observers/Tile/TileObserver.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L5)

___

### onVideoTileAdded

• **onVideoTileAdded**: (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)) => *void*

Called whenever an attendee starts sharing the video.

Note: this callback will be called on main thread.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:7](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L7)

Implementation of: [ChimeTileObserverContract](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md).[onVideoTileAdded](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotileadded)

Defined in: [Observers/Tile/TileObserver.common.ts:7](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L7)

___

### onVideoTilePaused

• **onVideoTilePaused**: (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)) => *void*

Called whenever an attendee tile pauseState changes from [VideoPauseState.Unpaused].

Note: this callback will be called on main thread.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:9](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L9)

Implementation of: [ChimeTileObserverContract](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md).[onVideoTilePaused](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotilepaused)

Defined in: [Observers/Tile/TileObserver.common.ts:9](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L9)

___

### onVideoTileRemoved

• **onVideoTileRemoved**: (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)) => *void*

Called whenever any attendee stops sharing the video.

Note: this callback will be called on main thread.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:8](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L8)

Implementation of: [ChimeTileObserverContract](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md).[onVideoTileRemoved](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotileremoved)

Defined in: [Observers/Tile/TileObserver.common.ts:8](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L8)

___

### onVideoTileResumed

• **onVideoTileResumed**: (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)) => *void*

Called whenever an attendee tile pauseState changes to [VideoPauseState.Unpaused].

Note: this callback will be called on main thread.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:10](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L10)

Implementation of: [ChimeTileObserverContract](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md).[onVideoTileResumed](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotileresumed)

Defined in: [Observers/Tile/TileObserver.common.ts:10](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L10)

___

### onVideoTileSizeChanged

• **onVideoTileSizeChanged**: (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)) => *void*

Called whenever a video steam content size is changed

Note: this callback will be called on main thread.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:11](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L11)

Implementation of: [ChimeTileObserverContract](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md).[onVideoTileSizeChanged](../interfaces/observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotilesizechanged)

Defined in: [Observers/Tile/TileObserver.common.ts:11](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L11)
