### Guessing Game in Rust!

##### This is the famous guessing game implemented in rust. I wrote while I was making my baby steps in rust. See [rust-book](https://doc.rust-lang.org/book) for more exercises.

###### Here are the steps to test the code:

* Clone the repo:
```
git clone https://github.com/khalfella/guessing_game.git
```

* Compile the code:

```
$ cargo build
   Compiling libc v0.2.50
   Compiling rand v0.4.6
   Compiling rand v0.3.23
   Compiling guessing_game v0.1.0 (/Users/mohamed.khalfella/projects/guessing_game)
    Finished dev [unoptimized + debuginfo] target(s) in 4.09s
```

* Play the game!

```
$ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.06s
     Running `target/debug/guessing_game`
Guess the number!
Please input your guess.
70
You guessed: 70
Too big
Please input your guess.
35
You guessed: 35
Too small
Please input your guess.
55
You guessed: 55
Too big
Please input your guess.
45
You guessed: 45
Too big
Please input your guess.
40
You guessed: 40
Too small
Please input your guess.
43
You guessed: 43
Too big
Please input your guess.
42
You guessed: 42
You win!
$
```
