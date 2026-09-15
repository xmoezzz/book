# `libusb1-sys` `0.7.0`

Platform: Windows x86_64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned build-level evidence

### Network / source acquisition records

_None._

### pkg-config / pkgconf records

_None._

### Other root-owned linker evidence

### Other root-owned link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "-c",
    "libusb\\libusb/os/events_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "libusb\\libusb/os/events_windows.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "-c",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "-c",
    "libusb\\libusb/os/windows_common.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "libusb\\libusb/os/windows_common.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "-c",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "-c",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "-c",
    "libusb\\libusb/core.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "libusb\\libusb/core.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "-c",
    "libusb\\libusb/descriptor.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "libusb\\libusb/descriptor.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "-c",
    "libusb\\libusb/hotplug.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "libusb\\libusb/hotplug.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "-c",
    "libusb\\libusb/io.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "libusb\\libusb/io.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "-c",
    "libusb\\libusb/strerror.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "libusb\\libusb/strerror.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "-c",
    "libusb\\libusb/sync.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "libusb\\libusb/sync.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000310       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000328       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003f8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000438       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000450       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400d7020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000288       \\177KERNEL32_NULL_THUNK_DATA 00000001400d7288     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002a0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400d72a0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002f0       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400d72f0     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000310       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000310       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400d7310     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000328       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000328       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400d7328     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000338       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400d7338     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000348       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400d7348     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003e0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400d73e0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003f8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003f8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400d73f8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000408       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400d7408     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000438       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000438       \\177ntdll_NULL_THUNK_DATA  00000001400d7438     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000450       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000450       \\177ole32_NULL_THUNK_DATA  00000001400d7450     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-5900-1783962118060109500.map",
  "pid": 5900,
  "ppid": 10144,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-5900-1783962118060109500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/target/debug/build/libusb1-sys-b1615f00d4ba7c03/out/libusb-vendored.a`

Owner: `libusb1-sys` `0.7.0`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/core.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/descriptor.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/hotplug.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/io.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/os/events_windows.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/os/threads_windows.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/os/windows_common.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/os/windows_usbdk.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/os/windows_winusb.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/strerror.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/libusb/libusb/sync.c`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "-c",
    "libusb\\libusb/os/windows_common.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
  "src": "libusb\\libusb/os/windows_common.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "-c",
    "libusb\\libusb/os/events_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
  "src": "libusb\\libusb/os/events_windows.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "-c",
    "libusb\\libusb/io.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
  "src": "libusb\\libusb/io.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "-c",
    "libusb\\libusb/strerror.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
  "src": "libusb\\libusb/strerror.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "-c",
    "libusb\\libusb/sync.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
  "src": "libusb\\libusb/sync.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "-c",
    "libusb\\libusb/descriptor.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
  "src": "libusb\\libusb/descriptor.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "-c",
    "libusb\\libusb/core.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
  "src": "libusb\\libusb/core.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "-c",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
  "src": "libusb\\libusb/os/windows_usbdk.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "-c",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
  "src": "libusb\\libusb/os/windows_winusb.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "-c",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
  "src": "libusb\\libusb/os/threads_windows.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "-c",
    "libusb\\libusb/hotplug.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
  "src": "libusb\\libusb/hotplug.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

### Native link records

_None._

### Resolved link records

_None._

### Resolved native inputs

_None._

## Complete analysis record stream

These are the recovered/enriched/generated records actually supplied to native-flow reconstruction.

### Analysis records

#### Record 1

