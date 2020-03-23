# How to compile
```
 $ rustc main.rs
```

# Tips
- rustfmt : formating tool
- 4 space, not tab
- println! : macro (! : macro)
- crate : code package

# Cargo
- Rust's system and package manager
- Build Code
- Download libraries & build libraries
- Manage dependency

## Create new project
```
$ cargo new hello_cargo --bin
```


## Build
cargo build
```
$ cargo build
```
or 

cargo check : compiling with execution
```
$ cargo check
```
__cargo check__ is faster than __cargo build__



## Run
Build & Run
```
$ cargo run
```

Run
```
$ ./target/debug/hello_cargo
```


## with github
```
$ git clone myid.com/someproject
$ cd someproject
$ cargo build
```




# Ref
https://rinthel.github.io/rust-lang-book-ko/ch01-02-hello-world.html

https://rinthel.github.io/rust-lang-book-ko/ch01-03-hello-cargo.html

https://doc.rust-lang.org/cargo/