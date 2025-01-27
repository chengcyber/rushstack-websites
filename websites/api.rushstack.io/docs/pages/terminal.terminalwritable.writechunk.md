---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/terminal](./terminal.md) &gt; [TerminalWritable](./terminal.terminalwritable.md) &gt; [writeChunk](./terminal.terminalwritable.writechunk.md)

## TerminalWritable.writeChunk() method

Upstream objects call this method to provide inputs to this object.

<b>Signature:</b>

```typescript
/** @sealed */
writeChunk(chunk: ITerminalChunk): void;
```

## Parameters

| Parameter | Type                                           | Description |
| --------- | ---------------------------------------------- | ----------- |
| chunk     | [ITerminalChunk](./terminal.iterminalchunk.md) |             |

<b>Returns:</b>

void

## Remarks

The subclass provides its implementation via the the [TerminalWritable.onWriteChunk()](./terminal.terminalwritable.onwritechunk.md) method, which is called by `writeChunk()` .

The object that calls `writeChunk()` must call `close()` when it is finished; failing to do so may introduce a resource leak, or may prevent some buffered data from being written.
