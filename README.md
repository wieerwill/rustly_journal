# Rusty Journal
The application is a command line task tracker. It records our tasks in a text file, displays them as a list in the terminal, and lets us mark them as done.

This programme follows the Microsoft Learning Path for [Rust](https://learn.microsoft.com/de-de/training/modules/rust-create-command-line-program/)

1. install rust toolchain with [rustup](https://rustup.rs)
2. `cargo run` to start the app

Try it out:
```sh
cargo run -- -j test-journal.json add "buy milk"
cargo run -- -j test-journal.json add "take the dog for a walk"
cargo run -- -j test-journal.json add "water the plants"
cargo run -- -j test-journal.json list
cargo run -- -j test-journal.json done 2
cargo run -- -j test-journal.json list
```

To compile the programme, switch to the terminal and execute the command `cargo run --release`.

The compiled binary (the executable) is located in the `target/release/` directory and is named after the project name. If you are using macOS or Linux, it will be called `rusty-journal`. If you use Windows, it is called `rusty-journal.exe`.