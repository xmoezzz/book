# `libssh2-sys` `0.3.0`

Platform: Windows x86_64

## Build-level coding evidence

### Source acquisition

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0`

```text
git submodule update --init
```

### Other root-owned linker native-library inputs

#### Linker process 4564

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0`

```text
C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-9lb_p4lz\src\libssh2-sys-0.3.0\.tmp\native-trace-7492-1783954719242\shims\link.exe @C:\Users\rustbuild\AppData\Local\Temp\crate-build-win-9lb_p4lz\src\libssh2-sys-0.3.0\target\debug\build\libssh2-sys-b19c95373884c7ea\rustc9nAEc5\linker-arguments
```

**Linker library inputs**

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/Kits/10/lib/10.0.22621.0/um/x64/kernel32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/Kits/10/lib/10.0.22621.0/um/x64/advapi32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/Kits/10/lib/10.0.22621.0/um/x64/ole32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/Kits/10/lib/10.0.22621.0/um/x64/oleaut32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/Kits/10/lib/10.0.22621.0/um/x64/ntdll.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/Kits/10/lib/10.0.22621.0/um/x64/userenv.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/Kits/10/lib/10.0.22621.0/um/x64/ws2_32.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/Kits/10/lib/10.0.22621.0/um/x64/dbghelp.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/msvcrt.lib` (library)
* `C:/BuildTools2022/VC/Tools/MSVC/14.44.35207/lib/x64/vcruntime.lib` (library)
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/Kits/10/lib/10.0.22621.0/ucrt/x64/ucrt.lib` (library)

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

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/target/debug/build/libssh2-sys-f82558fc55df8c19/out/build/libssh2.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/agent.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/agent_win.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/bcrypt_pbkdf.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/blowfish.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/channel.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -I <include directory> -I <include directory> -I <include directory> -W0 -DHAVE_LONGLONG -DLIBSSH2_WIN32 -DLIBSSH2_WINCNG -DLIBSSH2_DH_GEX_NEW -DLIBSSH2_HAVE_ZLIB -DLIBSSH2DEBUG <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
