# preferences-serde1
_Read and write user-specific application data in Rust_

[![Crates.io](https://img.shields.io/crates/v/preferences-serde1.svg)](https://crates.io/crates/preferences-serde1)
[![Documentation](https://docs.rs/preferences-serde1/badge.svg)](https://docs.rs/preferences-serde1/)
[![Crate License](https://img.shields.io/crates/l/preferences-serde1.svg)](https://crates.io/crates/preferences-serde1)

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
