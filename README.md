# Rust on the mchck

A bare metal example of blink written in rust for the mchck

## Requirements

```bash
rustup run stable cargo install xargo
rustup override set nightly
```

You'll also need `arm-none-eabi-objcopy` in your PATH.

## Compile and upload

```bash
make flash
```
