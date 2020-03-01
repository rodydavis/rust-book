# Learning Rust

This repo contains all the projects I created while going through the Rust book.

https://doc.rust-lang.org/book/

`rustc 1.41.1 (f3e1a954d 2020-02-24)`

## Installing Rust

`curl https://sh.rustup.rs -sSf | sh`

## Bugs

- Fixed issue with VSCode Rust extension not seeing rustup

https://github.com/rust-lang/rls-vscode/issues/577

Updated my vscode settings file:

```json
{
    "rust-client.enableMultiProjectSetup": true,
    "rust-client.rustupPath": "/Users/rodydavis/.cargo/bin/rustup",
}
```