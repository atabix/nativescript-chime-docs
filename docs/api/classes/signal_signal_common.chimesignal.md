---
layout: default
parent: Classes
grand_parent: API
title: "ChimeSignal"
---

# Class: ChimeSignal

[Signal/Signal.common](../modules/signal_signal_common.md).ChimeSignal

## Table of contents

### Constructors

- [constructor](signal_signal_common.chimesignal.md#constructor)

### Properties

- [android](signal_signal_common.chimesignal.md#android)
- [ios](signal_signal_common.chimesignal.md#ios)

### Accessors

- [attendee](signal_signal_common.chimesignal.md#attendee)
- [strength](signal_signal_common.chimesignal.md#strength)

### Methods

- [toObject](signal_signal_common.chimesignal.md#toobject)
- [toString](signal_signal_common.chimesignal.md#tostring)
- [fromNative](signal_signal_common.chimesignal.md#fromnative)

## Constructors

### constructor

\+ **new ChimeSignal**(): [*ChimeSignal*](signal_signal_common.chimesignal.md)

**Returns:** [*ChimeSignal*](signal_signal_common.chimesignal.md)

Defined in: [Signal/Signal.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Signal/Signal.common.ts#L5)

## Properties

### android

• **android**: *SignalUpdate*

Defined in: [Signal/Signal.common.ts:4](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Signal/Signal.common.ts#L4)

___

### ios

• **ios**: *SignalUpdate*

Defined in: [Signal/Signal.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Signal/Signal.common.ts#L5)

## Accessors

### attendee

• get **attendee**(): [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)

**Returns:** [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)

Defined in: [Signal/Signal.common.ts:11](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Signal/Signal.common.ts#L11)

___

### strength

• get **strength**(): [*ChimeSignalStrength*](../modules/signal_signal_common.md#chimesignalstrength)

**Returns:** [*ChimeSignalStrength*](../modules/signal_signal_common.md#chimesignalstrength)

Defined in: [Signal/Signal.common.ts:18](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Signal/Signal.common.ts#L18)

## Methods

### toObject

▸ **toObject**(): *object*

**Returns:** *object*

Defined in: [Signal/Signal.common.ts:26](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Signal/Signal.common.ts#L26)

___

### toString

▸ **toString**(): *string*

**Returns:** *string*

Defined in: [Signal/Signal.common.ts:35](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Signal/Signal.common.ts#L35)

___

### fromNative

▸ `Static`**fromNative**(`signal`: *SignalUpdate* \| *SignalUpdate*): [*ChimeSignal*](signal_signal_common.chimesignal.md)

#### Parameters:

Name | Type |
:------ | :------ |
`signal` | *SignalUpdate* \| *SignalUpdate* |

**Returns:** [*ChimeSignal*](signal_signal_common.chimesignal.md)

Defined in: [Signal/Signal.common.ts:22](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Signal/Signal.common.ts#L22)
