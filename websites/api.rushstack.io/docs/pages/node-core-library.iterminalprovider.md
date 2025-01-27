---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [ITerminalProvider](./node-core-library.iterminalprovider.md)

## ITerminalProvider interface

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Implement the interface to create a terminal provider. Terminal providers can be registered to a [Terminal](./node-core-library.terminal.md) instance to receive messages.

<b>Signature:</b>

```typescript
export interface ITerminalProvider
```

## Properties

| Property                                                                | Type    | Description                                                                                                            |
| ----------------------------------------------------------------------- | ------- | ---------------------------------------------------------------------------------------------------------------------- |
| [eolCharacter](./node-core-library.iterminalprovider.eolcharacter.md)   | string  | <b><i>(BETA)</i></b> This property should return the newline character the terminal provider expects.                  |
| [supportsColor](./node-core-library.iterminalprovider.supportscolor.md) | boolean | <b><i>(BETA)</i></b> This property should return true only if the terminal provider supports rendering console colors. |

## Methods

| Method                                                                  | Description                                                                                                                          |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| [write(data, severity)](./node-core-library.iterminalprovider.write.md) | <b><i>(BETA)</i></b> This function gets called on every terminal provider upon every message function call on the terminal instance. |
