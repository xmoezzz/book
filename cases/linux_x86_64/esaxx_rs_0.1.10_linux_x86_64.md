# `esaxx-rs` `0.1.10`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1877409

Build-script executable: `/work/target/debug/build/esaxx-rs-7ef540a38bbf63c6/build_script_build-7ef540a38bbf63c6`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/esaxx-rs-776e80a67982f782/out/libesaxx.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/esaxx.cpp`

### Source preparation

Working directory: `/work`

```text
/usr/bin/c++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src -Wall -Wextra -std=c++11 -o /work/target/debug/build/esaxx-rs-776e80a67982f782/out/src/esaxx.o -c src/esaxx.cpp
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1plus -quiet -I src -imultiarch x86_64-linux-gnu -D_GNU_SOURCE src/esaxx.cpp -quiet -dumpdir /work/target/debug/build/esaxx-rs-776e80a67982f782/out/src/ -dumpbase esaxx.cpp -dumpbase-ext .cpp -m64 -mtune=generic -march=x86-64 -gdwarf-4 -O0 ...
```

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -std=c++11 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
