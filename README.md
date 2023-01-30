# rust-new-project-template
A good starting point for a new Rust project

## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)

## All Rust projects can follow this pattern:

## week1
1. Create a new repo using Rust New Project Template: https://github.com/noahgift/rust-new-project-template
2. Create a new Codespaces and use it
3. Use main.rs to call handle CLI and use lib.rs to handle logic and import clap in Cargo.toml as shown in this project.
4. Use `cargo run -- marco --name "Marco" or whatever you want to call your project.
Put your "ideas" in as comments in rust to seed GitHub Copilot, i.e //build add function
5. Run make format i.e. cargo format
6. Run make lint i.e. cargo clippy --quiet
7. Run project: cargo run -- --help
8. Push your changes to allow GitHub Actions to: format check, lint check, and other actions like binary deploy.


## week2
