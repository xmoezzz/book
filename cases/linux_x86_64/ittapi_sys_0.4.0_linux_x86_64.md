# `ittapi-sys` `0.4.0`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1972389

Build-script executable: `/work/target/debug/build/ittapi-sys-6a7c858c557916e3/build_script_build-6a7c858c557916e3`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/libittnotify.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c-library/src/ittnotify`

### Source file examples

* `/work/c-library/src/ittnotify/ittnotify_static.c`
* `/work/c-library/src/ittnotify/jitprofiling.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/48f6f8d8d7ef524e-ittnotify_static.o -c c-library/src/ittnotify/ittnotify_static.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I c-library/src/ittnotify/ -I c-library/include/ -imultiarch x86_64-linux-gnu c-library/src/ittnotify/ittnotify_static.c -quiet -dumpdir /work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/ -dumpbase 48f6f8d8d7ef524e-ittnotify_static.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/48f6f8d8d7ef524e-jitprofiling.o -c c-library/src/ittnotify/jitprofiling.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I c-library/src/ittnotify/ -I c-library/include/ -imultiarch x86_64-linux-gnu c-library/src/ittnotify/jitprofiling.c -quiet -dumpdir /work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/ -dumpbase 48f6f8d8d7ef524e-jitprofiling.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
