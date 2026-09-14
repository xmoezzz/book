# `blst` `0.3.16`

Platform: Windows x86_64

## Build-level coding evidence

### Other root-owned linker native-library inputs

#### Linker process 18504

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16`

```text
C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-0hsojvdd\src\blst-0.3.16\.tmp\native-trace-10996-1783961691514\shims\link.exe @C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-0hsojvdd\src\blst-0.3.16\target\debug\build\blst-dba7bcd6694a6644\rustcPtFOgY\linker-arguments
```

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

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

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/target/debug/build/blst-3627d23ac2a5253f/out/libblst.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/blst/build/win64`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/blst/src`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/blst/build/win64/add_mod_256-x86_64.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/blst/build/win64/add_mod_384-x86_64.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/blst/build/win64/add_mod_384x384-x86_64.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/blst/build/win64/ct_inverse_mod_256-x86_64.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0hsojvdd/src/blst-0.3.16/blst/build/win64/ct_is_square_mod_384-x86_64.asm`

### Compilation

```text
ml64 -nologo -Zi -D__ADX__ <object> -c <source>
```

```text
cl -nologo -MD -Z7 -Brepro -W4 -Zl -D__ADX__ <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
