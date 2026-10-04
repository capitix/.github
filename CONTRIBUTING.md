# Contributing

## Repositories

Each service has its own repository (ADR-024) and may use any language and data store (ADR-023, ADR-006). Services interoperate only through published contracts; never through another service's code or data store.

## Branches

- `main` is the only long-lived branch.
- Work on short-lived branches named `<type>/<topic>`, for example `feat/payment-holds`, `fix/merge-event`, `docs/adr-025`.
- Open a pull request into `main`. Pull requests are squash-merged.

## Commit messages

Use [Conventional Commits](https://www.conventionalcommits.org/), with an optional area scope:

```
feat(api): add payment holds
fix(feed): stamp sequence after commit
docs(adr): record ADR-025
```

Types: `feat`, `fix`, `docs`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`. Mark breaking changes with `!` or a `BREAKING CHANGE:` footer. Commits, pull requests, and documentation carry no AI attribution.

## Releases

Each repository is versioned independently and tagged `vX.Y.Z`. Localization packs are tagged `<owner>.<JURISDICTION>/<version>`.

## Architecture changes

Architecture decisions are proposed as pull requests to the `architecture` repository. Merging an ADR pull request accepts the decision.
