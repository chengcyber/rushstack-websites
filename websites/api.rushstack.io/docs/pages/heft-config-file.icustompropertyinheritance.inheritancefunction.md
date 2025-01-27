---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft-config-file](./heft-config-file.md) &gt; [ICustomPropertyInheritance](./heft-config-file.icustompropertyinheritance.md) &gt; [inheritanceFunction](./heft-config-file.icustompropertyinheritance.inheritancefunction.md)

## ICustomPropertyInheritance.inheritanceFunction property

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Provides a custom inheritance function. This function takes two arguments: the first is the child file's object, and the second is the parent file's object. The function should return the resulting combined object.

<b>Signature:</b>

```typescript
inheritanceFunction: PropertyInheritanceCustomFunction<TObject>;
```
