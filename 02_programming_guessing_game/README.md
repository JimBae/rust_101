
# Programming a Guessing Game

# Keyword
- let
- match
- method
- associated functions

# Command
```
$ cargo new guessing_game --bin
```

## Cargo.toml file
Filename: Cargo.toml
```
[package]
name = "guessing_game"
version = "0.1.0"
authors = ["Your Name <you@example.com>"]

[dependencies]
```

# Processing a Guess

```
use std::io;

fn main() {
    println!("Guess the number!");
    println!("Please input your guess!");
    let mut guess = String::new();

    io::stdin().read_line(&mut guess).exepct("Failed to read line.");

    println!("You guessed: {}", guess);
}
```

## Storing Values with Variables
```
let mut guess = String::new();
```

```
let foo = 5;     // immutable
let mut bar = 5; // mutable
```

## Handling Potential Failture with the Result Type
Result types are enums(enumerations).
Variants of Result types are __Ok__ and __Err__.

## Printing Values with println! Placeholders

# Generating a Secret Number

## Using a Crate to Get More Functionality
- crate : rust's package
- install __rand__ crate 
Filename: Cargo.toml
```
[dependencies]
rand = "0.5.5"
```

```
$ cargo build
```



## Ensuring Reproducible Builds with the Cargo.lock File
## Updating a Crate to Get a New Version
## Generating a Random Number

# Comparing the Guess to the Secret Number

# Allowing Multiple Guesses with Looping

## Quitting After a Correct Guess

## Handling Invalid Input


# Ref
https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html

https://rinthel.github.io/rust-lang-book-ko/ch02-00-guessing-game-tutorial.html

 