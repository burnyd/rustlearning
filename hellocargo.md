cargo --version
cargo 1.64.0 (387270bc7 2022-09-16)

rustprojects cargo new hello_cargo
     Created binary (application) `hello_cargo` package

^^ This creats the hello_cargo directory.

rustprojects tree hello_cargo
hello_cargo
├── Cargo.toml
└── src
    └── main.rs

1 directory, 2 files

## Building a binary with cargo.
hello_cargo git:(main) ✗ cargo build
   Compiling hello_cargo v0.1.0 (/home/burnyd/projects/rustlearning/rustprojects/hello_cargo)
    Finished dev [unoptimized + debuginfo] target(s) in 0.24s

## This created a bunch of artifacts
The /target directory is now here with the binary within the debug directory.
➜  debug git:(main) ✗ ./hello_cargo

## Or you can cargo run it.
hello_cargo git:(main) ✗ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
     Running `target/debug/hello_cargo`
Hello, world!

## Cargo check

hello_cargo git:(main) ✗ cargo check
    Checking hello_cargo v0.1.0 (/home/burnyd/projects/rustlearning/rustprojects/hello_cargo)
    Finished dev [unoptimized + debuginfo] target(s) in 0.05s

