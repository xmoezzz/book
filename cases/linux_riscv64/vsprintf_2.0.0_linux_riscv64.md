# `vsprintf` `2.0.0`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 655226

Build-script executable: `/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60`

Working directory: `/tmp/crate-build-riscv64-gfzd8r8w/src/vsprintf-2.0.0`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/vsprintf-f77575bd6455339a/out/libvsprintf.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-gfzd8r8w/src/vsprintf-2.0.0`

### Source directories

* `/tmp/crate-build-riscv64-gfzd8r8w/src/vsprintf-2.0.0/src`

### Source file examples

* `/tmp/crate-build-riscv64-gfzd8r8w/src/vsprintf-2.0.0/src/lib.c`

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/vsprintf-f77575bd6455339a/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