```json
{
  "event": "native_trace_root_context",
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.54",
      "name": "cc",
      "version": "1.0.54",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
      "name": "libc",
      "version": "0.2.126",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
      "name": "libusb1-sys",
      "version": "0.7.0",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.17",
      "name": "pkg-config",
      "version": "0.3.17",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#vcpkg@0.2.10",
      "name": "vcpkg",
      "version": "0.2.10",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "exit_code": 0,
  "kind": "exec",
  "pid": 8796,
  "ppid": 21276,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:efb0dbf343f76093:07ddf5fd5616b294",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
  "pid": 8796,
  "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:1a69b800e5a1e48c:07ddf5fd5616b294",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
  "pid": 8796,
  "sha256": "c27fc12b1c8efcf70946c16dd29ba446463b55c90dd2751e2493a9bd24c01356",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:d043ec9d75cef817:07ddf5fd5616b294",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
  "pid": 8796,
  "sha256": "01a8a7dd7613c78ab47763d34b99c8c461c7bf981259f0462f3e0b1a011fce60",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:1ceda9c220daf075:07ddf5fd5616b294",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "kernel32.lib",
  "pid": 8796,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:1ceda9c220daf075:07ddf5fd5616b294",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "kernel32.lib",
  "pid": 8796,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:1ceda9c220daf075:07ddf5fd5616b294",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "kernel32.lib",
  "pid": 8796,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:1db9512c4d5c31e6:07ddf5fd5616b294",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "ntdll.lib",
  "pid": 8796,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:861f0814f9c52599:07ddf5fd5616b294",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "userenv.lib",
  "pid": 8796,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:50848825683fdca9:07ddf5fd5616b294",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "ws2_32.lib",
  "pid": 8796,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "used:link:9698ec7fa70b69a4:df7d4e53c08047f7:07ddf5fd5616b294",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "path": "dbghelp.lib",
  "pid": 8796,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib"
  ],
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.126",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 8796,
  "ppid": 21276,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "directories": [
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000200       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000250       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000270       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000288       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000298       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000340       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000358       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140030200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140030250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140030270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140030288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140030298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400302a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140030340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140030358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140030388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-8796-1783962117196119200.map",
  "pid": 8796,
  "ppid": 21276,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-8796-1783962117196119200.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 5900,
  "ppid": 10144,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 5900,
  "ppid": 10144,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000310       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000328       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003f8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000438       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000450       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400d7020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000288       \\177KERNEL32_NULL_THUNK_DATA 00000001400d7288     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002a0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400d72a0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002f0       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400d72f0     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000310       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000310       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400d7310     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000328       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000328       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400d7328     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000338       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400d7338     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000348       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400d7348     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003e0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400d73e0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003f8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003f8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400d73f8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000408       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400d7408     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000438       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000438       \\177ntdll_NULL_THUNK_DATA  00000001400d7438     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000450       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000450       \\177ole32_NULL_THUNK_DATA  00000001400d7450     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-5900-1783962118060109500.map",
  "pid": 5900,
  "ppid": 10144,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-5900-1783962118060109500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "-c",
    "libusb\\libusb/os/events_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 7960,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "-c",
    "libusb\\libusb/os/events_windows.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:de6aee10093e7c9c:89f87f88825ace81",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
  "path": "libusb\\libusb/os/events_windows.c",
  "pid": 7960,
  "sha256": "726bdaeabb280c83681b88848d9a1526f73d3cd5f30b1aaf43dbd303e865148a",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "-c",
    "libusb\\libusb/os/events_windows.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:7b582338bc3feb5a:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
  "pid": 7960,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "-c",
    "libusb\\libusb/os/events_windows.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:de6aee10093e7c9c:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/os/events_windows.c",
  "pid": 7960,
  "sha256": "726bdaeabb280c83681b88848d9a1526f73d3cd5f30b1aaf43dbd303e865148a",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "-c",
    "libusb\\libusb/os/events_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
  "src": "libusb\\libusb/os/events_windows.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "-c",
    "libusb\\libusb/os/events_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "libusb\\libusb/os/events_windows.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "-c",
    "libusb\\libusb/os/events_windows.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 7960,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "-c",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 7220,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "-c",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:b542610f655664dc:0df419cdb9097083",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
  "path": "libusb\\libusb/os/threads_windows.c",
  "pid": 7220,
  "sha256": "33c5124b46509e59393bbc6da0f090325737a9666ae147d0776225c5b29c209b",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "-c",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:d68bc97f19b4a2fa:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
  "pid": 7220,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "-c",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:b542610f655664dc:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/os/threads_windows.c",
  "pid": 7220,
  "sha256": "33c5124b46509e59393bbc6da0f090325737a9666ae147d0776225c5b29c209b",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "-c",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
  "src": "libusb\\libusb/os/threads_windows.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 32

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "-c",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 33

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "-c",
    "libusb\\libusb/os/threads_windows.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 7220,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 34

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "-c",
    "libusb\\libusb/os/windows_common.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 3824,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 35

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "-c",
    "libusb\\libusb/os/windows_common.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:6982ac0adddc9e68:af62424006762a76",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
  "path": "libusb\\libusb/os/windows_common.c",
  "pid": 3824,
  "sha256": "732f5966d1b5eea85ff3d458b7fea7ff66cc2dd6773423183f87e95f3c220cf4",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "-c",
    "libusb\\libusb/os/windows_common.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:5931fde62d634a20:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
  "pid": 3824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 37

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "-c",
    "libusb\\libusb/os/windows_common.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:6982ac0adddc9e68:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/os/windows_common.c",
  "pid": 3824,
  "sha256": "732f5966d1b5eea85ff3d458b7fea7ff66cc2dd6773423183f87e95f3c220cf4",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 38

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "-c",
    "libusb\\libusb/os/windows_common.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
  "src": "libusb\\libusb/os/windows_common.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 39

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "-c",
    "libusb\\libusb/os/windows_common.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "libusb\\libusb/os/windows_common.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 40

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "-c",
    "libusb\\libusb/os/windows_common.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 3824,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 41

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "-c",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 13184,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 42

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "-c",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:2ec4c2282f7cda89:5f5f38fa048512fd",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
  "path": "libusb\\libusb/os/windows_usbdk.c",
  "pid": 13184,
  "sha256": "c7373e402f110d339a60ff53f9bea309101f8b4b0d849d173133a21c0313290f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 43

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "-c",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:8dbcb0a7cf0f0d89:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
  "pid": 13184,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 44

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "-c",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:2ec4c2282f7cda89:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/os/windows_usbdk.c",
  "pid": 13184,
  "sha256": "c7373e402f110d339a60ff53f9bea309101f8b4b0d849d173133a21c0313290f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 45

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "-c",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
  "src": "libusb\\libusb/os/windows_usbdk.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 46

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "-c",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 47

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "-c",
    "libusb\\libusb/os/windows_usbdk.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 13184,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 48

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "-c",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 10368,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 49

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "-c",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:856a5e3c9c670f92:e279c1b906732047",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
  "path": "libusb\\libusb/os/windows_winusb.c",
  "pid": 10368,
  "sha256": "d53505a352bf26932354fb7ff702e18e2fa00633b9a70b7cf2a9afa66db33c57",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 50

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "-c",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:dad8a2b8e4b949c8:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
  "pid": 10368,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 51

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "-c",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:856a5e3c9c670f92:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/os/windows_winusb.c",
  "pid": 10368,
  "sha256": "d53505a352bf26932354fb7ff702e18e2fa00633b9a70b7cf2a9afa66db33c57",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 52

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "-c",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
  "src": "libusb\\libusb/os/windows_winusb.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 53

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "-c",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 54

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "-c",
    "libusb\\libusb/os/windows_winusb.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 10368,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 55

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "-c",
    "libusb\\libusb/core.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 4008,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 56

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "-c",
    "libusb\\libusb/core.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:903179def06d11d6:bb561450468ee43c",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
  "path": "libusb\\libusb/core.c",
  "pid": 4008,
  "sha256": "b37ffd84593b06137201e60d6155d8cc4e3f2ab2b99ab9c4cecbdca848f36b9c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 57

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "-c",
    "libusb\\libusb/core.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:e4a68655ecb1892e:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
  "pid": 4008,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 58

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "-c",
    "libusb\\libusb/core.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:903179def06d11d6:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/core.c",
  "pid": 4008,
  "sha256": "b37ffd84593b06137201e60d6155d8cc4e3f2ab2b99ab9c4cecbdca848f36b9c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 59

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "-c",
    "libusb\\libusb/core.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
  "src": "libusb\\libusb/core.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 60

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "-c",
    "libusb\\libusb/core.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "libusb\\libusb/core.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 61

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "-c",
    "libusb\\libusb/core.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 4008,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 62

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "-c",
    "libusb\\libusb/descriptor.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 19704,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 63

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "-c",
    "libusb\\libusb/descriptor.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:5f9514adb5f619cb:df7f1c108e82fbc5",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
  "path": "libusb\\libusb/descriptor.c",
  "pid": 19704,
  "sha256": "31ac71b59c48fc6403b74f881d0e90bdbf496fe6a53645a950e153609f0532bb",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 64

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "-c",
    "libusb\\libusb/descriptor.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:19de61a836f35a3b:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
  "pid": 19704,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 65

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "-c",
    "libusb\\libusb/descriptor.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:5f9514adb5f619cb:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/descriptor.c",
  "pid": 19704,
  "sha256": "31ac71b59c48fc6403b74f881d0e90bdbf496fe6a53645a950e153609f0532bb",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 66

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "-c",
    "libusb\\libusb/descriptor.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
  "src": "libusb\\libusb/descriptor.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 67

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "-c",
    "libusb\\libusb/descriptor.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "libusb\\libusb/descriptor.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 68

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "-c",
    "libusb\\libusb/descriptor.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 19704,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 69

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "-c",
    "libusb\\libusb/hotplug.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15996,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 70

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "-c",
    "libusb\\libusb/hotplug.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:c3d6d7bb5778e4b3:896b426a73da4b59",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
  "path": "libusb\\libusb/hotplug.c",
  "pid": 15996,
  "sha256": "5b51573b1fdf8d82c71dac0db9947a531082e520304eb71a98d34aa68521b406",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 71

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "-c",
    "libusb\\libusb/hotplug.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:6b0439baa9be873c:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
  "pid": 15996,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 72

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "-c",
    "libusb\\libusb/hotplug.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:c3d6d7bb5778e4b3:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/hotplug.c",
  "pid": 15996,
  "sha256": "5b51573b1fdf8d82c71dac0db9947a531082e520304eb71a98d34aa68521b406",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 73

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "-c",
    "libusb\\libusb/hotplug.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
  "src": "libusb\\libusb/hotplug.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 74

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "-c",
    "libusb\\libusb/hotplug.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "libusb\\libusb/hotplug.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 75

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "-c",
    "libusb\\libusb/hotplug.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 15996,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 76

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "-c",
    "libusb\\libusb/io.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 12204,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 77

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "-c",
    "libusb\\libusb/io.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:cbfba7291eaaa5f5:164c58d699a8c64c",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
  "path": "libusb\\libusb/io.c",
  "pid": 12204,
  "sha256": "2eaa3438b7542b72d036ed6dcaaead018060b660bf2786f2e8da4b14a045c7c2",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 78

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "-c",
    "libusb\\libusb/io.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:9da7fe64d427f9e2:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
  "pid": 12204,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 79

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "-c",
    "libusb\\libusb/io.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:cbfba7291eaaa5f5:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/io.c",
  "pid": 12204,
  "sha256": "2eaa3438b7542b72d036ed6dcaaead018060b660bf2786f2e8da4b14a045c7c2",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 80

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "-c",
    "libusb\\libusb/io.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
  "src": "libusb\\libusb/io.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 81

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "-c",
    "libusb\\libusb/io.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "libusb\\libusb/io.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 82

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "-c",
    "libusb\\libusb/io.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 12204,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 83

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "-c",
    "libusb\\libusb/strerror.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 9640,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 84

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "-c",
    "libusb\\libusb/strerror.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:83f36efef19d2525:0bb707dcef06aabd",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
  "path": "libusb\\libusb/strerror.c",
  "pid": 9640,
  "sha256": "17ee9b6cf5b07b39adce9806339799a5085fde8c5f17ed86af324b856ca7d1ec",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 85

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "-c",
    "libusb\\libusb/strerror.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:7cc23f44e0cc5b4b:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
  "pid": 9640,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 86

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "-c",
    "libusb\\libusb/strerror.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:83f36efef19d2525:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/strerror.c",
  "pid": 9640,
  "sha256": "17ee9b6cf5b07b39adce9806339799a5085fde8c5f17ed86af324b856ca7d1ec",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 87

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "-c",
    "libusb\\libusb/strerror.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
  "src": "libusb\\libusb/strerror.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 88

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "-c",
    "libusb\\libusb/strerror.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "libusb\\libusb/strerror.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 89

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "-c",
    "libusb\\libusb/strerror.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 9640,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 90

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "-c",
    "libusb\\libusb/sync.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 21244,
  "ppid": 17824,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 91

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "-c",
    "libusb\\libusb/sync.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:3a40cc190bbf1bd5:c2d66d7521e1e17d",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
  "path": "libusb\\libusb/sync.c",
  "pid": 21244,
  "sha256": "1aad8b0255e24496e99c050a069c31685fae72ee5c73b7a29ab722193eff0e24",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 92

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "-c",
    "libusb\\libusb/sync.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:42618d33f231e6b9:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
  "pid": 21244,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 93

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "-c",
    "libusb\\libusb/sync.c"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:cl:ed5e0b2a06e6a505:3a40cc190bbf1bd5:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "libusb\\libusb/sync.c",
  "pid": 21244,
  "sha256": "1aad8b0255e24496e99c050a069c31685fae72ee5c73b7a29ab722193eff0e24",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 94

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "-c",
    "libusb\\libusb/sync.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
  "src": "libusb\\libusb/sync.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 95

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "-c",
    "libusb\\libusb/sync.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "libusb\\libusb/sync.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 96

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
    "-I",
    "libusb\\libusb",
    "/source-charset:utf-8",
    "-DPRINTF_FORMAT(a, b)=",
    "-DENABLE_LOGGING=1",
    "-DOS_WINDOWS=1",
    "-DDEFAULT_VISIBILITY=",
    "-DPLATFORM_WINDOWS=1",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
    "-c",
    "libusb\\libusb/sync.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 21244,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 97

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 19020,
  "ppid": 17824,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 98

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:89f87f88825ace81:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
  "pid": 19020,
  "sha256": "e639c7af019fd6ae7b1c105db212b03bc712e61fa32433edf49c0d22736e6794",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 99

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:0df419cdb9097083:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
  "pid": 19020,
  "sha256": "4ef72d01135102de26748df1255a0f4e8242e22eec0e752255b869bca51d6aee",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 100

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:af62424006762a76:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
  "pid": 19020,
  "sha256": "996c9c262f7019255908de6c5627cb3eae33f1bce521c641d7523307ec9c8d92",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 101

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:5f5f38fa048512fd:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
  "pid": 19020,
  "sha256": "813c2949aa7ffda4dee129acab47f8b47d41ab82b189e531cda7b47dbca987fd",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 102

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:e279c1b906732047:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
  "pid": 19020,
  "sha256": "d44965bc7af2a5b312dc578a18c9e08eb65ecb8fea69fcc6e7d68c9083ed1e42",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 103

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:bb561450468ee43c:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
  "pid": 19020,
  "sha256": "df8e98974153a2337446cd4b8f7b0c1e7c6482099520cffe9393adee9c50a606",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 104

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:df7f1c108e82fbc5:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
  "pid": 19020,
  "sha256": "fa3dbf3aa0a01efb42a668b98539c555fd6734004cc31400af872f3da3e2dba9",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 105

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:896b426a73da4b59:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
  "pid": 19020,
  "sha256": "3e4ce964c0ff7ae0ea82d954f2f67f7772834e5205260f90167cc08f7a6b74ce",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 106

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:164c58d699a8c64c:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
  "pid": 19020,
  "sha256": "119058e01d8ec242294ceaabe70b6919e1f9a8434705e0686aeaf05dbe0a2b91",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 107

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:0bb707dcef06aabd:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
  "pid": 19020,
  "sha256": "ceb593231eb04f800b2d959e8b145eefb70b4d18df2aa62601e663d35f2a2bde",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 108

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:c2d66d7521e1e17d:7b04da838a9fadb4",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
  "pid": 19020,
  "sha256": "74f32fbacb7926b0e91e1d1f2161590b409824beada4e355a6b356013bbf69ce",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 109

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:89f87f88825ace81:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
  "pid": 19020,
  "sha256": "e639c7af019fd6ae7b1c105db212b03bc712e61fa32433edf49c0d22736e6794",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 110

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:0df419cdb9097083:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
  "pid": 19020,
  "sha256": "4ef72d01135102de26748df1255a0f4e8242e22eec0e752255b869bca51d6aee",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 111

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:af62424006762a76:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
  "pid": 19020,
  "sha256": "996c9c262f7019255908de6c5627cb3eae33f1bce521c641d7523307ec9c8d92",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 112

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:5f5f38fa048512fd:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
  "pid": 19020,
  "sha256": "813c2949aa7ffda4dee129acab47f8b47d41ab82b189e531cda7b47dbca987fd",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 113

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:e279c1b906732047:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
  "pid": 19020,
  "sha256": "d44965bc7af2a5b312dc578a18c9e08eb65ecb8fea69fcc6e7d68c9083ed1e42",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 114

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:bb561450468ee43c:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
  "pid": 19020,
  "sha256": "df8e98974153a2337446cd4b8f7b0c1e7c6482099520cffe9393adee9c50a606",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 115

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:df7f1c108e82fbc5:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
  "pid": 19020,
  "sha256": "fa3dbf3aa0a01efb42a668b98539c555fd6734004cc31400af872f3da3e2dba9",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 116

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:896b426a73da4b59:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
  "pid": 19020,
  "sha256": "3e4ce964c0ff7ae0ea82d954f2f67f7772834e5205260f90167cc08f7a6b74ce",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 117

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:164c58d699a8c64c:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
  "pid": 19020,
  "sha256": "119058e01d8ec242294ceaabe70b6919e1f9a8434705e0686aeaf05dbe0a2b91",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 118

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:0bb707dcef06aabd:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
  "pid": 19020,
  "sha256": "ceb593231eb04f800b2d959e8b145eefb70b4d18df2aa62601e663d35f2a2bde",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 119

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "used:lib:ed5e0b2a06e6a505:c2d66d7521e1e17d:f09f93220eb3a09e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
  "pid": 19020,
  "sha256": "74f32fbacb7926b0e91e1d1f2161590b409824beada4e355a6b356013bbf69ce",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 120

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 121

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 122

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "cargo_pkg_name": "libusb1-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "pid": 19020,
  "ppid": 17824,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 123

```json
{
  "crate": "libusb1-sys",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "event_id": "bsrun:0fab436ae814bce2:8cde7cfe1cc00938:d97ab15822b128b2",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "0.7.0",
  "_owner": {
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 124

```json
{
  "crate": "libc",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "event_id": "bsrun:b1a64ca4e15bce45:0948d81a04254351:1ab561366dbc5d64",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/target/debug/build/libc-1f9ada9e9bb3e206\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/target/debug/build/libc-1f9ada9e9bb3e206/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
  "success": true,
  "target": null,
  "version": "0.2.126",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cwd_prefix"
  }
}
```

#### Record 125

```json
{
  "event": "process_tracer_diagnostic",
  "platform": "windows_etw",
  "phase": "realtime",
  "argv": [],
  "spawn_error": null,
  "exit_status": null,
  "stdout": "",
  "stderr": "",
  "raw_event_count": 49143,
  "parsed_event_count": 49029,
  "parse_error_count": 0,
  "command_line_event_count": 49029,
  "build_script_root_event_count": 708,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 11024,
  "dropped_event_count": 25415
}
```

#### Record 126

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 5332,
  "ppid": 14560,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T17:01:57.863527+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build-script-build.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 5332,
  "build_script_related": true,
  "build_script_target_dir": "libc-1f9ada9e9bb3e206",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/target/debug/build/libc-1f9ada9e9bb3e206/out"
}
```

#### Record 127

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 3212,
  "ppid": 5332,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T17:01:57.873423+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 5332,
  "build_script_related": true,
  "build_script_target_dir": "libc-1f9ada9e9bb3e206",
  "_owner": {
    "crate": "libc",
    "version": "0.2.126",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/target/debug/build/libc-1f9ada9e9bb3e206/out",
  "_direct_build_script_child": true,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 128

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17824,
  "ppid": 14560,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T17:01:58.556985+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\build-script-build.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 129

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11968,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\tools\\vcpkg\\installed\\x64-windows\\tools\\pkgconf\\pkgconf.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\tools\\vcpkg\\installed\\x64-windows\\tools\\pkgconf\\pkgconf.exe"
  ],
  "comm": "pkgconf.exe",
  "time": "2026-07-13T17:01:58.573063+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\tools\\vcpkg\\installed\\x64-windows\\tools\\pkgconf\\pkgconf.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 130

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7960,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:58.646173+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 131

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12952,
  "ppid": 7960,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:58.656013+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 132

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7220,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:58.908401+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 133

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11320,
  "ppid": 7220,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:58.915455+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 134

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 3824,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:59.103192+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 135

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16956,
  "ppid": 3824,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:59.111779+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 136

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13184,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:59.327738+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 137

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 21468,
  "ppid": 13184,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:59.456092+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 138

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 10368,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:59.684108+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 139

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 20624,
  "ppid": 10368,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:01:59.692661+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 140

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 4008,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:00.116537+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 141

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11852,
  "ppid": 4008,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:00.127380+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 142

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 19704,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:00.362195+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 143

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13908,
  "ppid": 19704,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:00.369520+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 144

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15996,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:00.581590+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 145

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 8280,
  "ppid": 15996,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:00.589924+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 146

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12204,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:00.806791+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 147

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16436,
  "ppid": 12204,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:00.817310+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 148

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 9640,
  "ppid": 17824,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:01.029775+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 149

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 5056,
  "ppid": 9640,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:02:01.036837+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 764,
  "build_script_root_pid": 17824,
  "build_script_related": true,
  "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 150

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 20100,
  "ppid": 13416,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:55.938504+00:00",
  "end_time": "2026-07-13T17:01:56.018373+00:00",
  "start_unix_nanos": 1783962115938503600,
  "end_unix_nanos": 1783962116018373600,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 151

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 6784,
  "ppid": 13416,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-",
    "--crate-name",
    "___",
    "--print=file-names",
    "--crate-type",
    "bin",
    "--crate-type",
    "rlib",
    "--crate-type",
    "dylib",
    "--crate-type",
    "cdylib",
    "--crate-type",
    "staticlib",
    "--crate-type",
    "proc-macro",
    "--print=sysroot",
    "--print=split-debuginfo",
    "--print=crate-name",
    "--print=cfg",
    "-Wwarnings"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name --print=cfg -Wwarnings",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-",
    "--crate-name",
    "___",
    "--print=file-names",
    "--crate-type",
    "bin",
    "--crate-type",
    "rlib",
    "--crate-type",
    "dylib",
    "--crate-type",
    "cdylib",
    "--crate-type",
    "staticlib",
    "--crate-type",
    "proc-macro",
    "--print=sysroot",
    "--print=split-debuginfo",
    "--print=crate-name",
    "--print=cfg",
    "-Wwarnings"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:56.043284+00:00",
  "end_time": "2026-07-13T17:01:56.074185+00:00",
  "start_unix_nanos": 1783962116043284200,
  "end_unix_nanos": 1783962116074185200,
  "crate_name": "___",
  "crate_type": [
    "bin",
    "rlib",
    "dylib",
    "cdylib",
    "staticlib",
    "proc-macro"
  ],
  "out_dir": null
}
```

#### Record 152

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 19772,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:56.827456+00:00",
  "end_time": "2026-07-13T17:01:56.847300+00:00",
  "start_unix_nanos": 1783962116827456200,
  "end_unix_nanos": 1783962116847299700,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 153

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 21452,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-",
    "--crate-name",
    "___",
    "--print=file-names",
    "--crate-type",
    "bin",
    "--crate-type",
    "rlib",
    "--crate-type",
    "dylib",
    "--crate-type",
    "cdylib",
    "--crate-type",
    "staticlib",
    "--crate-type",
    "proc-macro",
    "--print=sysroot",
    "--print=split-debuginfo",
    "--print=crate-name",
    "--print=cfg",
    "-Wwarnings"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name --print=cfg -Wwarnings",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-",
    "--crate-name",
    "___",
    "--print=file-names",
    "--crate-type",
    "bin",
    "--crate-type",
    "rlib",
    "--crate-type",
    "dylib",
    "--crate-type",
    "cdylib",
    "--crate-type",
    "staticlib",
    "--crate-type",
    "proc-macro",
    "--print=sysroot",
    "--print=split-debuginfo",
    "--print=crate-name",
    "--print=cfg",
    "-Wwarnings"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:56.854465+00:00",
  "end_time": "2026-07-13T17:01:56.876969+00:00",
  "start_unix_nanos": 1783962116854464600,
  "end_unix_nanos": 1783962116876969000,
  "crate_name": "___",
  "crate_type": [
    "bin",
    "rlib",
    "dylib",
    "cdylib",
    "staticlib",
    "proc-macro"
  ],
  "out_dir": null
}
```

#### Record 154

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 17764,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:56.919046+00:00",
  "end_time": "2026-07-13T17:01:56.944448+00:00",
  "start_unix_nanos": 1783962116919046100,
  "end_unix_nanos": 1783962116944448200,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 155

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 18244,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=c4237a4646e9f296",
    "-C",
    "extra-filename=-1f9ada9e9bb3e206",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=c4237a4646e9f296 -C extra-filename=-1f9ada9e9bb3e206 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=c4237a4646e9f296",
    "-C",
    "extra-filename=-1f9ada9e9bb3e206",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:56.969340+00:00",
  "end_time": "2026-07-13T17:01:57.749648+00:00",
  "start_unix_nanos": 1783962116969340300,
  "end_unix_nanos": 1783962117749647700,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206"
}
```

