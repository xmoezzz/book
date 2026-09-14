# `lzma-sys` `0.1.20`

Platform: Windows x86_64

## Build-level coding evidence

### Other root-owned linker native-library inputs

#### Linker process 18196

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20`

```text
C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-eiz69gvm\src\lzma-sys-0.1.20\.tmp\native-trace-17784-1783954350186\shims\link.exe @C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-eiz69gvm\src\lzma-sys-0.1.20\target\debug\build\lzma-sys-a81f6d26c241e1a8\rustcDlnOXv\linker-arguments
```

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

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

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/target/debug/build/lzma-sys-c7f013308fc211e8/out/liblzma.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/xz-5.2/src`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/xz-5.2/src/common/tuklib_cpucores.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/xz-5.2/src/common/tuklib_physmem.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/xz-5.2/src/liblzma/check/check.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/xz-5.2/src/liblzma/check/crc32_fast.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-eiz69gvm/src/lzma-sys-0.1.20/xz-5.2/src/liblzma/check/crc32_table.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -W4 -DHAVE_CONFIG_H=1 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
