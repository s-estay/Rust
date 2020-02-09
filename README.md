# Rust

![](https://github.com/s-estay/Rust/blob/master/rustacean-flat-happy.png)

## Getting started

- Update Rust/Cargo: `rustup update`
- Create new project: `cargo new hello-rust`
- Compile and run: `cargo run`
- Check if project compiles (doesn't produce an executable): `cargo check` (faster than `cargo run`)
- Install dependencies: `cargo build`
- Compile with optimizations: `cargo build --release` (use when done with project)
- [Atom](https://atom.io/) will create a workspace outside the project folders called `Cargo.toml`:
```
[workspace]
members = ["hello-ferris", "hello-rust"]
```

## Definitions

- HAL: hardware abstraction layer

## References

- [Rust, getting started](https://www.rust-lang.org/learn/get-started)
- [Rust IDE support for Atom](https://github.com/rust-lang/atom-ide-rust)
