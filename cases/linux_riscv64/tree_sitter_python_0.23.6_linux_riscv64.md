# `tree-sitter-python` `0.23.6`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6`

### Source directories

* `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/src`

### Source file examples

* `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/src/parser.c`
* `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/src/scanner.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
