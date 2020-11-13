---
id: daf-w3c.w3cmessagehandler
title: W3cMessageHandler class
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Packages](./index.md) &gt; [daf-w3c](./daf-w3c.md) &gt; [W3cMessageHandler](./daf-w3c.w3cmessagehandler.md)

## W3cMessageHandler class

An implementation of the [AbstractMessageHandler](./daf-message-handler.abstractmessagehandler.md) .

This plugin can handle incoming W3C Verifiable Credentials and Presentations and prepare them for internal storage as [Message](./daf-message-handler.message.md) types.

The current version can only handle `JWT` encoded

<b>Signature:</b>

```typescript
export declare class W3cMessageHandler extends AbstractMessageHandler 
```
<b>Extends:</b> [AbstractMessageHandler](./daf-message-handler.abstractmessagehandler.md)

## Remarks

[IDataStore](./daf-core.idatastore.md)

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [handle(message, context)](./daf-w3c.w3cmessagehandler.handle.md) |  |  |