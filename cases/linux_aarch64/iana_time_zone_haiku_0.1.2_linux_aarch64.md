# `iana-time-zone-haiku` `0.1.2`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 35966

Build-script executable: `/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657`

Working directory: `/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2`

### Source directories

* `/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2/src`

### Source file examples

* `/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2/src/implementation.cc`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -w -std=c++11 -o /target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o -c src/implementation.cc
```

### Compilation

```text
cc1plus -quiet -imultiarch aarch64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -std=c++11 -ffunction-sections -fdata-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
