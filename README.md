# Bittopos CLI

The `btto` command-line interface for local Bittopos workspaces.

## Build and test

```bash
cargo build --locked
cargo test --locked
cargo run -- --help
```

The CLI depends on the canonical shared core crate. Its Git dependency is pinned to an immutable reviewed commit; update the revision through a PR when adopting a new core version.

License: MPL-2.0.
