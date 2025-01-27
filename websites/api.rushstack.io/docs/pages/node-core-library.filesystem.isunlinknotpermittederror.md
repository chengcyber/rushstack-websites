---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [FileSystem](./node-core-library.filesystem.md) &gt; [isUnlinkNotPermittedError](./node-core-library.filesystem.isunlinknotpermittederror.md)

## FileSystem.isUnlinkNotPermittedError() method

Returns true if the error object indicates that the `unlink` system call failed due to a permissions issue (`EPERM` ).

<b>Signature:</b>

```typescript
static isUnlinkNotPermittedError(error: Error): boolean;
```

## Parameters

| Parameter | Type  | Description |
| --------- | ----- | ----------- |
| error     | Error |             |

<b>Returns:</b>

boolean
