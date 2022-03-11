---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/module-minifier-plugin](./module-minifier-plugin.md)

## module-minifier-plugin package

## Classes

| Class                                                                                          | Description                                                                                                                                                                                                                                                                                                 |
| ---------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ModuleMinifierPlugin](./module-minifier-plugin.moduleminifierplugin.md)                       | Webpack plugin that minifies code on a per-module basis rather than per-asset. The actual minification is handled by the input <code>minifier</code> object.                                                                                                                                                |
| [NoopMinifier](./module-minifier-plugin.noopminifier.md)                                       | Minifier implementation that does not actually transform the code, for debugging.                                                                                                                                                                                                                           |
| [PortableMinifierModuleIdsPlugin](./module-minifier-plugin.portableminifiermoduleidsplugin.md) | Plugin responsible for converting the Webpack module ids (of whatever variety) to stable ids before code is handed to the minifier, then back again. Uses the node module identity of the target module. Will emit an error if it encounters multiple versions of the same package in the same compilation. |
| [SynchronousMinifier](./module-minifier-plugin.synchronousminifier.md)                         | Minifier implementation that synchronously minifies code on the main thread.                                                                                                                                                                                                                                |
| [WorkerPoolMinifier](./module-minifier-plugin.workerpoolminifier.md)                           | Minifier implementation that uses a thread pool for minification.                                                                                                                                                                                                                                           |

## Functions

| Function                                                                                                                    | Description                                                                                                                                          |
| --------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| [generateLicenseFileForAsset(compilation, asset, minifiedModules)](./module-minifier-plugin.generatelicensefileforasset.md) | Generates a companion asset containing all extracted comments. If it is non-empty, returns a banner comment directing users to said companion asset. |
| [rehydrateAsset(asset, moduleMap, banner)](./module-minifier-plugin.rehydrateasset.md)                                      | Rehydrates an asset with minified modules.                                                                                                           |

## Interfaces

| Interface                                                                                        | Description                                                                       |
| ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| [IAssetInfo](./module-minifier-plugin.iassetinfo.md)                                             | Information about a dehydrated webpack ECMAScript asset                           |
| [IDehydratedAssets](./module-minifier-plugin.idehydratedassets.md)                               | The set of data remaining to rehydrate in the current compilation                 |
| [IExtendedModule](./module-minifier-plugin.iextendedmodule.md)                                   | Extension of the webpack Module typings with members that are used by this Plugin |
| [IModuleInfo](./module-minifier-plugin.imoduleinfo.md)                                           | Information about a minified module                                               |
| [IModuleMinificationCallback](./module-minifier-plugin.imoduleminificationcallback.md)           | Callback passed to a minifier function                                            |
| [IModuleMinificationErrorResult](./module-minifier-plugin.imoduleminificationerrorresult.md)     | Result from the minifier function when an error is encountered.                   |
| [IModuleMinificationRequest](./module-minifier-plugin.imoduleminificationrequest.md)             | Request to the minifier                                                           |
| [IModuleMinificationSuccessResult](./module-minifier-plugin.imoduleminificationsuccessresult.md) | Result from the minifier on a successful minification.                            |
| [IModuleMinifier](./module-minifier-plugin.imoduleminifier.md)                                   | Object that can be invoked to minify code.                                        |
| [IModuleMinifierFunction](./module-minifier-plugin.imoduleminifierfunction.md)                   | An async function called to minify a module (or dehydrated chunk)                 |
| [IModuleMinifierPluginHooks](./module-minifier-plugin.imoduleminifierpluginhooks.md)             | Hooks provided by the ModuleMinifierPlugin                                        |
| [IModuleMinifierPluginOptions](./module-minifier-plugin.imoduleminifierpluginoptions.md)         | Options to the ModuleMinifierPlugin constructor                                   |
| [ISynchronousMinifierOptions](./module-minifier-plugin.isynchronousminifieroptions.md)           | Options for configuring the SynchronousMinifier                                   |
| [IWorkerPoolMinifierOptions](./module-minifier-plugin.iworkerpoolminifieroptions.md)             | Options for configuring the WorkerPoolMinifier                                    |

## Variables

| Variable                                                                             | Description                                                                                                                                                                                                          |
| ------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [CHUNK_MODULES_TOKEN](./module-minifier-plugin.chunk_modules_token.md)               | Token to replace the object or array of module definitions so that the minifier can operate on the Webpack runtime or chunk boilerplate in isolation                                                                 |
| [IDENTIFIER_LEADING_DIGITS](./module-minifier-plugin.identifier_leading_digits.md)   | The sorted sequence of leading digits for mangled identifiers Computed from character frequency analysis of the source code for OneDrive                                                                             |
| [IDENTIFIER_TRAILING_DIGITS](./module-minifier-plugin.identifier_trailing_digits.md) | The sorted sequence of trailing digits for mangled identifiers Computed from character frequency analysis of the source code for OneDrive                                                                            |
| [MODULE_WRAPPER_PREFIX](./module-minifier-plugin.module_wrapper_prefix.md)           | Prefix to wrap <code>function (module, **webpack_exports**, **webpack_require**) { ... }</code> so that the minifier doesn't delete it. Public because alternate Minifier implementations may wish to know about it. |
| [MODULE_WRAPPER_SUFFIX](./module-minifier-plugin.module_wrapper_suffix.md)           | Suffix to wrap <code>function (module, **webpack_exports**, **webpack_require**) { ... }</code> so that the minifier doesn't delete it. Public because alternate Minifier implementations may wish to know about it. |
| [STAGE_AFTER](./module-minifier-plugin.stage_after.md)                               | Stage \# to use when this should be the last tap in the hook                                                                                                                                                         |
| [STAGE_BEFORE](./module-minifier-plugin.stage_before.md)                             | Stage \# to use when this should be the first tap in the hook                                                                                                                                                        |

## Type Aliases

| Type Alias                                                                         | Description                                |
| ---------------------------------------------------------------------------------- | ------------------------------------------ |
| [IAssetMap](./module-minifier-plugin.iassetmap.md)                                 | A map from file names to dehydrated assets |
| [IModuleMap](./module-minifier-plugin.imodulemap.md)                               | A map from module ids to minified modules  |
| [IModuleMinificationResult](./module-minifier-plugin.imoduleminificationresult.md) | Result from the minifier.                  |