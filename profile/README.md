# Capitix

A modular business platform: independently useful finance, supply chain, commercial, operations, and people modules. Each module lives in its own repository, may use any language and data store, and interacts with others only through versioned APIs, events, and contracts.

| Repository | Purpose |
|---|---|
| [architecture](https://github.com/capitix/architecture) | Architecture, decision records, specifications, and the service registry |
| [contracts](https://github.com/capitix/contracts) | Common language-neutral schemas |
| [conformance](https://github.com/capitix/conformance) | Black-box conformance suite every service passes |
| [kit-rust](https://github.com/capitix/kit-rust) | Optional Rust reference implementations |
| [localization](https://github.com/capitix/localization) | Localization packs and jurisdiction profiles |
| [distribution](https://github.com/capitix/distribution) | Installation bundles and packaging per deployment profile |
| [infrastructure](https://github.com/capitix/infrastructure) | Infrastructure as code for vendor operations |
| One repository per service | For example `general-ledger`, created as each service's design begins |
