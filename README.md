# Pico 2 Template

A Rust project template for Raspberry Pi Pico 2 (RP2350) development.

## Prerequisites

Install [`cargo-generate`](https://crates.io/crates/cargo-generate) if you don't already have it:

```sh
cargo install cargo-generate --locked
```

## Usage

Generate a new project:

```sh
cargo generate --git https://github.com/mattreid1/pico2-template.git
```

## Options

- HAL: Choose between [Embassy](https://embassy.dev/) (async) or [rp-hal](https://github.com/rp-rs/rp-hal)
- defmt logging: Optional debugging support
