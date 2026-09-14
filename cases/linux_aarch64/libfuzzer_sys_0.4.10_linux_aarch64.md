# `libfuzzer-sys` `0.4.10`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 262736

Build-script executable: `/target/debug/build/libfuzzer-sys-903e12b1e257365f/build_script_build-903e12b1e257365f`

Working directory: `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/libfuzzer-sys-4668ee7688114da5/out/libfuzzer.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10`

### Source directories

* `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10/libfuzzer`

### Source file examples

* `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerFork.cpp`
* `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerIO.cpp`
* `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerIOPosix.cpp`
* `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerIOWindows.cpp`
* `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10/libfuzzer/FuzzerInterceptors.cpp`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -o /target/aarch64-unknown-linux-gnu/debug/build/libfuzzer-sys-4668ee7688114da5/out/e5f0d71fb86e9d6b-FuzzerUtilWindows.o -c libfuzzer/FuzzerUtilWindows.cpp
```

Working directory: `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -o /target/aarch64-unknown-linux-gnu/debug/build/libfuzzer-sys-4668ee7688114da5/out/e5f0d71fb86e9d6b-FuzzerUtilPosix.o -c libfuzzer/FuzzerUtilPosix.cpp
```

Working directory: `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -o /target/aarch64-unknown-linux-gnu/debug/build/libfuzzer-sys-4668ee7688114da5/out/e5f0d71fb86e9d6b-FuzzerUtilFuchsia.o -c libfuzzer/FuzzerUtilFuchsia.cpp
```

Working directory: `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -o /target/aarch64-unknown-linux-gnu/debug/build/libfuzzer-sys-4668ee7688114da5/out/e5f0d71fb86e9d6b-FuzzerUtilDarwin.o -c libfuzzer/FuzzerUtilDarwin.cpp
```

Working directory: `/tmp/crate-build-aarch64-eird13ul/src/libfuzzer-sys-0.4.10`

```text
/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -imultiarch aarch64-linux-gnu -D_GNU_SOURCE libfuzzer/FuzzerUtilLinux.cpp -quiet -dumpbase FuzzerUtilLinux.cpp -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/libfuzzer-sys-4668ee7688114da5/out/e5f0d71fb86e9d6b-FuzzerUtilLinux.o -gdwarf-4 -O0 -std=c++17 -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer ...
```

### Compilation

```text
cc1plus -quiet -imultiarch aarch64-linux-gnu -D_GNU_SOURCE <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 -O0 -std=c++17 -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer ...
```

```text
g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
