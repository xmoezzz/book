# `tree-sitter` `0.25.10`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 899599

Build-script executable: `/target/debug/build/tree-sitter-8dc1f3946d662536/build_script_build-8dc1f3946d662536`

Working directory: `/tmp/crate-build-riscv64-t93nq76z/src/tree-sitter-0.25.10`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-da428669c74d6a77/out/libtree-sitter.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-t93nq76z/src/tree-sitter-0.25.10`

### Source directories

* `/tmp/crate-build-riscv64-t93nq76z/src/tree-sitter-0.25.10/src`

### Source file examples

* `/tmp/crate-build-riscv64-t93nq76z/src/tree-sitter-0.25.10/src/lib.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D _POSIX_C_SOURCE=200112L -D _DEFAULT_SOURCE -D _DARWIN_C_SOURCE <source> -quiet ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
