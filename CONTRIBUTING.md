# Contributing

## Branches

- `main` is the only long-lived branch and is protected.
- Work on short-lived branches named `<type>/<scope>-<topic>`, for example `feat/ap-payment-holds`, `fix/party-merge-event`, `docs/adr-022`, `chore/ci-cache`.
- Open a pull request into `main`. Pull requests are squash-merged.

## Commit messages

Use [Conventional Commits](https://www.conventionalcommits.org/) with the module identifier as scope:

```
feat(ap): add payment holds
fix(party): emit party.merged on duplicate merge
docs(architecture): record ADR-022
```

Types: `feat`, `fix`, `docs`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`. Mark breaking changes with `!` or a `BREAKING CHANGE:` footer.

## Releases

Modules, services, and kit packages are versioned independently and tagged as `<id>/vX.Y.Z` (for example `ap/v1.4.0`, `kit/outbox-relay/v1.0.0`). Localization packs are tagged `<owner>.<JURISDICTION>/<version>`.

## Architecture changes

Architecture decisions are proposed as pull requests to the `architecture` repository. Merging an ADR pull request accepts the decision.
