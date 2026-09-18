# `tree-sitter-javascript` `0.23.1`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-javascript-8117a8e06d24ff2b/out/libtree-sitter-javascript.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-vual5leg/src/tree-sitter-javascript-0.23.1`

### Source directories

* `/tmp/crate-build-riscv64-vual5leg/src/tree-sitter-javascript-0.23.1/src`

### Source file examples

* `/tmp/crate-build-riscv64-vual5leg/src/tree-sitter-javascript-0.23.1/src/parser.c`
* `/tmp/crate-build-riscv64-vual5leg/src/tree-sitter-javascript-0.23.1/src/scanner.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-javascript-8117a8e06d24ff2b/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
