# `tracy-client-sys` `0.21.0`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 793347

Build-script executable: `/target/debug/build/tracy-client-sys-29b326db0f36ed92/build_script_build-29b326db0f36ed92`

Working directory: `/tmp/crate-build-aarch64-ai9j_81h/src/tracy-client-sys-0.21.0`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/tracy-client-sys-a719c4af516b378d/out/libtracy-client.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-ai9j_81h/src/tracy-client-sys-0.21.0`

### Source directories

* `/tmp/crate-build-aarch64-ai9j_81h/src/tracy-client-sys-0.21.0/tracy`

### Source file examples

* `/tmp/crate-build-aarch64-ai9j_81h/src/tracy-client-sys-0.21.0/tracy/TracyClient.cpp`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-ai9j_81h/src/tracy-client-sys-0.21.0`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -w -std=c++11 -DTRACY_ENABLE -o /target/aarch64-unknown-linux-gnu/debug/build/tracy-client-sys-a719c4af516b378d/out/b558eb55dea76cee-TracyClient.o -c tracy/TracyClient.cpp
```

### Compilation

```text
cc1plus -quiet -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D TRACY_ENABLE <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -std=c++11 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
