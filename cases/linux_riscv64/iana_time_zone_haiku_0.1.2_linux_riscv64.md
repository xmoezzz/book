# `iana-time-zone-haiku` `0.1.2`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 36970

Build-script executable: `/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657`

Working directory: `/tmp/crate-build-riscv64-sb1e4l9t/src/iana-time-zone-haiku-0.1.2`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/iana-time-zone-haiku-bfab047517a46b99/out/libtz_haiku.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-sb1e4l9t/src/iana-time-zone-haiku-0.1.2`

### Source directories

* `/tmp/crate-build-riscv64-sb1e4l9t/src/iana-time-zone-haiku-0.1.2/src`

### Source file examples

* `/tmp/crate-build-riscv64-sb1e4l9t/src/iana-time-zone-haiku-0.1.2/src/implementation.cc`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-sb1e4l9t/src/iana-time-zone-haiku-0.1.2`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -w -std=c++11 -o /target/riscv64gc-unknown-linux-gnu/debug/build/iana-time-zone-haiku-bfab047517a46b99/out/48d3f1b29a630f4c-implementation.o -c src/implementation.cc
```

### Compilation

```text
cc1plus -quiet -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/iana-time-zone-haiku-bfab047517a46b99/out/ -dumpbase <source> -dumpbase-ext .cc -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
