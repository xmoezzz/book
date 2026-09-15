# `cxx` `1.0.128`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 643097

Build-script executable: `/target/debug/build/cxx-5be0b8067fd31bcb/build_script_build-5be0b8067fd31bcb`

Working directory: `/tmp/crate-build-riscv64-urhjgobl/src/cxx-1.0.128`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/cxx-2d3bb8e380ecdc12/out/libcxxbridge1.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-urhjgobl/src/cxx-1.0.128`

### Source directories

* `/tmp/crate-build-riscv64-urhjgobl/src/cxx-1.0.128/src`

### Source file examples

* `/tmp/crate-build-riscv64-urhjgobl/src/cxx-1.0.128/src/cxx.cc`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-urhjgobl/src/cxx-1.0.128`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++11 -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/cxx-2d3bb8e380ecdc12/out/c16f17691ff6f04b-cxx.o -c /tmp/crate-build-riscv64-urhjgobl/src/cxx-1.0.128/src/cxx.cc
```

### Compilation

```text
cc1plus -quiet -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/cxx-2d3bb8e380ecdc12/out/ -dumpbase <source> -dumpbase-ext .cc -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
