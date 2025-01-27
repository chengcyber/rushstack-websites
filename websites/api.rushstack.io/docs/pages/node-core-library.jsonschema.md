---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [JsonSchema](./node-core-library.jsonschema.md)

## JsonSchema class

Represents a JSON schema that can be used to validate JSON data files loaded by the JsonFile class.

<b>Signature:</b>

```typescript
export declare class JsonSchema
```

## Remarks

The schema itself is normally loaded and compiled later, only if it is actually required to validate an input. To avoid schema errors at runtime, it's recommended to create a unit test that calls JsonSchema.ensureCompiled() for each of your schema objects.

## Properties

| Property                                                 | Modifiers | Type   | Description                                                      |
| -------------------------------------------------------- | --------- | ------ | ---------------------------------------------------------------- |
| [shortName](./node-core-library.jsonschema.shortname.md) |           | string | Returns a short name for this schema, for use in error messages. |

## Methods

| Method                                                                                                                | Modifiers           | Description                                                                                                                            |
| --------------------------------------------------------------------------------------------------------------------- | ------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| [ensureCompiled()](./node-core-library.jsonschema.ensurecompiled.md)                                                  |                     | If not already done, this loads the schema from disk and compiles it.                                                                  |
| [fromFile(filename, options)](./node-core-library.jsonschema.fromfile.md)                                             | <code>static</code> | Registers a JsonSchema that will be loaded from a file on disk.                                                                        |
| [fromLoadedObject(schemaObject)](./node-core-library.jsonschema.fromloadedobject.md)                                  | <code>static</code> | Registers a JsonSchema that will be loaded from a file on disk.                                                                        |
| [validateObject(jsonObject, filenameForErrors, options)](./node-core-library.jsonschema.validateobject.md)            |                     | Validates the specified JSON object against this JSON schema. If the validation fails, an exception will be thrown.                    |
| [validateObjectWithCallback(jsonObject, errorCallback)](./node-core-library.jsonschema.validateobjectwithcallback.md) |                     | Validates the specified JSON object against this JSON schema. If the validation fails, a callback is called for each validation error. |
