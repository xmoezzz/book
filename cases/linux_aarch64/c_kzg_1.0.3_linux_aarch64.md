# `c-kzg` `1.0.3`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 864818

Build-script executable: `/target/debug/build/c-kzg-ee37d3f050ee354a/build_script_build-ee37d3f050ee354a`

Working directory: `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/c-kzg-1599ee71ecaeb2bb/out/libckzg.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3`

### Source directories

* `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/src`

### Source file examples

* `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/src/c_kzg_4844.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/blst/bindings -w -o /target/aarch64-unknown-linux-gnu/debug/build/c-kzg-1599ee71ecaeb2bb/out/98490c8781b409d2-c_kzg_4844.o -c /tmp/crate-build-aarch64-itu0kct7/src/c-kzg-1.0.3/src/c_kzg_4844.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
