# `esaxx-rs` `0.1.10`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 283063

Build-script executable: `/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c`

Working directory: `/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10`

### Source directories

* `/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10/src`

### Source file examples

* `/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10/src/esaxx.cpp`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I src -Wall -Wextra -std=c++11 -o /target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o -c src/esaxx.cpp
```

### Compilation

```text
cc1plus -quiet -I <include directory> -imultiarch aarch64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 -O0 -Wall -Wextra -std=c++11 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
