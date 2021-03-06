---
id: core.iidentifier
title: IIdentifier interface
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## IIdentifier interface

Identifier interface

<b>Signature:</b>

```typescript
export interface IIdentifier
```

## Properties

| Property                                                 | Type                                | Description                                                                          |
| -------------------------------------------------------- | ----------------------------------- | ------------------------------------------------------------------------------------ |
| [alias](./core.iidentifier.alias.md)                     | string                              | Optional. Identifier alias. Can be used to reference an object in an external system |
| [controllerKeyId](./core.iidentifier.controllerkeyid.md) | string                              | Controller key id                                                                    |
| [did](./core.iidentifier.did.md)                         | string                              | Decentralized identifier                                                             |
| [keys](./core.iidentifier.keys.md)                       | [IKey](./core.ikey.md) \[\]         | Array of managed keys                                                                |
| [provider](./core.iidentifier.provider.md)               | string                              | Identifier provider name                                                             |
| [services](./core.iidentifier.services.md)               | [IService](./core.iservice.md) \[\] | Array of services                                                                    |
