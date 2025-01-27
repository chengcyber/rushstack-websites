---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor-model](./api-extractor-model.md) &gt; [ExcerptToken](./api-extractor-model.excerpttoken.md)

## ExcerptToken class

Represents a fragment of text belonging to an [Excerpt](./api-extractor-model.excerpt.md) object.

<b>Signature:</b>

```typescript
export declare class ExcerptToken
```

## Constructors

| Constructor                                                                                          | Modifiers | Description                                                      |
| ---------------------------------------------------------------------------------------------------- | --------- | ---------------------------------------------------------------- |
| [(constructor)(kind, text, canonicalReference)](./api-extractor-model.excerpttoken._constructor_.md) |           | Constructs a new instance of the <code>ExcerptToken</code> class |

## Properties

| Property                                                                       | Modifiers | Type                                                          | Description                                                                                                                                                  |
| ------------------------------------------------------------------------------ | --------- | ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [canonicalReference](./api-extractor-model.excerpttoken.canonicalreference.md) |           | DeclarationReference \| undefined                             | The hyperlink target for a token whose type is <code>ExcerptTokenKind.Reference</code>. For other token types, this property will be <code>undefined</code>. |
| [kind](./api-extractor-model.excerpttoken.kind.md)                             |           | [ExcerptTokenKind](./api-extractor-model.excerpttokenkind.md) | Indicates the kind of token.                                                                                                                                 |
| [text](./api-extractor-model.excerpttoken.text.md)                             |           | string                                                        | The text fragment.                                                                                                                                           |
