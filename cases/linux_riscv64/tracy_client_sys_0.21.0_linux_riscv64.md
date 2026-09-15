# `tracy-client-sys` `0.21.0`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 795056

Build-script executable: `/target/debug/build/tracy-client-sys-29b326db0f36ed92/build_script_build-29b326db0f36ed92`

Working directory: `/tmp/crate-build-riscv64-oyns_pqx/src/tracy-client-sys-0.21.0`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/tracy-client-sys-3dafd510c6c13bff/out/libtracy-client.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-oyns_pqx/src/tracy-client-sys-0.21.0`

### Source directories

* `/tmp/crate-build-riscv64-oyns_pqx/src/tracy-client-sys-0.21.0/tracy`

### Source file examples

* `/tmp/crate-build-riscv64-oyns_pqx/src/tracy-client-sys-0.21.0/tracy/TracyClient.cpp`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-oyns_pqx/src/tracy-client-sys-0.21.0`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -w -std=c++11 -DTRACY_ENABLE -o /target/riscv64gc-unknown-linux-gnu/debug/build/tracy-client-sys-3dafd510c6c13bff/out/b558eb55dea76cee-TracyClient.o -c tracy/TracyClient.cpp
```

### Compilation

```text
cc1plus -quiet -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D TRACY_ENABLE <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tracy-client-sys-3dafd510c6c13bff/out/ -dumpbase <source> -dumpbase-ext .cpp -march=rv64gc -mabi=lp64d -misa-spec=2.2 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
