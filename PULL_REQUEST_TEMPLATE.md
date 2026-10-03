## Summary

<!-- What changes and why. Link the issue or ADR. -->

## Modules affected

<!-- Module identifiers, for example: ap, contracts/ap -->

## Checklist

- [ ] Conventional Commit title with module scope
- [ ] No imports of another service's code (only `contracts/` and `kit/`)
- [ ] Migrations touch only this service's own database
- [ ] Contract changes are additive within the major version, or a new major version is introduced (ADR-008)
- [ ] Tests added or updated
