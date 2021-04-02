---
layout: default
parent: Interfaces
grand_parent: API
title: "ChimeTileObserverContract"
---

# Interface: ChimeTileObserverContract

[Observers/Tile/TileObserver.common](../modules/observers_tile_tileobserver_common.md).ChimeTileObserverContract

## Implemented by

* [*ChimeTileObserver*](../classes/observers_tile_tileobserver_common.chimetileobserver.md)

## Table of contents

### Properties

- [onVideoTileAdded](observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotileadded)
- [onVideoTilePaused](observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotilepaused)
- [onVideoTileRemoved](observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotileremoved)
- [onVideoTileResumed](observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotileresumed)
- [onVideoTileSizeChanged](observers_tile_tileobserver_common.chimetileobservercontract.md#onvideotilesizechanged)

## Properties

### onVideoTileAdded

• **onVideoTileAdded**: (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)) => *void*

Called whenever an attendee starts sharing the video.

Note: this callback will be called on main thread.

**`param`** Video tile state associated with new attendee.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:32](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L32)

Defined in: [Observers/Tile/TileObserver.common.ts:32](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L32)

___

### onVideoTilePaused

• `Optional` **onVideoTilePaused**: (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)) => *void*

Called whenever an attendee tile pauseState changes from [VideoPauseState.Unpaused].

Note: this callback will be called on main thread.

**`param`** Video tile state associated with attendee who is paused.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:50](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L50)

Defined in: [Observers/Tile/TileObserver.common.ts:50](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L50)

___

### onVideoTileRemoved

• `Optional` **onVideoTileRemoved**: (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)) => *void*

Called whenever any attendee stops sharing the video.

Note: this callback will be called on main thread.

**`param`** Video tile state associated with attendee who is removed.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:41](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L41)

Defined in: [Observers/Tile/TileObserver.common.ts:41](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L41)

___

### onVideoTileResumed

• `Optional` **onVideoTileResumed**: (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)) => *void*

Called whenever an attendee tile pauseState changes to [VideoPauseState.Unpaused].

Note: this callback will be called on main thread.

**`param`** Video tile state associated with attendee who is resumed.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:59](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L59)

Defined in: [Observers/Tile/TileObserver.common.ts:59](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L59)

___

### onVideoTileSizeChanged

• `Optional` **onVideoTileSizeChanged**: (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)) => *void*

Called whenever a video steam content size is changed

Note: this callback will be called on main thread.

**`param`** Video tile state associated with attendee who is resumed.

#### Type declaration:

▸ (`tileState`: [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`tileState` | [*ChimeTileState*](../classes/tile_tile_common.chimetilestate.md) |

**Returns:** *void*

Defined in: [Observers/Tile/TileObserver.common.ts:68](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L68)

Defined in: [Observers/Tile/TileObserver.common.ts:68](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/Tile/TileObserver.common.ts#L68)
