# `tree-sitter-c` `0.23.4`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1030097

Build-script executable: `/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc`

Working directory: `/tmp/crate-build-riscv64-off2hhsx/src/tree-sitter-c-0.23.4`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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
