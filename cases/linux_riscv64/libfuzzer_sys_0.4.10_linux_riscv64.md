# `libfuzzer-sys` `0.4.10`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/libfuzzer-sys-fc2ea4733557ff0a/out/libfuzzer.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10`

### Source directories

* `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10/libfuzzer`

### Source file examples

* `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerFork.cpp`
* `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerIO.cpp`
* `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerIOPosix.cpp`
* `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerIOWindows.cpp`
* `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerInterceptors.cpp`

### Compilation

```text
cc1plus -quiet -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/libfuzzer-sys-fc2ea4733557ff0a/out/ -dumpbase <source> -dumpbase-ext .cpp -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -gdwarf-4 ...
```

```text
g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
