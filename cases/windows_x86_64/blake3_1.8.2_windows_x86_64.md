# `blake3` `1.8.2`

Platform: Windows x86_64

## Build-level coding evidence

### Other root-owned linker native-library inputs

#### Linker process 9468

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2`

```text
C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-ey86v0ro\src\blake3-1.8.2\.tmp\native-trace-16444-1783954404969\shims\link.exe @C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-ey86v0ro\src\blake3-1.8.2\target\debug\build\blake3-5b031c2601323f61\rustcmbqJpY\linker-arguments
```

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

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

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/target/debug/build/blake3-334cee71006a0189/out/libblake3_sse2_sse41_avx2_assembly.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/c`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/c/blake3_avx2_x86-64_windows_msvc.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/c/blake3_sse2_x86-64_windows_msvc.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/c/blake3_sse41_x86-64_windows_msvc.asm`

### Compilation

```text
ml64 -nologo -Zi <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
