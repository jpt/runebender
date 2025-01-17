# Runebender

A font editor written in Rust, currently in very early stages.

**This software is very raw, and is not yet suitable for use**.

## Building

The only way to run Runebender is to build it yourself, from source. This
requires installing Rust; instructions are available at
[rustup.rs](https://rustup.rs).

## Running

To run on a UFO file:

```rust
cargo run -- optional/path/to/some/unifedfontobject.ufo
```

UFO files may also be opened with file>open in the running program.

## Contributions

Contributions are welcome. The [Rust Code of Conduct] applies. Please feel free to add your name to the [AUTHORS] file in any substantive pull request.

A very good place to ask questions and discuss development work is our
[Zulip chat instance](https://xi.zulipchat.com), in the [#runebender](https://xi.zulipchat.com/#narrow/stream/197829-runebender) channel.

## License

All files in this repository are licensed under the [Apache 2.0](LICENSE) license.

[Rust Code of Conduct]: https://www.rust-lang.org/policies/code-of-conduct
[AUTHORS]: AUTHORS
