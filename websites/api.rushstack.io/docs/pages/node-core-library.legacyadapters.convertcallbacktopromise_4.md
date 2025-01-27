---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [LegacyAdapters](./node-core-library.legacyadapters.md) &gt; [convertCallbackToPromise](./node-core-library.legacyadapters.convertcallbacktopromise_4.md)

## LegacyAdapters.convertCallbackToPromise() method

<b>Signature:</b>

```typescript
static convertCallbackToPromise<TResult, TError, TArg1, TArg2, TArg3, TArg4>(fn: (arg1: TArg1, arg2: TArg2, arg3: TArg3, arg4: TArg4, cb: LegacyCallback<TResult, TError>) => void, arg1: TArg1, arg2: TArg2, arg3: TArg3, arg4: TArg4): Promise<TResult>;
```

## Parameters

| Parameter | Type                                                                                                                                                 | Description |
| --------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| fn        | (arg1: TArg1, arg2: TArg2, arg3: TArg3, arg4: TArg4, cb: [LegacyCallback](./node-core-library.legacycallback.md) &lt;TResult, TError&gt;) =&gt; void |             |
| arg1      | TArg1                                                                                                                                                |             |
| arg2      | TArg2                                                                                                                                                |             |
| arg3      | TArg3                                                                                                                                                |             |
| arg4      | TArg4                                                                                                                                                |             |

<b>Returns:</b>

Promise&lt;TResult&gt;
