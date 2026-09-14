# `bzip2-sys` `0.1.11+1.0.8`

Platform: Windows x86_64

## Build-level coding evidence

### Other root-owned linker native-library inputs

#### Linker process 17376

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8`

```text
C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-s0gqjxr5\src\bzip2-sys-0.1.11+1.0.8\.tmp\native-trace-14128-1783954232469\shims\link.exe @C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-s0gqjxr5\src\bzip2-sys-0.1.11+1.0.8\target\debug\build\bzip2-sys-ac58be4c0227d725\rustcuMd0Np\linker-arguments
```

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

**Resolved dynamic-library entries**

* `ADVAPI32.dll` (dynamic_library)
* `KERNEL32.dll` (dynamic_library)
* `OLEAUT32.dll` (dynamic_library)
* `VCRUNTIME140.dll` (dynamic_library)
* `api-ms-win-core-synch-l1-2-0.dll` (dynamic_library)
* `api-ms-win-crt-heap-l1-1-0.dll` (dynamic_library)
* `api-ms-win-crt-locale-l1-1-0.dll` (dynamic_library)
* `api-ms-win-crt-math-l1-1-0.dll` (dynamic_library)
* `api-ms-win-crt-runtime-l1-1-0.dll` (dynamic_library)
* `api-ms-win-crt-stdio-l1-1-0.dll` (dynamic_library)
* `bcryptprimitives.dll` (dynamic_library)
* `ntdll.dll` (dynamic_library)
* `ole32.dll` (dynamic_library)

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/target/debug/build/bzip2-sys-a53f7c14e427c16f/out/lib/libbz2.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/blocksort.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/bzlib.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/compress.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/crctable.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/decompress.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -W0 -D_WIN32 -DBZ_EXPORT -D_FILE_OFFSET_BITS=64 -DBZ_NO_STDIO <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