#### Record 156

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 13828,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=6cef19bea8c8c1b3",
    "-C",
    "extra-filename=-c4b6998a8a12f14c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=6cef19bea8c8c1b3 -C extra-filename=-c4b6998a8a12f14c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=6cef19bea8c8c1b3",
    "-C",
    "extra-filename=-c4b6998a8a12f14c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:56.972938+00:00",
  "end_time": "2026-07-13T17:01:57.813405+00:00",
  "start_unix_nanos": 1783962116972937500,
  "end_unix_nanos": 1783962117813404500,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
}
```

#### Record 157

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 14568,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "vcpkg",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=56049ea20610ea92",
    "-C",
    "extra-filename=-42c7c414e5e8470f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name vcpkg --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=56049ea20610ea92 -C extra-filename=-42c7c414e5e8470f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "vcpkg",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=56049ea20610ea92",
    "-C",
    "extra-filename=-42c7c414e5e8470f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:56.976290+00:00",
  "end_time": "2026-07-13T17:01:57.441599+00:00",
  "start_unix_nanos": 1783962116976290300,
  "end_unix_nanos": 1783962117441599100,
  "crate_name": "vcpkg",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
}
```

#### Record 158

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 9532,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "pkg_config",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=3609964f1616c877",
    "-C",
    "extra-filename=-7b190a94bd300319",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name pkg_config --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=3609964f1616c877 -C extra-filename=-7b190a94bd300319 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "pkg_config",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=3609964f1616c877",
    "-C",
    "extra-filename=-7b190a94bd300319",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:56.980816+00:00",
  "end_time": "2026-07-13T17:01:57.383563+00:00",
  "start_unix_nanos": 1783962116980815700,
  "end_unix_nanos": 1783962117383563200,
  "crate_name": "pkg_config",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
}
```

#### Record 159

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 17104,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2018",
    "build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"vendored\"))",
    "-C",
    "metadata=70f709d66493fbc9",
    "-C",
    "extra-filename=-f584e82167a0b2d3",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libcc-c4b6998a8a12f14c.rlib",
    "--extern",
    "pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libpkg_config-7b190a94bd300319.rlib",
    "--extern",
    "vcpkg=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libvcpkg-42c7c414e5e8470f.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"vendored\\\"))\" -C metadata=70f709d66493fbc9 -C extra-filename=-f584e82167a0b2d3 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libcc-c4b6998a8a12f14c.rlib --extern pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libpkg_config-7b190a94bd300319.rlib --extern vcpkg=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libvcpkg-42c7c414e5e8470f.rlib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2018",
    "build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"vendored\"))",
    "-C",
    "metadata=70f709d66493fbc9",
    "-C",
    "extra-filename=-f584e82167a0b2d3",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libcc-c4b6998a8a12f14c.rlib",
    "--extern",
    "pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libpkg_config-7b190a94bd300319.rlib",
    "--extern",
    "vcpkg=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libvcpkg-42c7c414e5e8470f.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:57.875500+00:00",
  "end_time": "2026-07-13T17:01:58.360066+00:00",
  "start_unix_nanos": 1783962117875500400,
  "end_unix_nanos": 1783962118360066100,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3"
}
```

