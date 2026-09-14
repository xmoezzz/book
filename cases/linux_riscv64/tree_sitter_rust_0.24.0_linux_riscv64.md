# `tree-sitter-rust` `0.24.0`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 976383

Build-script executable: `/target/debug/build/tree-sitter-rust-58f6167257b554d7/build_script_build-58f6167257b554d7`

Working directory: `/tmp/crate-build-riscv64-3fzg04eo/src/tree-sitter-rust-0.24.0`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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
