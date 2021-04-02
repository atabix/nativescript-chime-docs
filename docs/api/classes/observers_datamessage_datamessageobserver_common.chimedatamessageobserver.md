---
layout: default
parent: Classes
grand_parent: API
title: "ChimeDataMessageObserver"
---

# Class: ChimeDataMessageObserver

[Observers/DataMessage/DataMessageObserver.common](../modules/observers_datamessage_datamessageobserver_common.md).ChimeDataMessageObserver

## Implements

* [*ChimeDataMessageObserverContract*](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessageobservercontract.md)

## Table of contents

### Constructors

- [constructor](observers_datamessage_datamessageobserver_common.chimedatamessageobserver.md#constructor)

### Properties

- [android](observers_datamessage_datamessageobserver_common.chimedatamessageobserver.md#android)
- [ios](observers_datamessage_datamessageobserver_common.chimedatamessageobserver.md#ios)
- [onDataMessageReceived](observers_datamessage_datamessageobserver_common.chimedatamessageobserver.md#ondatamessagereceived)

## Constructors

### constructor

\+ **new ChimeDataMessageObserver**(`listeners`: [*ChimeDataMessageObserverContract*](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessageobservercontract.md)): [*ChimeDataMessageObserver*](observers_datamessage_datamessageobserver_common.chimedatamessageobserver.md)

#### Parameters:

Name | Type |
:------ | :------ |
`listeners` | [*ChimeDataMessageObserverContract*](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessageobservercontract.md) |

**Returns:** [*ChimeDataMessageObserver*](observers_datamessage_datamessageobserver_common.chimedatamessageobserver.md)

Defined in: [Observers/DataMessage/DataMessageObserver.common.ts:7](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/DataMessage/DataMessageObserver.common.ts#L7)

## Properties

### android

• **android**: *DataMessageObserver*

Defined in: [Observers/DataMessage/DataMessageObserver.common.ts:4](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/DataMessage/DataMessageObserver.common.ts#L4)

___

### ios

• **ios**: DataMessageObserver

Defined in: [Observers/DataMessage/DataMessageObserver.common.ts:5](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/DataMessage/DataMessageObserver.common.ts#L5)

___

### onDataMessageReceived

• **onDataMessageReceived**: (`message`: [*ChimeDataMessage*](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessage.md)) => *void*

#### Type declaration:

▸ (`message`: [*ChimeDataMessage*](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessage.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`message` | [*ChimeDataMessage*](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessage.md) |

**Returns:** *void*

Defined in: [Observers/DataMessage/DataMessageObserver.common.ts:7](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/DataMessage/DataMessageObserver.common.ts#L7)

Implementation of: [ChimeDataMessageObserverContract](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessageobservercontract.md).[onDataMessageReceived](../interfaces/observers_datamessage_datamessageobserver_common.chimedatamessageobservercontract.md#ondatamessagereceived)

Defined in: [Observers/DataMessage/DataMessageObserver.common.ts:7](https://github.com/atabix/nativescript-plugins/blob/90ee9de/packages/nativescript-amazon-chime/support/Observers/DataMessage/DataMessageObserver.common.ts#L7)
