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

### Source preparation

Working directory: `/tmp/crate-build-riscv64-3fzg04eo/src/tree-sitter-rust-0.24.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-rust-d951640963b37bac/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/tmp/crate-build-riscv64-3fzg04eo/src/tree-sitter-rust-0.24.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-rust-d951640963b37bac/out/ea708c7824d36062-scanner.o -c src/scanner.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-rust-d951640963b37bac/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
