# `symbolic-demangle` `12.16.3`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 476911

Build-script executable: `/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e`

Working directory: `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3`

### Source directories

* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/src`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling`

### Source file examples

* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/src/swiftdemangle.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Context.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/CrashReporter.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Demangler.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Errors.cpp`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o -c src/swiftdemangle.cpp
```

Working directory: `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o -c vendor/swift/lib/Demangling/CrashReporter.cpp
```

Working directory: `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o -c vendor/swift/lib/Demangling/Demangler.cpp
```

Working directory: `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o -c vendor/swift/lib/Demangling/Errors.cpp
```

Working directory: `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3`

```text
/usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -I vendor/swift/include -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o /target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o -c vendor/swift/lib/Demangling/NodeDumper.cpp
```

### Compilation

```text
cc1plus -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -D SWIFT_STDLIB_HAS_TYPE_PRINTING=1 <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> ...
```

```text
g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -I <include directory> -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 -fpermissive -Wno-changes-meaning -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
