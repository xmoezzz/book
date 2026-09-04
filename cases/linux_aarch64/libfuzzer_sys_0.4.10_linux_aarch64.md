# `libfuzzer-sys` `0.4.10`

Platform: Linux aarch64

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
