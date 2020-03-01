# Getting Started

`cargo build`
`./target/debug/hello_cargo`
`Hello, world!`

## Notes

- `cargo run` will compile and run the code for you in one step
- `cargo check` is used to see if you code compiles but does not generate a binary
- `cargo check` is faster than `cargo build`
- `cargo` commands are the same across Linux, Windows and MacOS
- `cargo build --release` is for building for release and optimization
- building for release is slower
- with simple projects `cargo` doesn't offer more than `rustc`
- `cargo` is great for complex projects with multiple crates

To checkout and run a project build with Rust:

```
$ git clone someurl.com/someproject
$ cd someproject
$ cargo build
```