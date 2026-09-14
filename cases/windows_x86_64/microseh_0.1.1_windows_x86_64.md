# `microseh` `0.1.1`

Platform: Windows x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 472

Build-script executable: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/target/debug/build/microseh-0edf7b18d08647b2/build_script_build-0edf7b18d08647b2.exe`

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1`

Full linker command: retained in the raw case.

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

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

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/target/debug/build/microseh-61421f00da104e5f/out/libcseh.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/src`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-m1kjn116/src/microseh-0.1.1/src/seh.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -W4 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
