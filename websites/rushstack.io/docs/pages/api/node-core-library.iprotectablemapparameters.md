---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [IProtectableMapParameters](./node-core-library.iprotectablemapparameters.md)

## IProtectableMapParameters interface

Constructor parameters for [ProtectableMap](./node-core-library.protectablemap.md)

<b>Signature:</b>

```typescript
export interface IProtectableMapParameters<K, V> 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [onClear?](./node-core-library.iprotectablemapparameters.onclear.md) | (source: [ProtectableMap](./node-core-library.protectablemap.md) &lt;K, V&gt;) =&gt; void | <i>(Optional)</i> An optional hook that will be invoked before Map.clear() is performed. |
|  [onDelete?](./node-core-library.iprotectablemapparameters.ondelete.md) | (source: [ProtectableMap](./node-core-library.protectablemap.md) &lt;K, V&gt;, key: K) =&gt; void | <i>(Optional)</i> An optional hook that will be invoked before Map.delete() is performed. |
|  [onSet?](./node-core-library.iprotectablemapparameters.onset.md) | (source: [ProtectableMap](./node-core-library.protectablemap.md) &lt;K, V&gt;, key: K, value: V) =&gt; V | <i>(Optional)</i> An optional hook that will be invoked before Map.set() is performed. |
