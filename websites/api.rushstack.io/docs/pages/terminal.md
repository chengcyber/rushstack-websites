---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/terminal](./terminal.md)

## terminal package

This library implements a system for processing human readable text that will be output by console applications.

## Remarks

See the [TerminalWritable](./terminal.terminalwritable.md) documentation for an overview of the major concepts.

## Classes

| Class                                                                        | Description                                                                                                                                                                                                                                                                                                                           |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [CallbackWritable](./terminal.callbackwritable.md)                           | This class enables very basic [TerminalWritable.onWriteChunk()](./terminal.terminalwritable.onwritechunk.md) operations to be implemented as a callback function, avoiding the need to define a subclass of <code>TerminalWritable</code>.                                                                                            |
| [DiscardStdoutTransform](./terminal.discardstdouttransform.md)               | <b><i>(BETA)</i></b> <code>DiscardStdoutTransform</code> discards <code>stdout</code> chunks while fixing up malformed <code>stderr</code> lines.                                                                                                                                                                                     |
| [MockWritable](./terminal.mockwritable.md)                                   | <b><i>(BETA)</i></b> A [TerminalWritable](./terminal.terminalwritable.md) subclass for use by unit tests.                                                                                                                                                                                                                             |
| [NormalizeNewlinesTextRewriter](./terminal.normalizenewlinestextrewriter.md) | For use with [TextRewriterTransform](./terminal.textrewritertransform.md) , this rewriter converts all newlines to a standard format.                                                                                                                                                                                                 |
| [PrintUtilities](./terminal.printutilities.md)                               | A collection of utilities for printing messages to the console.                                                                                                                                                                                                                                                                       |
| [RemoveColorsTextRewriter](./terminal.removecolorstextrewriter.md)           | For use with [TextRewriterTransform](./terminal.textrewritertransform.md) , this rewriter removes ANSI escape codes including colored text.                                                                                                                                                                                           |
| [SplitterTransform](./terminal.splittertransform.md)                         | Use this instead of [TerminalTransform](./terminal.terminaltransform.md) if you need to output <code>ITerminalChunk</code> data to more than one destination.                                                                                                                                                                         |
| [StderrLineTransform](./terminal.stderrlinetransform.md)                     | <b><i>(BETA)</i></b> <code>StderrLineTransform</code> normalizes lines that mix characters from <code>stdout</code> and <code>stderr</code>, so that each output line is routed entirely to <code>stdout</code> or <code>stderr</code>.                                                                                               |
| [StdioSummarizer](./terminal.stdiosummarizer.md)                             | <b><i>(BETA)</i></b> Summarizes the results of a failed build task by returning a subset of <code>stderr</code> output not to exceed a specified maximum number of lines.                                                                                                                                                             |
| [StdioWritable](./terminal.stdiowritable.md)                                 | A [TerminalWritable](./terminal.terminalwritable.md) subclass that writes its output directly to the process <code>stdout</code> and <code>stderr</code> streams.                                                                                                                                                                     |
| [TerminalTransform](./terminal.terminaltransform.md)                         | The abstract base class for [TerminalWritable](./terminal.terminalwritable.md) objects that receive an input, transform it somehow, and then write the output to another <code>TerminalWritable</code>.                                                                                                                               |
| [TerminalWritable](./terminal.terminalwritable.md)                           | The abstract base class for objects that can present, route, or process text output for a console application. This output is typically prepared using the [Terminal](./node-core-library.terminal.md) API.                                                                                                                           |
| [TextRewriter](./terminal.textrewriter.md)                                   | The abstract base class for operations that can be applied by [TextRewriterTransform](./terminal.textrewritertransform.md) .                                                                                                                                                                                                          |
| [TextRewriterTransform](./terminal.textrewritertransform.md)                 | A [TerminalTransform](./terminal.terminaltransform.md) subclass that performs one or more [TextRewriter](./terminal.textrewriter.md) operations. The most common operations are [NormalizeNewlinesTextRewriter](./terminal.normalizenewlinestextrewriter.md) and [RemoveColorsTextRewriter](./terminal.removecolorstextrewriter.md) . |

## Enumerations

| Enumeration                                          | Description                                                                                        |
| ---------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| [TerminalChunkKind](./terminal.terminalchunkkind.md) | Specifies the kind of data represented by a [ITerminalChunk](./terminal.iterminalchunk.md) object. |

## Interfaces

| Interface                                                                                    | Description                                                                                                            |
| -------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| [ICallbackWritableOptions](./terminal.icallbackwritableoptions.md)                           | Constructor options for [CallbackWritable](./terminal.callbackwritable.md) .                                           |
| [IDiscardStdoutTransformOptions](./terminal.idiscardstdouttransformoptions.md)               | <b><i>(BETA)</i></b> Constructor options for [DiscardStdoutTransform](./terminal.discardstdouttransform.md)            |
| [INormalizeNewlinesTextRewriterOptions](./terminal.inormalizenewlinestextrewriteroptions.md) | Constructor options for [NormalizeNewlinesTextRewriter](./terminal.normalizenewlinestextrewriter.md)                   |
| [ISplitterTransformOptions](./terminal.isplittertransformoptions.md)                         | Constructor options for [SplitterTransform](./terminal.splittertransform.md) .                                         |
| [IStdioLineTransformOptions](./terminal.istdiolinetransformoptions.md)                       | <b><i>(BETA)</i></b> Constructor options for [StderrLineTransform](./terminal.stderrlinetransform.md)                  |
| [IStdioSummarizerOptions](./terminal.istdiosummarizeroptions.md)                             | <b><i>(BETA)</i></b> Constructor options for [StdioSummarizer](./terminal.stdiosummarizer.md) .                        |
| [ITerminalChunk](./terminal.iterminalchunk.md)                                               | Represents a chunk of output that will ultimately be written to a [TerminalWritable](./terminal.terminalwritable.md) . |
| [ITerminalTransformOptions](./terminal.iterminaltransformoptions.md)                         | Constructor options for [TerminalTransform](./terminal.terminaltransform.md) .                                         |
| [ITerminalWritableOptions](./terminal.iterminalwritableoptions.md)                           | Constructor options for [TerminalWritable](./terminal.terminalwritable.md)                                             |
| [ITextRewriterTransformOptions](./terminal.itextrewritertransformoptions.md)                 | Constructor options for [TextRewriterTransform](./terminal.textrewritertransform.md) .                                 |

## Variables

| Variable                                                     | Description                                    |
| ------------------------------------------------------------ | ---------------------------------------------- |
| [DEFAULT_CONSOLE_WIDTH](./terminal.default_console_width.md) | A sensible fallback column width for consoles. |

## Type Aliases

| Type Alias                                           | Description                                                                             |
| ---------------------------------------------------- | --------------------------------------------------------------------------------------- |
| [TextRewriterState](./terminal.textrewriterstate.md) | Represents the internal state of a [TextRewriter](./terminal.textrewriter.md) subclass. |
