# `tree-sitter-c-sharp` `0.23.1`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1`

### Source directories

* `/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1/src`

### Source file examples

* `/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1/src/parser.c`
* `/tmp/crate-build-riscv64-do_wfrdl/src/tree-sitter-c-sharp-0.23.1/src/scanner.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
