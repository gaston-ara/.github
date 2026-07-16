# Pull Request

## Linked Issue

<!-- Use "Closes #N". The linked issue must be approved before opening. -->

Closes #

## PR Type

<!-- Select exactly one and add the matching type:* label. -->

- [ ] Bug (`type:bug`)
- [ ] Feature (`type:feature`)
- [ ] Docs (`type:docs`)
- [ ] Refactor (`type:refactor`)
- [ ] Chore (`type:chore`)
- [ ] Breaking (`type:breaking-change`)

## Summary

- <!-- Summary point -->
- <!-- Summary point -->

## Changes

| File or area    | Change                 |
| --------------- | ---------------------- |
| <!-- path -->   | <!-- description -->   |

## Chain Context

| Field         | Details                     |
| ------------- | --------------------------- |
| Strategy      | Single PR / chained PRs     |
| Current slice | <!-- slice -->              |
| Base / head   | `base` <- `head`            |
| Dependencies  | None                        |
| Previous PR   | None                        |
| Next PR       | None                        |
| Start state   | <!-- state before -->       |
| End state     | <!-- state after -->        |
| Out of scope  | <!-- excluded work -->      |

### Dependency Diagram

```text
base -> current PR -> next PR
```

## Test Plan

| Evidence             | Command or scenario | Result          |
| -------------------- | ------------------- | --------------- |
| Focused checks       | <!-- command -->    | <!-- result --> |
| Full checks          | <!-- command -->    | <!-- result --> |
| Runtime verification | <!-- scenario -->   | <!-- result --> |

## Rollback Boundary

<!-- Name what can be reverted without removing unrelated changes. -->

## Contributor Checklist

- [ ] The linked issue is approved and referenced with `Closes #N`.
- [ ] Exactly one PR type and one matching `type:*` label are selected.
- [ ] Focused, full, and runtime checks pass, or `N/A` is justified.
- [ ] Documentation is updated when behavior changes.
- [ ] Commits follow Conventional Commits.
- [ ] Commit messages contain no `Co-Authored-By` trailers.
