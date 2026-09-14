# `esaxx-rs` `0.1.10`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1265086

Build-script executable: `/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c`

Working directory: `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10`

### Source directories

* `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10/src`

### Source file examples

* `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10/src/esaxx.cpp`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src -Wall -Wextra -std=c++11 -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -c src/esaxx.cpp
```

### Compilation

```text
cc1plus -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
