# Rust Raw Pointer Vector Modification Bug

This repository demonstrates a common error when working with raw pointers in Rust and how to prevent it.  The `bug.rs` file contains code that attempts to modify a vector using a raw pointer, leading to undefined behavior.  `bugSolution.rs` offers a safer alternative using standard library functions.