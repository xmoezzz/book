# `ittapi-sys` `0.4.0`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 535954

Build-script executable: `/target/debug/build/ittapi-sys-153a64372a747f59/build_script_build-153a64372a747f59`

Working directory: `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/libittnotify.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0`

### Source directories

* `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/c-library/src/ittnotify`

### Source file examples

* `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/c-library/src/ittnotify/ittnotify_static.c`
* `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0/c-library/src/ittnotify/jitprofiling.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-ittnotify_static.o -c c-library/src/ittnotify/ittnotify_static.c
```

Working directory: `/tmp/crate-build-ppc64le-6bvg6w9y/src/ittapi-sys-0.4.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I c-library/src/ittnotify/ -I c-library/include/ -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/ittapi-sys-a76b361200bb5b33/out/48f6f8d8d7ef524e-jitprofiling.o -c c-library/src/ittnotify/jitprofiling.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
