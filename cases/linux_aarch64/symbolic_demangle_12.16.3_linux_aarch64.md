# `symbolic-demangle` `12.16.3`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 474299

Build-script executable: `/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e`

Working directory: `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3`

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

## `/target/aarch64-unknown-linux-gnu/debug/build/symbolic-demangle-7bc69301fc40e82b/out/libswiftdemangle.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3`

### Source directories

* `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3/src`
* `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling`

### Source file examples

* `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3/src/swiftdemangle.cpp`
* `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Context.cpp`
* `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/CrashReporter.cpp`
* `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Demangler.cpp`
* `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Errors.cpp`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/aarch64-unknown-linux-gnu/debug/build/symbolic-demangle-7bc69301fc40e82b/out/0602fb52cb66f316-swiftdemangle.o -c src/swiftdemangle.cpp
```

Working directory: `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3`

```text
/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I vendor/swift/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -D SWIFT_STDLIB_HAS_TYPE_PRINTING=1 vendor/swift/lib/Demangling/Context.cpp -quiet -dumpbase Context.cpp -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/symbolic-demangle-7bc69301fc40e82b/out/9e67921832b6be5b-Context.o -gdwarf-4 ...
```

Working directory: `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/aarch64-unknown-linux-gnu/debug/build/symbolic-demangle-7bc69301fc40e82b/out/9e67921832b6be5b-CrashReporter.o -c vendor/swift/lib/Demangling/CrashReporter.cpp
```

Working directory: `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/aarch64-unknown-linux-gnu/debug/build/symbolic-demangle-7bc69301fc40e82b/out/9e67921832b6be5b-Demangler.o -c vendor/swift/lib/Demangling/Demangler.cpp
```

Working directory: `/tmp/crate-build-aarch64-rmql_qba/src/symbolic-demangle-12.16.3`

```text
/usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/aarch64-unknown-linux-gnu/debug/build/symbolic-demangle-7bc69301fc40e82b/out/9e67921832b6be5b-Errors.o -c vendor/swift/lib/Demangling/Errors.cpp
```

### Compilation

```text
g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -I <include directory> -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o <object> -c <source>
```

```text
cc1plus -quiet -I <include directory> -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -D SWIFT_STDLIB_HAS_TYPE_PRINTING=1 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
