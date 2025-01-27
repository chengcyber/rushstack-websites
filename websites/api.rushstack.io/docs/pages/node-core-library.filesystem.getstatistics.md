---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [FileSystem](./node-core-library.filesystem.md) &gt; [getStatistics](./node-core-library.filesystem.getstatistics.md)

## FileSystem.getStatistics() method

Gets the statistics for a particular filesystem object. If the path is a link, this function follows the link and returns statistics about the link target. Behind the scenes it uses `fs.statSync()` .

<b>Signature:</b>

```typescript
static getStatistics(path: string): FileSystemStats;
```

## Parameters

| Parameter | Type   | Description                                             |
| --------- | ------ | ------------------------------------------------------- |
| path      | string | The absolute or relative path to the filesystem object. |

<b>Returns:</b>

[FileSystemStats](./node-core-library.filesystemstats.md)
