# Rust Examples

## Env

## Usage

### Basic

Compile and Run a Rust File

``` bash
cd <project directory>

rustc <file-name>

./<binary-name>
```

### Cargo: Build system and package manager

Create package

``` bash
cargo new <project-name>

cd <project-directory>
```

Execution

option 1: Build and Run separately

Build

``` bash
cargo build
```

Run

``` bash
./target/debug/<binary-name>
```

option 2: Build and Run at the same time

``` bash
cargo run
```


## Command Info

`cargo check`: check if the code is ready to build without generating the binary.

## Samples

### 1. hello

``` bash
cd hello

cargo run
```