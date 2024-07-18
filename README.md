# grain-fizz-buzz

```bash
# Compile and Run
grain --no-wasm-tail-call FizzBuzz1.gr

# Run
wasmedge FizzBuzz1.gr.wasm
wasmer FizzBuzz1.gr.wasm
wasmtime FizzBuzz1.gr.wasm

# Compile and Run with tail-call proposal
grain FizzBuzz1.gr

# Run with tail-call proposal
wasmedge --enable-tail-call FizzBuzz1.gr.wasm
wasmtime FizzBuzz1.gr.wasm
```