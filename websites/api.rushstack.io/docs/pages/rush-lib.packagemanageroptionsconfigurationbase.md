---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [PackageManagerOptionsConfigurationBase](./rush-lib.packagemanageroptionsconfigurationbase.md)

## PackageManagerOptionsConfigurationBase class

Options that all package managers share.

<b>Signature:</b>

```typescript
export declare abstract class PackageManagerOptionsConfigurationBase implements IPackageManagerOptionsJsonBase
```

<b>Implements:</b> [IPackageManagerOptionsJsonBase](./rush-lib.ipackagemanageroptionsjsonbase.md)

## Remarks

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `PackageManagerOptionsConfigurationBase` class.

## Properties

| Property                                                                                           | Modifiers | Type                                                                 | Description                                                     |
| -------------------------------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------- | --------------------------------------------------------------- |
| [environmentVariables?](./rush-lib.packagemanageroptionsconfigurationbase.environmentvariables.md) |           | [IConfigurationEnvironment](./rush-lib.iconfigurationenvironment.md) | <i>(Optional)</i> Environment variables for the package manager |
