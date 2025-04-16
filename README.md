# Rust wget

The purpose of this project is to get familiar with Rust by writing a simple variation of the famous utility `wget` in Rust.

## Crates used

* `clap`
* `reqwest`
* `indicatif`
* `colored`

## Usage

* Compile the binary:

```bash
cargo build
```
or
```bash
cargo build --release
```

* Install something, for example:

```bash
./rust-wget https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.2/install.sh
```
