# `tree-sitter-c` `0.23.4`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/libtree-sitter-c.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-off2hhsx/src/tree-sitter-c-0.23.4`

### Source directories

* `/tmp/crate-build-riscv64-off2hhsx/src/tree-sitter-c-0.23.4/src`

### Source file examples

* `/tmp/crate-build-riscv64-off2hhsx/src/tree-sitter-c-0.23.4/src/parser.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-off2hhsx/src/tree-sitter-c-0.23.4`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ea708c7824d36062-parser.o -c src/parser.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
