---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [PosixModeBits](./node-core-library.posixmodebits.md)

## PosixModeBits enum

An integer value used to specify file permissions for POSIX-like operating systems.

<b>Signature:</b>

```typescript
export declare const enum PosixModeBits
```

## Enumeration Members

| Member        | Value            | Description                                                                                                                                           |
| ------------- | ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| AllExecute    | <code>73</code>  | An alias combining OthersExecute, GroupExecute, and UserExecute permission bits.                                                                      |
| AllRead       | <code>292</code> | An alias combining OthersRead, GroupRead, and UserRead permission bits.                                                                               |
| AllWrite      | <code>146</code> | An alias combining OthersWrite, GroupWrite, and UserWrite permission bits.                                                                            |
| GroupExecute  | <code>8</code>   | Indicates that users belonging to the item's group can execute the item (if it is a file) or search the item (if it is a directory).                  |
| GroupRead     | <code>32</code>  | Indicates that users belonging to the item's group can read the item.                                                                                 |
| GroupWrite    | <code>16</code>  | Indicates that users belonging to the item's group can modify the item.                                                                               |
| None          | <code>0</code>   | A zero value where no permissions bits are set.                                                                                                       |
| OthersExecute | <code>1</code>   | Indicates that other users (besides the item's owner user or group) can execute the item (if it is a file) or search the item (if it is a directory). |
| OthersRead    | <code>4</code>   | Indicates that other users (besides the item's owner user or group) can read the item.                                                                |
| OthersWrite   | <code>2</code>   | Indicates that other users (besides the item's owner user or group) can modify the item.                                                              |
| UserExecute   | <code>64</code>  | Indicates that the item's owner can execute the item (if it is a file) or search the item (if it is a directory).                                     |
| UserRead      | <code>256</code> | Indicates that the item's owner can read the item.                                                                                                    |
| UserWrite     | <code>128</code> | Indicates that the item's owner can modify the item.                                                                                                  |

## Remarks

This bitfield corresponds to the "mode_t" structure described in this document: http://pubs.opengroup.org/onlinepubs/9699919799/basedefs/sys\_stat.h.html

It is used with NodeJS APIs such as fs.Stat.mode and fs.chmodSync(). These values represent a set of permissions and can be combined using bitwise arithmetic.

POSIX is a registered trademark of the Institute of Electrical and Electronic Engineers, Inc.
