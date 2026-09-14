# `ducc-sys` `0.1.2`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 906917

Build-script executable: `/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0`

Working directory: `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/libduktape.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2`

### Source directories

* `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/duktape`

### Source file examples

* `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/duktape/duktape.c`
* `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2/duktape/wrapper.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I duktape -Wall -Wextra -std=c99 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/duktape.o -c duktape/duktape.c
```

Working directory: `/tmp/crate-build-aarch64-gijrqujv/src/ducc-sys-0.1.2`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I duktape -Wall -Wextra -std=c99 -o /target/aarch64-unknown-linux-gnu/debug/build/ducc-sys-699c09f02b71b097/out/duktape/wrapper.o -c duktape/wrapper.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -O0 -Wall -Wextra -std=c99 -ffunction-sections ...
```

### Static library construction

```text
ar crs <static library> <object files>
```
