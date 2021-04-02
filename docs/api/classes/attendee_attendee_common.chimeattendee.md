---
layout: default
parent: Classes
grand_parent: API
title: "ChimeAttendee"
---

# Class: ChimeAttendee

[Attendee/Attendee.common](../modules/attendee_attendee_common.md).ChimeAttendee

## Table of contents

### Constructors

- [constructor](attendee_attendee_common.chimeattendee.md#constructor)

### Properties

- [android](attendee_attendee_common.chimeattendee.md#android)
- [attendeeId](attendee_attendee_common.chimeattendee.md#attendeeid)
- [externalUserId](attendee_attendee_common.chimeattendee.md#externaluserid)
- [ios](attendee_attendee_common.chimeattendee.md#ios)
- [joinToken](attendee_attendee_common.chimeattendee.md#jointoken)

### Methods

- [nativeToObject](attendee_attendee_common.chimeattendee.md#nativetoobject)

## Constructors

### constructor

\+ **new ChimeAttendee**(`attendee`: [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)): [*ChimeAttendee*](attendee_attendee_common.chimeattendee.md)

#### Parameters:

Name | Type |
:------ | :------ |
`attendee` | [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md) |

**Returns:** [*ChimeAttendee*](attendee_attendee_common.chimeattendee.md)

Defined in: [Attendee/Attendee.common.ts:7](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Attendee/Attendee.common.ts#L7)

## Properties

### android

• **android**: *CreateAttendeeResponse*

Defined in: [Attendee/Attendee.common.ts:2](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Attendee/Attendee.common.ts#L2)

___

### attendeeId

• **attendeeId**: *string*

Defined in: [Attendee/Attendee.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Attendee/Attendee.common.ts#L5)

___

### externalUserId

• **externalUserId**: *string*

Defined in: [Attendee/Attendee.common.ts:6](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Attendee/Attendee.common.ts#L6)

___

### ios

• **ios**: *CreateAttendeeResponse*

Defined in: [Attendee/Attendee.common.ts:3](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Attendee/Attendee.common.ts#L3)

___

### joinToken

• **joinToken**: *string*= ''

Defined in: [Attendee/Attendee.common.ts:7](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Attendee/Attendee.common.ts#L7)

## Methods

### nativeToObject

▸ `Static`**nativeToObject**(`attendee`: *AttendeeInfo* \| *AttendeeInfo*): [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)

#### Parameters:

Name | Type |
:------ | :------ |
`attendee` | *AttendeeInfo* \| *AttendeeInfo* |

**Returns:** [*ChimeAttendeeOptions*](../interfaces/attendee_attendee_common.chimeattendeeoptions.md)

Defined in: [Attendee/Attendee.common.ts:15](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Attendee/Attendee.common.ts#L15)
