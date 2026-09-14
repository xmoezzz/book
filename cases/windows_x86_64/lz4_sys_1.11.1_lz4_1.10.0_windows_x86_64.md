# `lz4-sys` `1.11.1+lz4-1.10.0`

Platform: Windows x86_64

## Build-level coding evidence

### Other root-owned linker native-library inputs

#### Linker process 13692

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0`

```text
C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-36qa9ekf\src\lz4-sys-1.11.1+lz4-1.10.0\.tmp\native-trace-18192-1783954391371\shims\link.exe @C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-36qa9ekf\src\lz4-sys-1.11.1+lz4-1.10.0\target\debug\build\lz4-sys-57858e87cc2d10d3\rustcav1MMu\linker-arguments
```

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

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

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/target/debug/build/lz4-sys-8877f31bf4edc40f/out/liblz4.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4frame.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4hc.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/xxhash.c`

### Compilation

```text
cl -nologo -MD -O2 -Z7 -Brepro -W4 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
