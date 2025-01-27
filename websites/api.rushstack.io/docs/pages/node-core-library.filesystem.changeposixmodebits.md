---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [FileSystem](./node-core-library.filesystem.md) &gt; [changePosixModeBits](./node-core-library.filesystem.changeposixmodebits.md)

## FileSystem.changePosixModeBits() method

Changes the permissions (i.e. file mode bits) for a filesystem object. Behind the scenes it uses `fs.chmodSync()` .

<b>Signature:</b>

```typescript
static changePosixModeBits(path: string, mode: PosixModeBits): void;
```

## Parameters

| Parameter | Type                                                  | Description                                                         |
| --------- | ----------------------------------------------------- | ------------------------------------------------------------------- |
| path      | string                                                | The absolute or relative path to the object that should be updated. |
| mode      | [PosixModeBits](./node-core-library.posixmodebits.md) |                                                                     |

<b>Returns:</b>

void
