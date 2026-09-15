# `symbolic-demangle` `12.16.3`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 473859

Build-script executable: `/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e`

Working directory: `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/symbolic-demangle-de9a0d8e17a8053e/out/libswiftdemangle.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3`

### Source directories

* `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3/src`
* `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling`

### Source file examples

* `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3/src/swiftdemangle.cpp`
* `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Context.cpp`
* `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/CrashReporter.cpp`
* `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Demangler.cpp`
* `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Errors.cpp`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/riscv64gc-unknown-linux-gnu/debug/build/symbolic-demangle-de9a0d8e17a8053e/out/0602fb52cb66f316-swiftdemangle.o -c src/swiftdemangle.cpp ...
```

Working directory: `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/riscv64gc-unknown-linux-gnu/debug/build/symbolic-demangle-de9a0d8e17a8053e/out/9e67921832b6be5b-Context.o -c vendor/swift/lib/Demangling/Context.cpp ...
```

Working directory: `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/riscv64gc-unknown-linux-gnu/debug/build/symbolic-demangle-de9a0d8e17a8053e/out/9e67921832b6be5b-ManglingUtils.o -c vendor/swift/lib/Demangling/ManglingUtils.cpp ...
```

Working directory: `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/riscv64gc-unknown-linux-gnu/debug/build/symbolic-demangle-de9a0d8e17a8053e/out/9e67921832b6be5b-NodeDumper.o -c vendor/swift/lib/Demangling/NodeDumper.cpp ...
```

Working directory: `/tmp/crate-build-riscv64-02f80ktp/src/symbolic-demangle-12.16.3`

```text
/usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/riscv64gc-unknown-linux-gnu/debug/build/symbolic-demangle-de9a0d8e17a8053e/out/9e67921832b6be5b-NodePrinter.o -c vendor/swift/lib/Demangling/NodePrinter.cpp ...
```

### Compilation

```text
cc1plus -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -D SWIFT_STDLIB_HAS_TYPE_PRINTING=1 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/symbolic-demangle-de9a0d8e17a8053e/out/ -dumpbase <source> -dumpbase-ext ...
```

```text
g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c++17 -I <include directory> -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o <object> -c <source> ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
