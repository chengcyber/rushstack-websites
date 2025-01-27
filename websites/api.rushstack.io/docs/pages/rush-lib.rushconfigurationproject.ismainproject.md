---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [RushConfigurationProject](./rush-lib.rushconfigurationproject.md) &gt; [isMainProject](./rush-lib.rushconfigurationproject.ismainproject.md)

## RushConfigurationProject.isMainProject property

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Indicate whether this project is the main project for the related version policy.

False if the project is not for publishing. True if the project is individually versioned or if its lockstep version policy does not specify main project. False if the project is lockstepped and is not the main project for its version policy.

<b>Signature:</b>

```typescript
get isMainProject(): boolean;
```
