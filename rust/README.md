# Rust

This directory contains experimental work for programming the STM32F3Discovery
board with the Rust programming language. Follows the discovery
[book](https://docs.rust-embedded.org/discovery/) and the embedded Rust
[book](https://doc.rust-lang.org/stable/embedded-book/).

## Resources

- Heap allocator for Cortex-M: https://github.com/rust-embedded/alloc-cortex-m


```
openocd -f interface/stlink.cfg -f target/stm32f3x.cfg
```
