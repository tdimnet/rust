# rust
I'm learning Rust

## Commands

- `cargo new`: creating a project
- `cargo build`: building a project
- `cargo run`: building and running the project in one step
- `cargo check`: building a project, without producing a binary, to check for
  errors

## Traditional Workflow

```
# Cloning the project
$ git clone example.org/someproject

# Cd into it
$ cd someproject

# Building/starting working on it
$ cargo build
```

## Variables

```
let apples = 5; // immutable
let mut bananas = 5; // mutable
```

## The **Result** enum

- **Result** is an enumeration which is a type that can be in one of multiple
  states. Each possible state is called a **variant**.
- **Result**'s variants are __Ok__ and __Err__.


