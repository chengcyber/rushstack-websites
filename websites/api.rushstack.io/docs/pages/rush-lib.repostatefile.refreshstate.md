---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [RepoStateFile](./rush-lib.repostatefile.md) &gt; [refreshState](./rush-lib.repostatefile.refreshstate.md)

## RepoStateFile.refreshState() method

Refresh the data contained in repo-state.json using the current state of the Rush repo, and save the file if changes were made.

<b>Signature:</b>

```typescript
refreshState(rushConfiguration: RushConfiguration): boolean;
```

## Parameters

| Parameter         | Type                                                 | Description                          |
| ----------------- | ---------------------------------------------------- | ------------------------------------ |
| rushConfiguration | [RushConfiguration](./rush-lib.rushconfiguration.md) | The Rush configuration for the repo. |

<b>Returns:</b>

boolean

true if the file was modified, otherwise false.
