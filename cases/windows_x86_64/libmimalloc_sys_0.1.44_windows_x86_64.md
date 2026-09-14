# `libmimalloc-sys` `0.1.44`

Platform: Windows x86_64

## Build-level coding evidence

### Other root-owned linker native-library inputs

#### Linker process 8580

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44`

```text
C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-f1_wanlw\src\libmimalloc-sys-0.1.44\.tmp\native-trace-17988-1783954823744\shims\link.exe @C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-f1_wanlw\src\libmimalloc-sys-0.1.44\target\debug\build\libmimalloc-sys-524f41214193c3d1\rustco57ypk\linker-arguments
```

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

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

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/target/debug/build/libmimalloc-sys-215aebaae69fb964/out/libmimalloc.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src/static.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -I <include directory> -W4 -DMI_DEBUG=0 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
