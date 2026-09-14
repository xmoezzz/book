# `ittapi-sys` `0.4.0`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 536271

Build-script executable: `/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59`

Working directory: `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/ittapi-sys-d8e93a1c07f48bf8/out/libittnotify.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0`

### Source directories

* `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0/c-library/src/ittnotify`

### Source file examples

* `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0/c-library/src/ittnotify/ittnotify_static.c`
* `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0/c-library/src/ittnotify/jitprofiling.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/ittapi-sys-d8e93a1c07f48bf8/out/48f6f8d8d7ef524e-ittnotify_static.o -c c-library/src/ittnotify/ittnotify_static.c ...
```

Working directory: `/tmp/crate-build-riscv64-_fgjntse/src/ittapi-sys-0.4.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/ittapi-sys-d8e93a1c07f48bf8/out/48f6f8d8d7ef524e-jitprofiling.o -c c-library/src/ittnotify/jitprofiling.c ...
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ittapi-sys-d8e93a1c07f48bf8/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
