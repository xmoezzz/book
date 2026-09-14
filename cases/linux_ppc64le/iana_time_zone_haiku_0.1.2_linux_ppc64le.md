# `iana-time-zone-haiku` `0.1.2`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 36109

Build-script executable: `/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657`

Working directory: `/tmp/crate-build-ppc64le-a4ll3ell/src/iana-time-zone-haiku-0.1.2`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/iana-time-zone-haiku-04c3dd59e771f425/out/libtz_haiku.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-a4ll3ell/src/iana-time-zone-haiku-0.1.2`

### Source directories

* `/tmp/crate-build-ppc64le-a4ll3ell/src/iana-time-zone-haiku-0.1.2/src`

### Source file examples

* `/tmp/crate-build-ppc64le-a4ll3ell/src/iana-time-zone-haiku-0.1.2/src/implementation.cc`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-a4ll3ell/src/iana-time-zone-haiku-0.1.2`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -std=c++11 -o /target/powerpc64le-unknown-linux-gnu/debug/build/iana-time-zone-haiku-04c3dd59e771f425/out/48d3f1b29a630f4c-implementation.o -c src/implementation.cc
```

### Compilation

```text
cc1plus -quiet -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -std=c++11 -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
