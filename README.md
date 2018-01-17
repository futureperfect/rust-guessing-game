# Guessing Game

Guessing game is a trivial example of a working rust program using cargo as
derived from [The Rust Programming Language, v2](https://doc.rust-lang.org/book/second-edition/ch02-00-guessing-game-tutorial.html).

The most notable features or rust-isms observed here are:

* using `extern crate rand` to import an external package; in this case, a
  crate that handles generation of random numbers
* `loop` as a looping construct
* `expect` as a crashing construct on error
* `match` as a means to match on a complex type returned from a fuction
  invocation, e.g. `parse()` returns a `Result` type which can be either `Ok` or
  `Err`. This pattern is apparently common within rust code.

