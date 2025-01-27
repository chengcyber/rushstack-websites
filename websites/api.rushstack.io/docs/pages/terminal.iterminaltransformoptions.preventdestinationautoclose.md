---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/terminal](./terminal.md) &gt; [ITerminalTransformOptions](./terminal.iterminaltransformoptions.md) &gt; [preventDestinationAutoclose](./terminal.iterminaltransformoptions.preventdestinationautoclose.md)

## ITerminalTransformOptions.preventDestinationAutoclose property

Prevents the [TerminalTransform.destination](./terminal.terminaltransform.destination.md) object from being closed automatically when the transform is closed.

<b>Signature:</b>

```typescript
preventDestinationAutoclose?: boolean;
```

## Remarks

When a transform is closed, normally it will automatically close its destination `TerminalWritable` object. There are two ways to prevent that: either by setting `preventDestinationAutoclose` to `true` for the transform, or by setting [TerminalWritable.preventAutoclose](./terminal.terminalwritable.preventautoclose.md) to `true` for the `destination` object.
