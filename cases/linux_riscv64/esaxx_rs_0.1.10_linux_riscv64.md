# `esaxx-rs` `0.1.10`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 1250187

Build-script executable: `/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c`

Working directory: `/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10`

### Source directories

* `/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10/src`

### Source file examples

* `/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10/src/esaxx.cpp`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -mcmodel=medany -I src -Wall -Wextra -std=c++11 -o /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o -c src/esaxx.cpp
```

### Compilation

```text
cc1plus -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/ -dumpbase <source> -dumpbase-ext .cpp -march=rv64gc -mabi=lp64d -mcmodel=medany ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
