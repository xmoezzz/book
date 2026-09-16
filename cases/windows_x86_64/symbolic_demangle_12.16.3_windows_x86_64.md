# `symbolic-demangle` `12.16.3`

Platform: Windows x86_64

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-4kxeljci/src/symbolic-demangle-12.16.3/target/debug/build/symbolic-demangle-e5c76c398551c369/out/libswiftdemangle.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-4kxeljci/src/symbolic-demangle-12.16.3`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-4kxeljci/src/symbolic-demangle-12.16.3/src`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-4kxeljci/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-4kxeljci/src/symbolic-demangle-12.16.3/src/swiftdemangle.cpp`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-4kxeljci/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Context.cpp`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-4kxeljci/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/CrashReporter.cpp`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-4kxeljci/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Demangler.cpp`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-4kxeljci/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Errors.cpp`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -std:c++17 -I <include directory> -DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1 -DSWIFT_STDLIB_HAS_TYPE_PRINTING=1 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
