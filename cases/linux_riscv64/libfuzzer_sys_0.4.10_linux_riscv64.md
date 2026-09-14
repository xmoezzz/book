# `libfuzzer-sys` `0.4.10`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1249607

Build-script executable: `/target/debug/build/libfuzzer-sys-903e12b1e257365f/build_script_build-903e12b1e257365f`

Working directory: `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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

### Source preparation

Working directory: `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -o /target/riscv64gc-unknown-linux-gnu/debug/build/libfuzzer-sys-fc2ea4733557ff0a/out/e5f0d71fb86e9d6b-FuzzerUtilWindows.o -c libfuzzer/FuzzerUtilWindows.cpp
```

Working directory: `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -o /target/riscv64gc-unknown-linux-gnu/debug/build/libfuzzer-sys-fc2ea4733557ff0a/out/e5f0d71fb86e9d6b-FuzzerUtilPosix.o -c libfuzzer/FuzzerUtilPosix.cpp
```

Working directory: `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -o /target/riscv64gc-unknown-linux-gnu/debug/build/libfuzzer-sys-fc2ea4733557ff0a/out/e5f0d71fb86e9d6b-FuzzerUtilLinux.o -c libfuzzer/FuzzerUtilLinux.cpp
```

Working directory: `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -o /target/riscv64gc-unknown-linux-gnu/debug/build/libfuzzer-sys-fc2ea4733557ff0a/out/e5f0d71fb86e9d6b-FuzzerUtilFuchsia.o -c libfuzzer/FuzzerUtilFuchsia.cpp
```

Working directory: `/tmp/crate-build-riscv64-pyvdo53h/src/libfuzzer-sys-0.4.10`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -o /target/riscv64gc-unknown-linux-gnu/debug/build/libfuzzer-sys-fc2ea4733557ff0a/out/e5f0d71fb86e9d6b-FuzzerUtilDarwin.o -c libfuzzer/FuzzerUtilDarwin.cpp
```

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
