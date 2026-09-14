# `brotli-sys` `0.3.2`

Platform: Windows x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 18092

Build-script executable: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/target/debug/build/brotli-sys-5707e6ced7726049/build_script_build-5707e6ced7726049.exe`

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2`

Full linker command: retained in the raw case.

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

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

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/target/debug/build/brotli-sys-2611b5847f11cbf2/out/libbrotli.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/common`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/enc`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/common/dictionary.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec/bit_reader.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec/decode.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec/huffman.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec/state.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -W0 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
