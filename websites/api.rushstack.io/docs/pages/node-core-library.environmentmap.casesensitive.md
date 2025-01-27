---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [EnvironmentMap](./node-core-library.environmentmap.md) &gt; [caseSensitive](./node-core-library.environmentmap.casesensitive.md)

## EnvironmentMap.caseSensitive property

Whether the environment variable names are case-sensitive.

<b>Signature:</b>

```typescript
readonly caseSensitive: boolean;
```

## Remarks

On Windows operating system, environment variables are case-insensitive. The map will preserve the variable name casing from the most recent assignment operation.
