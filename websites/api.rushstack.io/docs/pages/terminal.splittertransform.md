---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/terminal](./terminal.md) &gt; [SplitterTransform](./terminal.splittertransform.md)

## SplitterTransform class

Use this instead of [TerminalTransform](./terminal.terminaltransform.md) if you need to output `ITerminalChunk` data to more than one destination.

<b>Signature:</b>

```typescript
export declare class SplitterTransform extends TerminalWritable
```

<b>Extends:</b> [TerminalWritable](./terminal.terminalwritable.md)

## Remarks

Splitting streams complicates the pipeline topology and can make debugging more difficult. For this reason, it is modeled as an explicit `SplitterTransform` node, rather than as a built-in feature of `TerminalTransform` .

## Constructors

| Constructor                                                             | Modifiers | Description                                                           |
| ----------------------------------------------------------------------- | --------- | --------------------------------------------------------------------- |
| [(constructor)(options)](./terminal.splittertransform._constructor_.md) |           | Constructs a new instance of the <code>SplitterTransform</code> class |

## Properties

| Property                                                     | Modifiers | Type                                                                     | Description |
| ------------------------------------------------------------ | --------- | ------------------------------------------------------------------------ | ----------- |
| [destinations](./terminal.splittertransform.destinations.md) |           | ReadonlyArray&lt;[TerminalWritable](./terminal.terminalwritable.md) &gt; |             |

## Methods

| Method                                                              | Modifiers | Description |
| ------------------------------------------------------------------- | --------- | ----------- |
| [onClose()](./terminal.splittertransform.onclose.md)                |           |             |
| [onWriteChunk(chunk)](./terminal.splittertransform.onwritechunk.md) |           |             |
