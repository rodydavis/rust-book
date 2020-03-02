# Getting Started

`$ cargo run`
`Hello, world!`

## Notes

- To import something that is not included with the few types Rust provides use: `use` to import the dependency
- To create a string variable: `let mut guess = String::new();`
- In Rust, variables are immutable by default
- To make a variable mutable append `mut`

```rust
let foo = 5; // immutable
let mut bar = 5; // mutable
```

- `::` means *associated function* (Some languages call this a static method)
- You’ll find a new function on many types, because it’s a common name for a function that makes a new value of some kind
- `let mut guess = String::new();` line has created a mutable variable that is currently bound to a new, empty instance of a String
- If we hadn’t put the use `std::io` line at the beginning of the program, we could have written this function call as `std::io::stdin`
- The `&` indicates that this argument is a *reference*
- references are immutable by default

```rust
let x = 5;
let y = 10;

println!("x = {} and y = {}", x, y);
```

- `cargo update` updates the dependencies and ignores the `Cargo.lock`
- Open the docs for all the packages in your browser: `cargo doc --open`
- You can shadow variables to convert values and keep the same name in scope
- When parsing numbers from strings you have to give the type as there can be many types of numbers
- When you are explicit on a type, any other variables used in the same scope that interact will use the same type
- `_` is a catch all value