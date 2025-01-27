---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/heft](./heft.md) &gt; [BuildStageHooks](./heft.buildstagehooks.md)

## BuildStageHooks class

<b>Signature:</b>

```typescript
export declare class BuildStageHooks extends StageHooksBase<IBuildStageProperties>
```

<b>Extends:</b> [StageHooksBase](./heft.stagehooksbase.md) &lt;[IBuildStageProperties](./heft.ibuildstageproperties.md) &gt;

## Properties

| Property                                           | Modifiers | Type                                                                  | Description |
| -------------------------------------------------- | --------- | --------------------------------------------------------------------- | ----------- |
| [bundle](./heft.buildstagehooks.bundle.md)         |           | SyncHook&lt;[IBundleSubstage](./heft.ibundlesubstage.md) &gt;         |             |
| [compile](./heft.buildstagehooks.compile.md)       |           | SyncHook&lt;[ICompileSubstage](./heft.icompilesubstage.md) &gt;       |             |
| [postBuild](./heft.buildstagehooks.postbuild.md)   |           | SyncHook&lt;[IPostBuildSubstage](./heft.ipostbuildsubstage.md) &gt;   |             |
| [preCompile](./heft.buildstagehooks.precompile.md) |           | SyncHook&lt;[IPreCompileSubstage](./heft.iprecompilesubstage.md) &gt; |             |
