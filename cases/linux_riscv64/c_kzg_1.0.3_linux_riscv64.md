# `c-kzg` `1.0.3`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 864718

Build-script executable: `/target/debug/build/c-kzg-ee37d3f050ee354a/build_script_build-ee37d3f050ee354a`

Working directory: `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/c-kzg-5d17959e8d535f25/out/libckzg.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3`

### Source directories

* `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3/src`

### Source file examples

* `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3/src/c_kzg_4844.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3`

```text
/usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3/blst/bindings -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/c-kzg-5d17959e8d535f25/out/98490c8781b409d2-c_kzg_4844.o -c /tmp/crate-build-riscv64-dm319ndk/src/c-kzg-1.0.3/src/c_kzg_4844.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/c-kzg-5d17959e8d535f25/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
