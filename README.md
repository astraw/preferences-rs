# preferences-serde1
_Read and write user-specific application data in Rust_

This is a replacement for the old
[`preferences`](https://crates.io/crates/preferences) crate to use `serde`
version 1.0. To update your old `Cargo.toml` which previously looked like this:

```toml
preferences = "1.1"
```

use this:

```toml
preferences = {version="2.0.0", package = "preferences-serde1"}
```
