---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [JsonNull](./node-core-library.jsonnull.md)

## JsonNull type

The Rush Stack lint rules discourage usage of `null` . However, JSON parsers always return JavaScript's `null` to keep the two syntaxes consistent. When creating interfaces that describe JSON structures, use `JsonNull` to avoid triggering the lint rule. Do not use `JsonNull` for any other purpose.

<b>Signature:</b>

```typescript
export declare type JsonNull = null;
```

## Remarks

If you are designing a new JSON file format, it's a good idea to avoid `null` entirely. In most cases there are better representations that convey more information about an item that is unknown, omitted, or disabled.

To understand why `null` is deprecated, please see the `@rushstack/eslint-plugin` documentation here:

[https://www.npmjs.com/package/@rushstack/eslint-plugin\#rushstackno-null](https://www.npmjs.com/package/@rushstack/eslint-plugin#rushstackno-null)
