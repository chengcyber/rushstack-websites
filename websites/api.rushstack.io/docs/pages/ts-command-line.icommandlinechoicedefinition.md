---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/ts-command-line](./ts-command-line.md) &gt; [ICommandLineChoiceDefinition](./ts-command-line.icommandlinechoicedefinition.md)

## ICommandLineChoiceDefinition interface

For use with [CommandLineParameterProvider.defineChoiceParameter()](./ts-command-line.commandlineparameterprovider.definechoiceparameter.md) , this interface defines a command line parameter which is constrained to a list of possible options.

<b>Signature:</b>

```typescript
export interface ICommandLineChoiceDefinition extends IBaseCommandLineDefinition
```

<b>Extends:</b> [IBaseCommandLineDefinition](./ts-command-line.ibasecommandlinedefinition.md)

## Properties

| Property                                                                        | Type                               | Description                                                                                               |
| ------------------------------------------------------------------------------- | ---------------------------------- | --------------------------------------------------------------------------------------------------------- |
| [alternatives](./ts-command-line.icommandlinechoicedefinition.alternatives.md)  | string\[\]                         | A list of strings (which contain no spaces), of possible options which can be selected                    |
| [completions?](./ts-command-line.icommandlinechoicedefinition.completions.md)   | () =&gt; Promise&lt;string\[\]&gt; | <i>(Optional)</i> An optional callback that provides a list of custom choices for tab completion.         |
| [defaultValue?](./ts-command-line.icommandlinechoicedefinition.defaultvalue.md) | string                             | <i>(Optional)</i> The default value which will be used if the parameter is omitted from the command line. |
