# `tree-sitter-python` `0.23.6`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 901423

Build-script executable: `/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311`

Working directory: `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6`

### Source directories

* `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/src`

### Source file examples

* `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/src/parser.c`
* `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o -c src/parser.c ...
```

Working directory: `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o -c src/scanner.c ...
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
