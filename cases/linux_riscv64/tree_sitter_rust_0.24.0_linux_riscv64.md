# `tree-sitter-rust` `0.24.0`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-rust-d951640963b37bac/out/libtree-sitter-rust.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-3fzg04eo/src/tree-sitter-rust-0.24.0`

### Source directories

* `/tmp/crate-build-riscv64-3fzg04eo/src/tree-sitter-rust-0.24.0/src`

### Source file examples

* `/tmp/crate-build-riscv64-3fzg04eo/src/tree-sitter-rust-0.24.0/src/parser.c`
* `/tmp/crate-build-riscv64-3fzg04eo/src/tree-sitter-rust-0.24.0/src/scanner.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-rust-d951640963b37bac/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
