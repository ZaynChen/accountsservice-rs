# accountsservice-rs
The Rust bindings of accountsservice

## Recommandation

using [zbus][zbus] instead of this crate, because [zbus][zbus] provides
Rust API for D-Bus communication, and this crate is a glib C bindings.

## Usage

```toml
accountsservice = { git = "https://github.com/ZaynChen/accountsservice-rs.git", version = "0.1.0" }
```

[zbus]: https://github.com/z-galaxy/zbus "zbus"
