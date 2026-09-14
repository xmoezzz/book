# `cxx` `1.0.128`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 2004614

Build-script executable: `/work/target/debug/build/cxx-a94004e58fe92546/build_script_build-a94004e58fe92546`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/cxx-c5ee6af0ce76b4cd/out/libcxxbridge1.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/cxx.cc`

### Source preparation

Working directory: `/work`

```text
/usr/bin/c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++11 -Wall -Wextra -o /work/target/debug/build/cxx-c5ee6af0ce76b4cd/out/c16f17691ff6f04b-cxx.o -c /work/src/cxx.cc
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE /work/src/cxx.cc -quiet -dumpdir /work/target/debug/build/cxx-c5ee6af0ce76b4cd/out/ -dumpbase c16f17691ff6f04b-cxx.cc -dumpbase-ext .cc -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 -Wall ...
```

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++11 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
