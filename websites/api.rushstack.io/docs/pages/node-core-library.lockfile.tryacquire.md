---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [LockFile](./node-core-library.lockfile.md) &gt; [tryAcquire](./node-core-library.lockfile.tryacquire.md)

## LockFile.tryAcquire() method

Attempts to create a lockfile with the given filePath.

<b>Signature:</b>

```typescript
static tryAcquire(resourceFolder: string, resourceName: string): LockFile | undefined;
```

## Parameters

| Parameter      | Type   | Description                                                                                                                                    |
| -------------- | ------ | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| resourceFolder | string | The folder where the lock file will be created                                                                                                 |
| resourceName   | string | An alphanumeric name that describes the resource being locked. This will become the filename of the temporary file created to manage the lock. |

<b>Returns:</b>

[LockFile](./node-core-library.lockfile.md) \| undefined

If successful, returns a `LockFile` instance. If unable to get a lock, returns `undefined` .
