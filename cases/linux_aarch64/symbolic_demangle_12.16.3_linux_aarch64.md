# `symbolic-demangle` `12.16.3`

Platform: Linux aarch64

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

### Compilation

```text
cc1plus -quiet -I <include directory> -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -D SWIFT_STDLIB_HAS_TYPE_PRINTING=1 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 ...
```

```text
g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c++17 -I <include directory> -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
