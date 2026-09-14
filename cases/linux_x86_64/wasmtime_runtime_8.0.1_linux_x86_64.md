# `wasmtime-runtime` `8.0.1`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 2018581

Build-script executable: `/work/target/debug/build/wasmtime-runtime-ce1dad6a91d141a6/build_script_build-ce1dad6a91d141a6`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/wasmtime-runtime-bf2fe768efeaa438/out/libwasmtime-helpers.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/helpers.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_x86_64 -o /work/target/debug/build/wasmtime-runtime-bf2fe768efeaa438/out/ea708c7824d36062-helpers.o -c src/helpers.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -imultiarch x86_64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_x86_64 src/helpers.c -quiet -dumpdir /work/target/debug/build/wasmtime-runtime-bf2fe768efeaa438/out/ -dumpbase ea708c7824d36062-helpers.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_x86_64 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
