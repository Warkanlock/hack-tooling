# Hack Tooling

This repository contains tools and utilities for the Hack Assembly language, specifically targeting the Nand2Tetris project. The repository is structured into two main tools: `asm2hack` and `vm2asm`.

## Table of Contents

- [asm2hack](#asm2hack)
  - [Description](#description)
  - [Usage](#usage)
  - [Development](#development)
- [vm2asm](#vm2asm)
  - [Description](#description)
  - [Usage](#usage)
  - [Development](#development)
- [License](#license)
- [Contributing](#contributing)

## asm2hack

### Description

The `asm2hack` tool converts Hack Assembly language files into Hack machine language.

### Usage

To use `asm2hack`, navigate to the `asm2hack` directory and run the following command:

```sh
cargo run -- <path-to-your-asm-file>
```

### Development

To develop and test `asm2hack`, navigate to the `asm2hack` directory and use the following commands:

```sh
# Run tests
cargo test

# Build the project
cargo build
```

### Project Structure

- `examples/`: Contains example `.asm` files to be used for testing and demonstration.
- `src/`: Contains the source code for the `asm2hack` tool.
- `target/`: The target directory for compiled files.
- `tests/`: Contains unit tests for the project.
- `Cargo.lock`: Specifies the exact versions of dependencies.
- `Cargo.toml`: Contains the project configuration and dependencies.

## vm2asm

### Description

The `vm2asm` tool converts VM code into Hack Assembly language.

### Usage

To use `vm2asm`, navigate to the `vm2asm` directory and run the following command:

```sh
cargo run -- <path-to-your-vm-file>
```

### Development

To develop and test `vm2asm`, navigate to the `vm2asm` directory and use the following commands:

```sh
# Run tests
cargo test

# Build the project
cargo build
```

### Project Structure

- `examples/`: Contains example `.vm` files to be used for testing and demonstration.
- `src/`: Contains the source code for the `vm2asm` tool.
- `target/`: The target directory for compiled files.
- `tests/`: Contains unit tests for the project.
- `Cargo.lock`: Specifies the exact versions of dependencies.
- `Cargo.toml`: Contains the project configuration and dependencies.
- `default`: Configuration file for default settings.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please see the [CONTRIBUTING](CONTRIBUTING.md) file for more details.
