# `blst` `0.3.16`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 698718

Build-script executable: `/target/debug/build/blst-0fe97681e9975598/build_script_build-0fe97681e9975598`

Working directory: `/tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/blst-c4021da583f59d00/out/libblst.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16`

### Source directories

* `/tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16/blst/src`

### Source file examples

* `/tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16/blst/src/server.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -fno-builtin -Wno-unused-function -Wno-unused-command-line-argument -D__BLST_NO_ASM__ -o /target/powerpc64le-unknown-linux-gnu/debug/build/blst-c4021da583f59d00/out/3ce72ea41a6346fd-server.o -c /tmp/crate-build-ppc64le-1q6jbbrz/src/blst-0.3.16/blst/src/server.c
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu -D __BLST_NO_ASM__ <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-function ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
