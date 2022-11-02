use std::io;

fn main() {
    println!("Guess the number!");

    println!("Please input your guess.");

    let mut guess = String::new();

    io::stdin()
        .read_line(&mut guess)
        .expect("Failed to read line");

    println!("You guessed: {guess}");
}

- std::io;
### So rust needs std library just to keep things super minimal.
So this means import the io library which comes from the std library.

- let mut guess = String::new();
### Rust variables are immutable by default so you have to use let mut to make guess mutable.  Immutable meaning once you declair a var its never going to change.

## Example
let apples = 5; // immutable
let mut bananas = 5; // mutable

-  let mut guess = String::new();

The :: syntax in the ::new line indicates that new is an associated function of the String type. An associated function is a function that’s implemented on a type, in this case String. This new function creates a new, empty string. You’ll find a new function on many types, because it’s a common name for a function that makes a new value of some kind.


