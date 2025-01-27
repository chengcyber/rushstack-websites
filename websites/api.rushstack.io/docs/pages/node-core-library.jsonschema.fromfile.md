---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [JsonSchema](./node-core-library.jsonschema.md) &gt; [fromFile](./node-core-library.jsonschema.fromfile.md)

## JsonSchema.fromFile() method

Registers a JsonSchema that will be loaded from a file on disk.

<b>Signature:</b>

```typescript
static fromFile(filename: string, options?: IJsonSchemaFromFileOptions): JsonSchema;
```

## Parameters

| Parameter | Type                                                                            | Description |
| --------- | ------------------------------------------------------------------------------- | ----------- |
| filename  | string                                                                          |             |
| options   | [IJsonSchemaFromFileOptions](./node-core-library.ijsonschemafromfileoptions.md) |             |

<b>Returns:</b>

[JsonSchema](./node-core-library.jsonschema.md)

## Remarks

NOTE: An error occurs if the file does not exist; however, the file itself is not loaded or validated until it the schema is actually used.
