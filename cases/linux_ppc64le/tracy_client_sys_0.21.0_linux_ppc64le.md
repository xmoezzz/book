# `tracy-client-sys` `0.21.0`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 794907

Build-script executable: `/target/debug/build/tracy-client-sys-29b326db0f36ed92/build_script_build-29b326db0f36ed92`

Working directory: `/tmp/crate-build-ppc64le-zi3qw7dl/src/tracy-client-sys-0.21.0`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/tracy-client-sys-59c5d520ece1f23a/out/libtracy-client.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-zi3qw7dl/src/tracy-client-sys-0.21.0`

### Source directories

* `/tmp/crate-build-ppc64le-zi3qw7dl/src/tracy-client-sys-0.21.0/tracy`

### Source file examples

* `/tmp/crate-build-ppc64le-zi3qw7dl/src/tracy-client-sys-0.21.0/tracy/TracyClient.cpp`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-zi3qw7dl/src/tracy-client-sys-0.21.0`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -std=c++11 -DTRACY_ENABLE -o /target/powerpc64le-unknown-linux-gnu/debug/build/tracy-client-sys-59c5d520ece1f23a/out/b558eb55dea76cee-TracyClient.o -c tracy/TracyClient.cpp
```

### Compilation

```text
cc1plus -quiet -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D TRACY_ENABLE <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -w ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