#### Record 160

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 9468,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=8a6205f25b850ac2",
    "-C",
    "extra-filename=-ce81a64e340b9860",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--cfg",
    "freebsd11",
    "--cfg",
    "libc_priv_mod_use",
    "--cfg",
    "libc_union",
    "--cfg",
    "libc_const_size_of",
    "--cfg",
    "libc_align",
    "--cfg",
    "libc_int128",
    "--cfg",
    "libc_core_cvoid",
    "--cfg",
    "libc_packedN",
    "--cfg",
    "libc_cfg_target_vendor",
    "--cfg",
    "libc_non_exhaustive",
    "--cfg",
    "libc_ptr_addr_of",
    "--cfg",
    "libc_underscore_const_names"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=8a6205f25b850ac2 -C extra-filename=-ce81a64e340b9860 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow --cfg freebsd11 --cfg libc_priv_mod_use --cfg libc_union --cfg libc_const_size_of --cfg libc_align --cfg libc_int128 --cfg libc_core_cvoid --cfg libc_packedN --cfg libc_cfg_target_vendor --cfg libc_non_exhaustive --cfg libc_ptr_addr_of --cfg libc_underscore_const_names",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=8a6205f25b850ac2",
    "-C",
    "extra-filename=-ce81a64e340b9860",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--cfg",
    "freebsd11",
    "--cfg",
    "libc_priv_mod_use",
    "--cfg",
    "libc_union",
    "--cfg",
    "libc_const_size_of",
    "--cfg",
    "libc_align",
    "--cfg",
    "libc_int128",
    "--cfg",
    "libc_core_cvoid",
    "--cfg",
    "libc_packedN",
    "--cfg",
    "libc_cfg_target_vendor",
    "--cfg",
    "libc_non_exhaustive",
    "--cfg",
    "libc_ptr_addr_of",
    "--cfg",
    "libc_underscore_const_names"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:01:57.906963+00:00",
  "end_time": "2026-07-13T17:01:57.994799+00:00",
  "start_unix_nanos": 1783962117906963300,
  "end_unix_nanos": 1783962117994799000,
  "crate_name": "libc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
}
```

#### Record 161

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libusb1-sys:0.7.0:12960",
  "root_process_pid": 764,
  "pid": 6476,
  "ppid": 14560,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libusb1_sys",
    "--edition=2018",
    "src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"vendored\"))",
    "-C",
    "metadata=7767b520a25ae234",
    "-C",
    "extra-filename=-235cf50c9a38f994",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\liblibc-ce81a64e340b9860.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
    "-l",
    "dylib=user32",
    "-l",
    "static=usb-vendored"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libusb1_sys --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"vendored\\\"))\" -C metadata=7767b520a25ae234 -C extra-filename=-235cf50c9a38f994 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\liblibc-ce81a64e340b9860.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out -l dylib=user32 -l static=usb-vendored",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libusb1_sys",
    "--edition=2018",
    "src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"vendored\"))",
    "-C",
    "metadata=7767b520a25ae234",
    "-C",
    "extra-filename=-235cf50c9a38f994",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\liblibc-ce81a64e340b9860.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
    "-l",
    "dylib=user32",
    "-l",
    "static=usb-vendored"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:02:01.599025+00:00",
  "end_time": "2026-07-13T17:02:01.716457+00:00",
  "start_unix_nanos": 1783962121599025300,
  "end_unix_nanos": 1783962121716456700,
  "crate_name": "libusb1_sys",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T17:02:03.105835+00:00",
  "crate": "libusb1-sys",
  "version": "0.7.0",
  "duration_seconds": 29.44681680004578,
  "trace_record_count": 149,
  "trace_owner_summary": {
    "owner_package_count": 5,
    "owner_packages": [
      {
        "crate": "pkg-config",
        "version": "0.3.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.17",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.17",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.17/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126/Cargo.toml"
      },
      {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/Cargo.toml"
      },
      {
        "crate": "vcpkg",
        "version": "0.2.10",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#vcpkg@0.2.10",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/vcpkg-0.2.10",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/vcpkg-0.2.10/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.0.54",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.54",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.54",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.54/Cargo.toml"
      }
    ],
    "attributed_event_count": 123,
    "unattributed_event_count": 26,
    "owners": [
      {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "event_count": 108,
        "kind_counts": {
          "exec": 13,
          "link": 13,
          "exec_context": 13,
          "resolved_link": 1,
          "used_input": 55,
          "compile": 11,
          "archive": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "libc",
        "version": "0.2.126",
        "event_count": 15,
        "kind_counts": {
          "exec": 1,
          "used_input": 10,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.54",
          "name": "cc",
          "version": "1.0.54",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
          "name": "libc",
          "version": "0.2.126",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
          "name": "libusb1-sys",
          "version": "0.7.0",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.17",
          "name": "pkg-config",
          "version": "0.3.17",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#vcpkg@0.2.10",
          "name": "vcpkg",
          "version": "0.2.10",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "exit_code": 0,
      "kind": "exec",
      "pid": 8796,
      "ppid": 21276,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:efb0dbf343f76093:07ddf5fd5616b294",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
      "pid": 8796,
      "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:1a69b800e5a1e48c:07ddf5fd5616b294",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
      "pid": 8796,
      "sha256": "c27fc12b1c8efcf70946c16dd29ba446463b55c90dd2751e2493a9bd24c01356",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:d043ec9d75cef817:07ddf5fd5616b294",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
      "pid": 8796,
      "sha256": "01a8a7dd7613c78ab47763d34b99c8c461c7bf981259f0462f3e0b1a011fce60",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:1ceda9c220daf075:07ddf5fd5616b294",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "kernel32.lib",
      "pid": 8796,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:1ceda9c220daf075:07ddf5fd5616b294",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "kernel32.lib",
      "pid": 8796,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:1ceda9c220daf075:07ddf5fd5616b294",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "kernel32.lib",
      "pid": 8796,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:1db9512c4d5c31e6:07ddf5fd5616b294",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "ntdll.lib",
      "pid": 8796,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:861f0814f9c52599:07ddf5fd5616b294",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "userenv.lib",
      "pid": 8796,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:50848825683fdca9:07ddf5fd5616b294",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "ws2_32.lib",
      "pid": 8796,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "used:link:9698ec7fa70b69a4:df7d4e53c08047f7:07ddf5fd5616b294",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "path": "dbghelp.lib",
      "pid": 8796,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib"
      ],
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.126",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 8796,
      "ppid": 21276,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\rustcnxk394\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.build_script_build.3db06150e552ba21-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.ah2v7fhgccoht2qrdptyfo122.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build_script_build-1f9ada9e9bb3e206.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "directories": [
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000200       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000250       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000270       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000288       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000298       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000340       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000358       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
          "kind": "library",
          "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
          "kind": "library",
          "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140030200     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000250       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140030250     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140030270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140030288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140030298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400302a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000340       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140030340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140030358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140030388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-8796-1783962117196119200.map",
      "pid": 8796,
      "ppid": 21276,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-8796-1783962117196119200.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 5900,
      "ppid": 10144,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 5900,
      "ppid": 10144,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\rustcAc8wDH\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000310       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000328       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003f8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000438       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000450       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
          "kind": "library",
          "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
          "kind": "library",
          "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400d7020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000288       \\177KERNEL32_NULL_THUNK_DATA 00000001400d7288     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002a0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400d72a0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000002f0       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400d72f0     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000310       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000310       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400d7310     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000328       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000328       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400d7328     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000338       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400d7338     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000348       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400d7348     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003e0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400d73e0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003f8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:000003f8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400d73f8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000408       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400d7408     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000438       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000438       \\177ntdll_NULL_THUNK_DATA  00000001400d7438     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000450       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\0002:00000450       \\177ole32_NULL_THUNK_DATA  00000001400d7450     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-5900-1783962118060109500.map",
      "pid": 5900,
      "ppid": 10144,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-link-link-5900-1783962118060109500.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "-c",
        "libusb\\libusb/os/events_windows.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 7960,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "-c",
        "libusb\\libusb/os/events_windows.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:de6aee10093e7c9c:89f87f88825ace81",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
      "path": "libusb\\libusb/os/events_windows.c",
      "pid": 7960,
      "sha256": "726bdaeabb280c83681b88848d9a1526f73d3cd5f30b1aaf43dbd303e865148a",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "-c",
        "libusb\\libusb/os/events_windows.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:7b582338bc3feb5a:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
      "pid": 7960,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "-c",
        "libusb\\libusb/os/events_windows.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:de6aee10093e7c9c:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/os/events_windows.c",
      "pid": 7960,
      "sha256": "726bdaeabb280c83681b88848d9a1526f73d3cd5f30b1aaf43dbd303e865148a",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "-c",
        "libusb\\libusb/os/events_windows.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
      "src": "libusb\\libusb/os/events_windows.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "-c",
        "libusb\\libusb/os/events_windows.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "libusb\\libusb/os/events_windows.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "-c",
        "libusb\\libusb/os/events_windows.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 7960,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "-c",
        "libusb\\libusb/os/threads_windows.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 7220,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "-c",
        "libusb\\libusb/os/threads_windows.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:b542610f655664dc:0df419cdb9097083",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
      "path": "libusb\\libusb/os/threads_windows.c",
      "pid": 7220,
      "sha256": "33c5124b46509e59393bbc6da0f090325737a9666ae147d0776225c5b29c209b",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "-c",
        "libusb\\libusb/os/threads_windows.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:d68bc97f19b4a2fa:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
      "pid": 7220,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "-c",
        "libusb\\libusb/os/threads_windows.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:b542610f655664dc:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/os/threads_windows.c",
      "pid": 7220,
      "sha256": "33c5124b46509e59393bbc6da0f090325737a9666ae147d0776225c5b29c209b",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "-c",
        "libusb\\libusb/os/threads_windows.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
      "src": "libusb\\libusb/os/threads_windows.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "-c",
        "libusb\\libusb/os/threads_windows.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "libusb\\libusb/os/threads_windows.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "-c",
        "libusb\\libusb/os/threads_windows.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 7220,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "-c",
        "libusb\\libusb/os/windows_common.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 3824,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "-c",
        "libusb\\libusb/os/windows_common.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:6982ac0adddc9e68:af62424006762a76",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
      "path": "libusb\\libusb/os/windows_common.c",
      "pid": 3824,
      "sha256": "732f5966d1b5eea85ff3d458b7fea7ff66cc2dd6773423183f87e95f3c220cf4",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "-c",
        "libusb\\libusb/os/windows_common.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:5931fde62d634a20:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
      "pid": 3824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "-c",
        "libusb\\libusb/os/windows_common.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:6982ac0adddc9e68:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/os/windows_common.c",
      "pid": 3824,
      "sha256": "732f5966d1b5eea85ff3d458b7fea7ff66cc2dd6773423183f87e95f3c220cf4",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "-c",
        "libusb\\libusb/os/windows_common.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
      "src": "libusb\\libusb/os/windows_common.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "-c",
        "libusb\\libusb/os/windows_common.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "libusb\\libusb/os/windows_common.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "-c",
        "libusb\\libusb/os/windows_common.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 3824,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "-c",
        "libusb\\libusb/os/windows_usbdk.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 13184,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "-c",
        "libusb\\libusb/os/windows_usbdk.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:2ec4c2282f7cda89:5f5f38fa048512fd",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
      "path": "libusb\\libusb/os/windows_usbdk.c",
      "pid": 13184,
      "sha256": "c7373e402f110d339a60ff53f9bea309101f8b4b0d849d173133a21c0313290f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "-c",
        "libusb\\libusb/os/windows_usbdk.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:8dbcb0a7cf0f0d89:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
      "pid": 13184,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "-c",
        "libusb\\libusb/os/windows_usbdk.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:2ec4c2282f7cda89:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/os/windows_usbdk.c",
      "pid": 13184,
      "sha256": "c7373e402f110d339a60ff53f9bea309101f8b4b0d849d173133a21c0313290f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "-c",
        "libusb\\libusb/os/windows_usbdk.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
      "src": "libusb\\libusb/os/windows_usbdk.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "-c",
        "libusb\\libusb/os/windows_usbdk.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "libusb\\libusb/os/windows_usbdk.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "-c",
        "libusb\\libusb/os/windows_usbdk.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 13184,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "-c",
        "libusb\\libusb/os/windows_winusb.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 10368,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "-c",
        "libusb\\libusb/os/windows_winusb.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:856a5e3c9c670f92:e279c1b906732047",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
      "path": "libusb\\libusb/os/windows_winusb.c",
      "pid": 10368,
      "sha256": "d53505a352bf26932354fb7ff702e18e2fa00633b9a70b7cf2a9afa66db33c57",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "-c",
        "libusb\\libusb/os/windows_winusb.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:dad8a2b8e4b949c8:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
      "pid": 10368,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "-c",
        "libusb\\libusb/os/windows_winusb.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:856a5e3c9c670f92:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/os/windows_winusb.c",
      "pid": 10368,
      "sha256": "d53505a352bf26932354fb7ff702e18e2fa00633b9a70b7cf2a9afa66db33c57",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "-c",
        "libusb\\libusb/os/windows_winusb.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
      "src": "libusb\\libusb/os/windows_winusb.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "-c",
        "libusb\\libusb/os/windows_winusb.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "libusb\\libusb/os/windows_winusb.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "-c",
        "libusb\\libusb/os/windows_winusb.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 10368,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "-c",
        "libusb\\libusb/core.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 4008,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "-c",
        "libusb\\libusb/core.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:903179def06d11d6:bb561450468ee43c",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
      "path": "libusb\\libusb/core.c",
      "pid": 4008,
      "sha256": "b37ffd84593b06137201e60d6155d8cc4e3f2ab2b99ab9c4cecbdca848f36b9c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "-c",
        "libusb\\libusb/core.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:e4a68655ecb1892e:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
      "pid": 4008,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "-c",
        "libusb\\libusb/core.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:903179def06d11d6:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/core.c",
      "pid": 4008,
      "sha256": "b37ffd84593b06137201e60d6155d8cc4e3f2ab2b99ab9c4cecbdca848f36b9c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "-c",
        "libusb\\libusb/core.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
      "src": "libusb\\libusb/core.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "-c",
        "libusb\\libusb/core.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "libusb\\libusb/core.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "-c",
        "libusb\\libusb/core.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 4008,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "-c",
        "libusb\\libusb/descriptor.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 19704,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "-c",
        "libusb\\libusb/descriptor.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:5f9514adb5f619cb:df7f1c108e82fbc5",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
      "path": "libusb\\libusb/descriptor.c",
      "pid": 19704,
      "sha256": "31ac71b59c48fc6403b74f881d0e90bdbf496fe6a53645a950e153609f0532bb",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "-c",
        "libusb\\libusb/descriptor.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:19de61a836f35a3b:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
      "pid": 19704,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "-c",
        "libusb\\libusb/descriptor.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:5f9514adb5f619cb:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/descriptor.c",
      "pid": 19704,
      "sha256": "31ac71b59c48fc6403b74f881d0e90bdbf496fe6a53645a950e153609f0532bb",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "-c",
        "libusb\\libusb/descriptor.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
      "src": "libusb\\libusb/descriptor.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "-c",
        "libusb\\libusb/descriptor.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "libusb\\libusb/descriptor.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "-c",
        "libusb\\libusb/descriptor.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 19704,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "-c",
        "libusb\\libusb/hotplug.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15996,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "-c",
        "libusb\\libusb/hotplug.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:c3d6d7bb5778e4b3:896b426a73da4b59",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
      "path": "libusb\\libusb/hotplug.c",
      "pid": 15996,
      "sha256": "5b51573b1fdf8d82c71dac0db9947a531082e520304eb71a98d34aa68521b406",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "-c",
        "libusb\\libusb/hotplug.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:6b0439baa9be873c:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
      "pid": 15996,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "-c",
        "libusb\\libusb/hotplug.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:c3d6d7bb5778e4b3:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/hotplug.c",
      "pid": 15996,
      "sha256": "5b51573b1fdf8d82c71dac0db9947a531082e520304eb71a98d34aa68521b406",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "-c",
        "libusb\\libusb/hotplug.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
      "src": "libusb\\libusb/hotplug.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "-c",
        "libusb\\libusb/hotplug.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "libusb\\libusb/hotplug.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "-c",
        "libusb\\libusb/hotplug.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 15996,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "-c",
        "libusb\\libusb/io.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 12204,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "-c",
        "libusb\\libusb/io.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:cbfba7291eaaa5f5:164c58d699a8c64c",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
      "path": "libusb\\libusb/io.c",
      "pid": 12204,
      "sha256": "2eaa3438b7542b72d036ed6dcaaead018060b660bf2786f2e8da4b14a045c7c2",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "-c",
        "libusb\\libusb/io.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:9da7fe64d427f9e2:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
      "pid": 12204,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "-c",
        "libusb\\libusb/io.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:cbfba7291eaaa5f5:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/io.c",
      "pid": 12204,
      "sha256": "2eaa3438b7542b72d036ed6dcaaead018060b660bf2786f2e8da4b14a045c7c2",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "-c",
        "libusb\\libusb/io.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
      "src": "libusb\\libusb/io.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "-c",
        "libusb\\libusb/io.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "libusb\\libusb/io.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "-c",
        "libusb\\libusb/io.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 12204,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "-c",
        "libusb\\libusb/strerror.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 9640,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "-c",
        "libusb\\libusb/strerror.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:83f36efef19d2525:0bb707dcef06aabd",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
      "path": "libusb\\libusb/strerror.c",
      "pid": 9640,
      "sha256": "17ee9b6cf5b07b39adce9806339799a5085fde8c5f17ed86af324b856ca7d1ec",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "-c",
        "libusb\\libusb/strerror.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:7cc23f44e0cc5b4b:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
      "pid": 9640,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "-c",
        "libusb\\libusb/strerror.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:83f36efef19d2525:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/strerror.c",
      "pid": 9640,
      "sha256": "17ee9b6cf5b07b39adce9806339799a5085fde8c5f17ed86af324b856ca7d1ec",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "-c",
        "libusb\\libusb/strerror.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
      "src": "libusb\\libusb/strerror.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "-c",
        "libusb\\libusb/strerror.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "libusb\\libusb/strerror.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "-c",
        "libusb\\libusb/strerror.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 9640,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
        "-c",
        "libusb\\libusb/sync.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 21244,
      "ppid": 17824,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
        "-c",
        "libusb\\libusb/sync.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:3a40cc190bbf1bd5:c2d66d7521e1e17d",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
      "path": "libusb\\libusb/sync.c",
      "pid": 21244,
      "sha256": "1aad8b0255e24496e99c050a069c31685fae72ee5c73b7a29ab722193eff0e24",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
        "-c",
        "libusb\\libusb/sync.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:42618d33f231e6b9:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
      "pid": 21244,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
        "-c",
        "libusb\\libusb/sync.c"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:cl:ed5e0b2a06e6a505:3a40cc190bbf1bd5:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "libusb\\libusb/sync.c",
      "pid": 21244,
      "sha256": "1aad8b0255e24496e99c050a069c31685fae72ee5c73b7a29ab722193eff0e24",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
        "-c",
        "libusb\\libusb/sync.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
      "src": "libusb\\libusb/sync.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
        "-c",
        "libusb\\libusb/sync.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
        "libusb\\libusb/sync.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\include",
        "-I",
        "libusb\\libusb",
        "/source-charset:utf-8",
        "-DPRINTF_FORMAT(a, b)=",
        "-DENABLE_LOGGING=1",
        "-DOS_WINDOWS=1",
        "-DDEFAULT_VISIBILITY=",
        "-DPLATFORM_WINDOWS=1",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
        "-c",
        "libusb\\libusb/sync.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 21244,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 19020,
      "ppid": 17824,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:89f87f88825ace81:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
      "pid": 19020,
      "sha256": "e639c7af019fd6ae7b1c105db212b03bc712e61fa32433edf49c0d22736e6794",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:0df419cdb9097083:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
      "pid": 19020,
      "sha256": "4ef72d01135102de26748df1255a0f4e8242e22eec0e752255b869bca51d6aee",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:af62424006762a76:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
      "pid": 19020,
      "sha256": "996c9c262f7019255908de6c5627cb3eae33f1bce521c641d7523307ec9c8d92",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:5f5f38fa048512fd:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
      "pid": 19020,
      "sha256": "813c2949aa7ffda4dee129acab47f8b47d41ab82b189e531cda7b47dbca987fd",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:e279c1b906732047:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
      "pid": 19020,
      "sha256": "d44965bc7af2a5b312dc578a18c9e08eb65ecb8fea69fcc6e7d68c9083ed1e42",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:bb561450468ee43c:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
      "pid": 19020,
      "sha256": "df8e98974153a2337446cd4b8f7b0c1e7c6482099520cffe9393adee9c50a606",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:df7f1c108e82fbc5:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
      "pid": 19020,
      "sha256": "fa3dbf3aa0a01efb42a668b98539c555fd6734004cc31400af872f3da3e2dba9",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:896b426a73da4b59:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
      "pid": 19020,
      "sha256": "3e4ce964c0ff7ae0ea82d954f2f67f7772834e5205260f90167cc08f7a6b74ce",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:164c58d699a8c64c:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
      "pid": 19020,
      "sha256": "119058e01d8ec242294ceaabe70b6919e1f9a8434705e0686aeaf05dbe0a2b91",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:0bb707dcef06aabd:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
      "pid": 19020,
      "sha256": "ceb593231eb04f800b2d959e8b145eefb70b4d18df2aa62601e663d35f2a2bde",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:c2d66d7521e1e17d:7b04da838a9fadb4",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
      "pid": 19020,
      "sha256": "74f32fbacb7926b0e91e1d1f2161590b409824beada4e355a6b356013bbf69ce",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:89f87f88825ace81:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
      "pid": 19020,
      "sha256": "e639c7af019fd6ae7b1c105db212b03bc712e61fa32433edf49c0d22736e6794",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:0df419cdb9097083:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
      "pid": 19020,
      "sha256": "4ef72d01135102de26748df1255a0f4e8242e22eec0e752255b869bca51d6aee",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:af62424006762a76:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
      "pid": 19020,
      "sha256": "996c9c262f7019255908de6c5627cb3eae33f1bce521c641d7523307ec9c8d92",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:5f5f38fa048512fd:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
      "pid": 19020,
      "sha256": "813c2949aa7ffda4dee129acab47f8b47d41ab82b189e531cda7b47dbca987fd",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:e279c1b906732047:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
      "pid": 19020,
      "sha256": "d44965bc7af2a5b312dc578a18c9e08eb65ecb8fea69fcc6e7d68c9083ed1e42",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:bb561450468ee43c:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
      "pid": 19020,
      "sha256": "df8e98974153a2337446cd4b8f7b0c1e7c6482099520cffe9393adee9c50a606",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:df7f1c108e82fbc5:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
      "pid": 19020,
      "sha256": "fa3dbf3aa0a01efb42a668b98539c555fd6734004cc31400af872f3da3e2dba9",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:896b426a73da4b59:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
      "pid": 19020,
      "sha256": "3e4ce964c0ff7ae0ea82d954f2f67f7772834e5205260f90167cc08f7a6b74ce",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:164c58d699a8c64c:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
      "pid": 19020,
      "sha256": "119058e01d8ec242294ceaabe70b6919e1f9a8434705e0686aeaf05dbe0a2b91",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:0bb707dcef06aabd:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
      "pid": 19020,
      "sha256": "ceb593231eb04f800b2d959e8b145eefb70b4d18df2aa62601e663d35f2a2bde",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "used:lib:ed5e0b2a06e6a505:c2d66d7521e1e17d:f09f93220eb3a09e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o",
      "pid": 19020,
      "sha256": "74f32fbacb7926b0e91e1d1f2161590b409824beada4e355a6b356013bbf69ce",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb-vendored.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/events_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/threads_windows.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_common.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_usbdk.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/os/windows_winusb.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/core.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/descriptor.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/hotplug.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/io.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/strerror.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out\\libusb\\libusb/sync.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "cargo_pkg_name": "libusb1-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "pid": 19020,
      "ppid": 17824,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "libusb1-sys",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "event_id": "bsrun:0fab436ae814bce2:8cde7cfe1cc00938:d97ab15822b128b2",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "0.7.0",
      "_owner": {
        "crate": "libusb1-sys",
        "version": "0.7.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0#libusb1-sys@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "event_id": "bsrun:b1a64ca4e15bce45:0948d81a04254351:1ab561366dbc5d64",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/target/debug/build/libc-1f9ada9e9bb3e206\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tbpizpwk/src/libusb1-sys-0.7.0/target/debug/build/libc-1f9ada9e9bb3e206/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
      "success": true,
      "target": null,
      "version": "0.2.126",
      "_owner": {
        "crate": "libc",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.126",
        "source": "cwd_prefix"
      }
    },
    {
      "event": "process_tracer_diagnostic",
      "platform": "windows_etw",
      "phase": "realtime",
      "argv": [],
      "spawn_error": null,
      "exit_status": null,
      "stdout": "",
      "stderr": "",
      "raw_event_count": 49143,
      "parsed_event_count": 49029,
      "parse_error_count": 0,
      "command_line_event_count": 49029,
      "build_script_root_event_count": 708,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 11024,
      "dropped_event_count": 25415
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 5332,
      "ppid": 14560,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T17:01:57.863527+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206\\build-script-build.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 5332,
      "build_script_related": true,
      "build_script_target_dir": "libc-1f9ada9e9bb3e206"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 3212,
      "ppid": 5332,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T17:01:57.873423+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 5332,
      "build_script_related": true,
      "build_script_target_dir": "libc-1f9ada9e9bb3e206"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17824,
      "ppid": 14560,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T17:01:58.556985+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3\\build-script-build.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11968,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\tools\\vcpkg\\installed\\x64-windows\\tools\\pkgconf\\pkgconf.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\tools\\vcpkg\\installed\\x64-windows\\tools\\pkgconf\\pkgconf.exe"
      ],
      "comm": "pkgconf.exe",
      "time": "2026-07-13T17:01:58.573063+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\tools\\vcpkg\\installed\\x64-windows\\tools\\pkgconf\\pkgconf.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7960,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:58.646173+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12952,
      "ppid": 7960,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:58.656013+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7220,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:58.908401+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11320,
      "ppid": 7220,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:58.915455+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 3824,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:59.103192+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16956,
      "ppid": 3824,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:59.111779+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13184,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:59.327738+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 21468,
      "ppid": 13184,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:59.456092+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 10368,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:59.684108+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 20624,
      "ppid": 10368,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:01:59.692661+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 4008,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:00.116537+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11852,
      "ppid": 4008,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:00.127380+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 19704,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:00.362195+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13908,
      "ppid": 19704,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:00.369520+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15996,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:00.581590+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 8280,
      "ppid": 15996,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:00.589924+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12204,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:00.806791+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16436,
      "ppid": 12204,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:00.817310+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 9640,
      "ppid": 17824,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:01.029775+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\.tmp\\native-trace-4600-1783962115687\\shims\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 5056,
      "ppid": 9640,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:02:01.036837+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 764,
      "build_script_root_pid": 17824,
      "build_script_related": true,
      "build_script_target_dir": "libusb1-sys-f584e82167a0b2d3"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 20100,
      "ppid": 13416,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:55.938504+00:00",
      "end_time": "2026-07-13T17:01:56.018373+00:00",
      "start_unix_nanos": 1783962115938503600,
      "end_unix_nanos": 1783962116018373600,
      "crate_name": null,
      "crate_type": [],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 6784,
      "ppid": 13416,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-",
        "--crate-name",
        "___",
        "--print=file-names",
        "--crate-type",
        "bin",
        "--crate-type",
        "rlib",
        "--crate-type",
        "dylib",
        "--crate-type",
        "cdylib",
        "--crate-type",
        "staticlib",
        "--crate-type",
        "proc-macro",
        "--print=sysroot",
        "--print=split-debuginfo",
        "--print=crate-name",
        "--print=cfg",
        "-Wwarnings"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name --print=cfg -Wwarnings",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-",
        "--crate-name",
        "___",
        "--print=file-names",
        "--crate-type",
        "bin",
        "--crate-type",
        "rlib",
        "--crate-type",
        "dylib",
        "--crate-type",
        "cdylib",
        "--crate-type",
        "staticlib",
        "--crate-type",
        "proc-macro",
        "--print=sysroot",
        "--print=split-debuginfo",
        "--print=crate-name",
        "--print=cfg",
        "-Wwarnings"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:56.043284+00:00",
      "end_time": "2026-07-13T17:01:56.074185+00:00",
      "start_unix_nanos": 1783962116043284200,
      "end_unix_nanos": 1783962116074185200,
      "crate_name": "___",
      "crate_type": [
        "bin",
        "rlib",
        "dylib",
        "cdylib",
        "staticlib",
        "proc-macro"
      ],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 19772,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:56.827456+00:00",
      "end_time": "2026-07-13T17:01:56.847300+00:00",
      "start_unix_nanos": 1783962116827456200,
      "end_unix_nanos": 1783962116847299700,
      "crate_name": null,
      "crate_type": [],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 21452,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-",
        "--crate-name",
        "___",
        "--print=file-names",
        "--crate-type",
        "bin",
        "--crate-type",
        "rlib",
        "--crate-type",
        "dylib",
        "--crate-type",
        "cdylib",
        "--crate-type",
        "staticlib",
        "--crate-type",
        "proc-macro",
        "--print=sysroot",
        "--print=split-debuginfo",
        "--print=crate-name",
        "--print=cfg",
        "-Wwarnings"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name --print=cfg -Wwarnings",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-",
        "--crate-name",
        "___",
        "--print=file-names",
        "--crate-type",
        "bin",
        "--crate-type",
        "rlib",
        "--crate-type",
        "dylib",
        "--crate-type",
        "cdylib",
        "--crate-type",
        "staticlib",
        "--crate-type",
        "proc-macro",
        "--print=sysroot",
        "--print=split-debuginfo",
        "--print=crate-name",
        "--print=cfg",
        "-Wwarnings"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:56.854465+00:00",
      "end_time": "2026-07-13T17:01:56.876969+00:00",
      "start_unix_nanos": 1783962116854464600,
      "end_unix_nanos": 1783962116876969000,
      "crate_name": "___",
      "crate_type": [
        "bin",
        "rlib",
        "dylib",
        "cdylib",
        "staticlib",
        "proc-macro"
      ],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 17764,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:56.919046+00:00",
      "end_time": "2026-07-13T17:01:56.944448+00:00",
      "start_unix_nanos": 1783962116919046100,
      "end_unix_nanos": 1783962116944448200,
      "crate_name": null,
      "crate_type": [],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 18244,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=c4237a4646e9f296",
        "-C",
        "extra-filename=-1f9ada9e9bb3e206",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=c4237a4646e9f296 -C extra-filename=-1f9ada9e9bb3e206 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=c4237a4646e9f296",
        "-C",
        "extra-filename=-1f9ada9e9bb3e206",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:56.969340+00:00",
      "end_time": "2026-07-13T17:01:57.749648+00:00",
      "start_unix_nanos": 1783962116969340300,
      "end_unix_nanos": 1783962117749647700,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libc-1f9ada9e9bb3e206"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 13828,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=6cef19bea8c8c1b3",
        "-C",
        "extra-filename=-c4b6998a8a12f14c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=6cef19bea8c8c1b3 -C extra-filename=-c4b6998a8a12f14c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.54\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=6cef19bea8c8c1b3",
        "-C",
        "extra-filename=-c4b6998a8a12f14c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:56.972938+00:00",
      "end_time": "2026-07-13T17:01:57.813405+00:00",
      "start_unix_nanos": 1783962116972937500,
      "end_unix_nanos": 1783962117813404500,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 14568,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "vcpkg",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=56049ea20610ea92",
        "-C",
        "extra-filename=-42c7c414e5e8470f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name vcpkg --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=56049ea20610ea92 -C extra-filename=-42c7c414e5e8470f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "vcpkg",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\vcpkg-0.2.10\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=56049ea20610ea92",
        "-C",
        "extra-filename=-42c7c414e5e8470f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:56.976290+00:00",
      "end_time": "2026-07-13T17:01:57.441599+00:00",
      "start_unix_nanos": 1783962116976290300,
      "end_unix_nanos": 1783962117441599100,
      "crate_name": "vcpkg",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 9532,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "pkg_config",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=3609964f1616c877",
        "-C",
        "extra-filename=-7b190a94bd300319",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name pkg_config --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=3609964f1616c877 -C extra-filename=-7b190a94bd300319 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "pkg_config",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.17\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=3609964f1616c877",
        "-C",
        "extra-filename=-7b190a94bd300319",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:56.980816+00:00",
      "end_time": "2026-07-13T17:01:57.383563+00:00",
      "start_unix_nanos": 1783962116980815700,
      "end_unix_nanos": 1783962117383563200,
      "crate_name": "pkg_config",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 17104,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2018",
        "build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"vendored\"))",
        "-C",
        "metadata=70f709d66493fbc9",
        "-C",
        "extra-filename=-f584e82167a0b2d3",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libcc-c4b6998a8a12f14c.rlib",
        "--extern",
        "pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libpkg_config-7b190a94bd300319.rlib",
        "--extern",
        "vcpkg=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libvcpkg-42c7c414e5e8470f.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"vendored\\\"))\" -C metadata=70f709d66493fbc9 -C extra-filename=-f584e82167a0b2d3 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libcc-c4b6998a8a12f14c.rlib --extern pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libpkg_config-7b190a94bd300319.rlib --extern vcpkg=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libvcpkg-42c7c414e5e8470f.rlib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2018",
        "build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"vendored\"))",
        "-C",
        "metadata=70f709d66493fbc9",
        "-C",
        "extra-filename=-f584e82167a0b2d3",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libcc-c4b6998a8a12f14c.rlib",
        "--extern",
        "pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libpkg_config-7b190a94bd300319.rlib",
        "--extern",
        "vcpkg=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\libvcpkg-42c7c414e5e8470f.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:57.875500+00:00",
      "end_time": "2026-07-13T17:01:58.360066+00:00",
      "start_unix_nanos": 1783962117875500400,
      "end_unix_nanos": 1783962118360066100,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-f584e82167a0b2d3"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 9468,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=8a6205f25b850ac2",
        "-C",
        "extra-filename=-ce81a64e340b9860",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--cfg",
        "freebsd11",
        "--cfg",
        "libc_priv_mod_use",
        "--cfg",
        "libc_union",
        "--cfg",
        "libc_const_size_of",
        "--cfg",
        "libc_align",
        "--cfg",
        "libc_int128",
        "--cfg",
        "libc_core_cvoid",
        "--cfg",
        "libc_packedN",
        "--cfg",
        "libc_cfg_target_vendor",
        "--cfg",
        "libc_non_exhaustive",
        "--cfg",
        "libc_ptr_addr_of",
        "--cfg",
        "libc_underscore_const_names"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=8a6205f25b850ac2 -C extra-filename=-ce81a64e340b9860 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --cap-lints allow --cfg freebsd11 --cfg libc_priv_mod_use --cfg libc_union --cfg libc_const_size_of --cfg libc_align --cfg libc_int128 --cfg libc_core_cvoid --cfg libc_packedN --cfg libc_cfg_target_vendor --cfg libc_non_exhaustive --cfg libc_ptr_addr_of --cfg libc_underscore_const_names",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.126\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=8a6205f25b850ac2",
        "-C",
        "extra-filename=-ce81a64e340b9860",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--cfg",
        "freebsd11",
        "--cfg",
        "libc_priv_mod_use",
        "--cfg",
        "libc_union",
        "--cfg",
        "libc_const_size_of",
        "--cfg",
        "libc_align",
        "--cfg",
        "libc_int128",
        "--cfg",
        "libc_core_cvoid",
        "--cfg",
        "libc_packedN",
        "--cfg",
        "libc_cfg_target_vendor",
        "--cfg",
        "libc_non_exhaustive",
        "--cfg",
        "libc_ptr_addr_of",
        "--cfg",
        "libc_underscore_const_names"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:01:57.906963+00:00",
      "end_time": "2026-07-13T17:01:57.994799+00:00",
      "start_unix_nanos": 1783962117906963300,
      "end_unix_nanos": 1783962117994799000,
      "crate_name": "libc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libusb1-sys:0.7.0:12960",
      "root_process_pid": 764,
      "pid": 6476,
      "ppid": 14560,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libusb1_sys",
        "--edition=2018",
        "src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"vendored\"))",
        "-C",
        "metadata=7767b520a25ae234",
        "-C",
        "extra-filename=-235cf50c9a38f994",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\liblibc-ce81a64e340b9860.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
        "-l",
        "dylib=user32",
        "-l",
        "static=usb-vendored"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libusb1_sys --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"vendored\\\"))\" -C metadata=7767b520a25ae234 -C extra-filename=-235cf50c9a38f994 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\liblibc-ce81a64e340b9860.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out -l dylib=user32 -l static=usb-vendored",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libusb1_sys",
        "--edition=2018",
        "src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"vendored\"))",
        "-C",
        "metadata=7767b520a25ae234",
        "-C",
        "extra-filename=-235cf50c9a38f994",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps\\liblibc-ce81a64e340b9860.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\build\\libusb1-sys-b1615f00d4ba7c03\\out",
        "-l",
        "dylib=user32",
        "-l",
        "static=usb-vendored"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:02:01.599025+00:00",
      "end_time": "2026-07-13T17:02:01.716457+00:00",
      "start_unix_nanos": 1783962121599025300,
      "end_unix_nanos": 1783962121716456700,
      "crate_name": "libusb1_sys",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tbpizpwk\\src\\libusb1-sys-0.7.0\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 3322,
    "crate": "libusb1-sys",
    "version": "0.7.0",
    "crate_id": "152288",
    "version_id": "1128312",
    "downloads": 3103150,
    "cumulative_downloads": 107965603836,
    "cumulative_share_of_global": 0.40365846825532004,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "build.rs",
    "build_script_exists": true,
    "package_build_field": "build.rs",
    "build_script_reason": "package_build_path",
    "download_source": "local"
  }
}
```
