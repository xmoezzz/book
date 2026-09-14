# `libusb1-sys` `0.7.0`

Platform: Windows x86_64

## Build-level coding evidence

### Other root-owned linker native-library inputs

#### Linker process 5900

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0`

```text
C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-tbpizpwk\src\libusb1-sys-0.7.0\.tmp\native-trace-4600-1783962115687\shims\link.exe @C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-tbpizpwk\src\libusb1-sys-0.7.0\target\debug\build\libusb1-sys-f584e82167a0b2d3\rustcAc8wDH\linker-arguments
```

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

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

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/target/debug/build/libusb1-sys-b1615f00d4ba7c03/out/libusb-vendored.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/os`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/core.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/descriptor.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/hotplug.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/io.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/os/events_windows.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -I <include directory> /source-charset:utf-8 -DPRINTF_FORMAT(a, b)= -DENABLE_LOGGING=1 -DOS_WINDOWS=1 -DDEFAULT_VISIBILITY= -DPLATFORM_WINDOWS=1 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
