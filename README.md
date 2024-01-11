# Simple Rust WASM in NodeJs example

This guide provides instructions on how to integrate Rust with Node.js using WebAssembly (WASM).

## Prerequisites

- Rust toolchain installed (cargo, rustc)
- Node.js and npm installed

## Step 1: Compile to WASM

```shell
cargo install wasm-pack
wasm-pack build --target nodejs
```

## Step 2: Run function in node

```shell
cd nodejs
npm install
node .
```
