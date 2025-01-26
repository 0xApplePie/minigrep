# Rust Grep CLI

A command-line search utility built in Rust that performs case-sensitive text search within files, similar to the Unix `grep` command.

## Features

- Case-sensitive text search
- File content scanning
- Command-line interface
- Simple and fast execution

## Installation

Ensure you have Rust installed on your system. Then clone this repository and build using cargo:

```bash
git clone https://github.com/0xApplePie/minigrep
cd rust-grep-cli
cargo build --release
```

## Usage

```bash
cargo run -- [search_pattern] [file_path]
```

Example:

```bash
cargo run -- "Hello" example.txt
```

## Options

- `search_pattern`: The text pattern you want to search for
- `file_path`: Path to the file you want to search in

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by the Unix `grep` utility
- Built with Rust 🦀
