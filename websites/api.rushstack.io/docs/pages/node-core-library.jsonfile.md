---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/node-core-library](./node-core-library.md) &gt; [JsonFile](./node-core-library.jsonfile.md)

## JsonFile class

Utilities for reading/writing JSON files.

<b>Signature:</b>

```typescript
export declare class JsonFile
```

## Methods

| Method                                                                                                                                        | Modifiers           | Description                                                                                                                 |
| --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| [load(jsonFilename)](./node-core-library.jsonfile.load.md)                                                                                    | <code>static</code> | Loads a JSON file.                                                                                                          |
| [loadAndValidate(jsonFilename, jsonSchema, options)](./node-core-library.jsonfile.loadandvalidate.md)                                         | <code>static</code> | Loads a JSON file and validate its schema.                                                                                  |
| [loadAndValidateAsync(jsonFilename, jsonSchema, options)](./node-core-library.jsonfile.loadandvalidateasync.md)                               | <code>static</code> | An async version of [JsonFile.loadAndValidate()](./node-core-library.jsonfile.loadandvalidate.md) .                         |
| [loadAndValidateWithCallback(jsonFilename, jsonSchema, errorCallback)](./node-core-library.jsonfile.loadandvalidatewithcallback.md)           | <code>static</code> | Loads a JSON file and validate its schema, reporting errors using a callback                                                |
| [loadAndValidateWithCallbackAsync(jsonFilename, jsonSchema, errorCallback)](./node-core-library.jsonfile.loadandvalidatewithcallbackasync.md) | <code>static</code> | An async version of [JsonFile.loadAndValidateWithCallback()](./node-core-library.jsonfile.loadandvalidatewithcallback.md) . |
| [loadAsync(jsonFilename)](./node-core-library.jsonfile.loadasync.md)                                                                          | <code>static</code> | An async version of [JsonFile.load()](./node-core-library.jsonfile.load.md) .                                               |
| [parseString(jsonContents)](./node-core-library.jsonfile.parsestring.md)                                                                      | <code>static</code> | Parses a JSON file's contents.                                                                                              |
| [save(jsonObject, jsonFilename, options)](./node-core-library.jsonfile.save.md)                                                               | <code>static</code> | Saves the file to disk. Returns false if nothing was written due to options.onlyIfChanged.                                  |
| [saveAsync(jsonObject, jsonFilename, options)](./node-core-library.jsonfile.saveasync.md)                                                     | <code>static</code> | An async version of [JsonFile.save()](./node-core-library.jsonfile.save.md) .                                               |
| [stringify(jsonObject, options)](./node-core-library.jsonfile.stringify.md)                                                                   | <code>static</code> | Serializes the specified JSON object to a string buffer.                                                                    |
| [updateString(previousJson, newJsonObject, options)](./node-core-library.jsonfile.updatestring.md)                                            | <code>static</code> | Serializes the specified JSON object to a string buffer.                                                                    |
| [validateNoUndefinedMembers(jsonObject)](./node-core-library.jsonfile.validatenoundefinedmembers.md)                                          | <code>static</code> | Used to validate a data structure before writing. Reports an error if there are any undefined members.                      |
