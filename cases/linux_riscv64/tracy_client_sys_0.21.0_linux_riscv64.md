# `tracy-client-sys` `0.21.0`

Platform: Linux riscv64

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
