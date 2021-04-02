---
layout: default
parent: Classes
grand_parent: API
title: "ChimeTileState"
---

# Class: ChimeTileState

[Tile/Tile.common](../modules/tile_tile_common.md).ChimeTileState

## Table of contents

### Constructors

- [constructor](tile_tile_common.chimetilestate.md#constructor)

### Properties

- [android](tile_tile_common.chimetilestate.md#android)
- [ios](tile_tile_common.chimetilestate.md#ios)

### Accessors

- [attendeeId](tile_tile_common.chimetilestate.md#attendeeid)
- [isLocalTile](tile_tile_common.chimetilestate.md#islocaltile)
- [pauseState](tile_tile_common.chimetilestate.md#pausestate)
- [tileId](tile_tile_common.chimetilestate.md#tileid)
- [videoStreamContentHeight](tile_tile_common.chimetilestate.md#videostreamcontentheight)
- [videoStreamContentWidth](tile_tile_common.chimetilestate.md#videostreamcontentwidth)

### Methods

- [toObject](tile_tile_common.chimetilestate.md#toobject)
- [toString](tile_tile_common.chimetilestate.md#tostring)
- [fromNative](tile_tile_common.chimetilestate.md#fromnative)

## Constructors

### constructor

\+ **new ChimeTileState**(): [*ChimeTileState*](tile_tile_common.chimetilestate.md)

**Returns:** [*ChimeTileState*](tile_tile_common.chimetilestate.md)

Defined in: [Tile/Tile.common.ts:16](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L16)

## Properties

### android

• **android**: *VideoTileState*

Defined in: [Tile/Tile.common.ts:15](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L15)

___

### ios

• **ios**: *VideoTileState*

Defined in: [Tile/Tile.common.ts:16](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L16)

## Accessors

### attendeeId

• get **attendeeId**(): *string*

**Returns:** *string*

Defined in: [Tile/Tile.common.ts:30](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L30)

___

### isLocalTile

• get **isLocalTile**(): *boolean*

**Returns:** *boolean*

Defined in: [Tile/Tile.common.ts:46](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L46)

___

### pauseState

• get **pauseState**(): [*ChimeVideoState*](../enums/video_video_common.chimevideostate.md)

**Returns:** [*ChimeVideoState*](../enums/video_video_common.chimevideostate.md)

Defined in: [Tile/Tile.common.ts:42](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L42)

___

### tileId

• get **tileId**(): *number*

**Returns:** *number*

Defined in: [Tile/Tile.common.ts:26](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L26)

___

### videoStreamContentHeight

• get **videoStreamContentHeight**(): *number*

**Returns:** *number*

Defined in: [Tile/Tile.common.ts:38](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L38)

___

### videoStreamContentWidth

• get **videoStreamContentWidth**(): *number*

**Returns:** *number*

Defined in: [Tile/Tile.common.ts:34](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L34)

## Methods

### toObject

▸ **toObject**(): *object*

**Returns:** *object*

Defined in: [Tile/Tile.common.ts:50](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L50)

___

### toString

▸ **toString**(): *string*

**Returns:** *string*

Defined in: [Tile/Tile.common.ts:63](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L63)

___

### fromNative

▸ `Static`**fromNative**(`state`: *VideoTileState* \| *VideoTileState*): [*ChimeTileState*](tile_tile_common.chimetilestate.md)

#### Parameters:

Name | Type |
:------ | :------ |
`state` | *VideoTileState* \| *VideoTileState* |

**Returns:** [*ChimeTileState*](tile_tile_common.chimetilestate.md)

Defined in: [Tile/Tile.common.ts:22](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Tile/Tile.common.ts#L22)
