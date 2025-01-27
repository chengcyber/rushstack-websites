---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [IConfigurationEnvironmentVariable](./rush-lib.iconfigurationenvironmentvariable.md)

## IConfigurationEnvironmentVariable interface

Represents the value of an environment variable, and if the value should be overridden if the variable is set in the parent environment.

<b>Signature:</b>

```typescript
export interface IConfigurationEnvironmentVariable
```

## Properties

| Property                                                              | Type    | Description                                                                                                                                 |
| --------------------------------------------------------------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| [override?](./rush-lib.iconfigurationenvironmentvariable.override.md) | boolean | <i>(Optional)</i> Set to true to override the environment variable even if it is set in the parent environment. The default value is false. |
| [value](./rush-lib.iconfigurationenvironmentvariable.value.md)        | string  | Value of the environment variable                                                                                                           |
