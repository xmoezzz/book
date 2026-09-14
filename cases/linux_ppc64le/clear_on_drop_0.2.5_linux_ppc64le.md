# `clear_on_drop` `0.2.5`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 876624

Build-script executable: `/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058`

Working directory: `/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5`

### Source directories

* `/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5/src`

### Source file examples

* `/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5/src/hide.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o -c src/hide.c
```

### Compilation

```text
cc1 -quiet -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
