---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/ts-command-line](./ts-command-line.md) &gt; [ICommandLineChoiceListDefinition](./ts-command-line.icommandlinechoicelistdefinition.md)

## ICommandLineChoiceListDefinition interface

For use with [CommandLineParameterProvider.defineChoiceListParameter()](./ts-command-line.commandlineparameterprovider.definechoicelistparameter.md) , this interface defines a command line parameter which is constrained to a list of possible options. The parameter can be specified multiple times to build a list.

<b>Signature:</b>

```typescript
export interface ICommandLineChoiceListDefinition extends IBaseCommandLineDefinition
```

<b>Extends:</b> [IBaseCommandLineDefinition](./ts-command-line.ibasecommandlinedefinition.md)

## Properties

| Property                                                                           | Type                               | Description                                                                                       |
| ---------------------------------------------------------------------------------- | ---------------------------------- | ------------------------------------------------------------------------------------------------- |
| [alternatives](./ts-command-line.icommandlinechoicelistdefinition.alternatives.md) | string\[\]                         | A list of strings (which contain no spaces), of possible options which can be selected            |
| [completions?](./ts-command-line.icommandlinechoicelistdefinition.completions.md)  | () =&gt; Promise&lt;string\[\]&gt; | <i>(Optional)</i> An optional callback that provides a list of custom choices for tab completion. |
