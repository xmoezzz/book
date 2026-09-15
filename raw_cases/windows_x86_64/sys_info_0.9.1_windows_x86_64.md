# `sys-info` `0.9.1`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
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
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "-c",
    "c/windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "c/windows.c"
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
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400cf020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400cf298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400cf2b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400cf300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400cf320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400cf338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400cf348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400cf358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400cf3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400cf408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400cf418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400cf448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400cf460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-9956-1783954450556344700.map",
  "pid": 9956,
  "ppid": 17684,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-9956-1783954450556344700.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/target/debug/build/sys-info-c7c214762441b2c0/out/libinfo.a`

Owner: `sys-info` `0.9.1`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/c/windows.c`

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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "-c",
    "c/windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
  "src": "c/windows.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
      "name": "cc",
      "version": "1.2.67",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
      "name": "sys-info",
      "version": "0.9.1",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "exit_code": 0,
  "kind": "exec",
  "pid": 6820,
  "ppid": 14004,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:af894ce939217790:2049612b3656864f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
  "pid": 6820,
  "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:55756007b9a8cd77:2049612b3656864f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
  "pid": 6820,
  "sha256": "bc10b3d4f9e70cd4b21eeaf3a249f7fe3c94bd8e8d2bbf2d42598ed147ce160b",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:9b2b1045105b045a:2049612b3656864f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
  "pid": 6820,
  "sha256": "ec02ee9a055e4ec6617677d1a0b6c039e4659b89eb2952e9bc9eba87ec772979",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:a7aa5c7e51c39095:2049612b3656864f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
  "pid": 6820,
  "sha256": "ff6efff4075e0da6e4767eda3aabf950aaf5c03d0e10e6a5f00c853fbf3b38eb",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:2e8266d845725bb6:2049612b3656864f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
  "pid": 6820,
  "sha256": "a9cb0655191f6f00d39679a0a0eb749cbf6d83f64b3515275338daaf08a919b7",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:e12f066409b37de4:2049612b3656864f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
  "pid": 6820,
  "sha256": "acdad7f98ed1b9cdbe26be386469cca0a840b203efc6807977f688b63ef3ca21",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2049612b3656864f",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "kernel32.lib",
  "pid": 6820,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2049612b3656864f",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "kernel32.lib",
  "pid": 6820,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2049612b3656864f",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "kernel32.lib",
  "pid": 6820,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:1db9512c4d5c31e6:2049612b3656864f",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "ntdll.lib",
  "pid": 6820,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:861f0814f9c52599:2049612b3656864f",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "userenv.lib",
  "pid": 6820,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:50848825683fdca9:2049612b3656864f",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "ws2_32.lib",
  "pid": 6820,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:df7d4e53c08047f7:2049612b3656864f",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "dbghelp.lib",
  "pid": 6820,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o"
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
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 6820,
  "ppid": 14004,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "directories": [
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140039200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140039250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140039270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140039288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140039298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400392a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140039340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140039358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140039388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-6820-1783954449852808500.map",
  "pid": 6820,
  "ppid": 14004,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-6820-1783954449852808500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 9956,
  "ppid": 17684,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 9956,
  "ppid": 17684,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400cf020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400cf298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400cf2b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400cf300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400cf320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400cf338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400cf348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400cf358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400cf3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400cf408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400cf418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400cf448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400cf460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-9956-1783954450556344700.map",
  "pid": 9956,
  "ppid": 17684,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-9956-1783954450556344700.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 12608,
  "ppid": 15744,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
  ],
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "event_id": "used:cl:87ce22965a1a641d:a186423718ab9414:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c",
  "pid": 12608,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
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
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
  "pid": 12608,
  "ppid": 15744,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 3324,
  "ppid": 15744,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
  "pid": 3324,
  "ppid": 15744,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "-c",
    "c/windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17596,
  "ppid": 15744,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "-c",
    "c/windows.c"
  ],
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "event_id": "used:cl:87ce22965a1a641d:cdac4496f0d655db:133ccd614ecc9c4b",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
  "path": "c/windows.c",
  "pid": 17596,
  "sha256": "e39e9c5aadffb812b9356e6cac6f72069aba6d6057b16f9f35ef2a4bcf0a147d",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "-c",
    "c/windows.c"
  ],
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "event_id": "used:cl:87ce22965a1a641d:cb048c08e5d3cd0f:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
  "pid": 17596,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "-c",
    "c/windows.c"
  ],
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "event_id": "used:cl:87ce22965a1a641d:cdac4496f0d655db:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "c/windows.c",
  "pid": 17596,
  "sha256": "e39e9c5aadffb812b9356e6cac6f72069aba6d6057b16f9f35ef2a4bcf0a147d",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "-c",
    "c/windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
  "src": "c/windows.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "-c",
    "c/windows.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "c/windows.c"
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
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
    "-c",
    "c/windows.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
  "pid": 17596,
  "ppid": 15744,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 18236,
  "ppid": 15744,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 37

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "event_id": "used:lib:87ce22965a1a641d:133ccd614ecc9c4b:6d888a0a0f2b4077",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
  "pid": 18236,
  "sha256": "1f06117b0d2343964661a00085510ec1fb2d522b679b05ae34eaaf17042db017",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 38

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "event_id": "used:lib:87ce22965a1a641d:133ccd614ecc9c4b:c8978c168354fb43",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
  "pid": 18236,
  "sha256": "1f06117b0d2343964661a00085510ec1fb2d522b679b05ae34eaaf17042db017",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 39

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 40

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 41

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "cargo_pkg_name": "sys-info",
  "cargo_pkg_version": "0.9.1",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
  "pid": 18236,
  "ppid": 15744,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 42

```json
{
  "crate": "sys-info",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "event_id": "bsrun:2601cd5fd2ab4327:f23b4b4446b9576f:ed0f811f16e5d56a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "0.9.1",
  "_owner": {
    "crate": "sys-info",
    "version": "0.9.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
    "source": "cwd_prefix"
  }
}
```

#### Record 43

```json
{
  "crate": "libc",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "bsrun:a733304fa0307800:75ca51b32ed7320d:e73ed18e0674950c",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/target/debug/build/libc-763fb040b2d663ab\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/target/debug/build/libc-763fb040b2d663ab/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
  "success": true,
  "target": null,
  "version": "0.2.186",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  }
}
```

#### Record 44

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
  "raw_event_count": 13802,
  "parsed_event_count": 13802,
  "parse_error_count": 0,
  "command_line_event_count": 13802,
  "build_script_root_event_count": 286,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 1265,
  "dropped_event_count": 7307
}
```

#### Record 45

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13564,
  "ppid": 13048,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:54:10.034771+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
  "root_cargo_pid": 18096,
  "build_script_root_pid": 13564,
  "build_script_related": true,
  "build_script_target_dir": "libc-763fb040b2d663ab",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/target/debug/build/libc-763fb040b2d663ab/out"
}
```

#### Record 46

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12512,
  "ppid": 13564,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
  ],
  "comm": "rustc-trace-wrapper.exe",
  "time": "2026-07-13T14:54:10.045300+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "root_cargo_pid": 18096,
  "build_script_root_pid": 13564,
  "build_script_related": true,
  "build_script_target_dir": "libc-763fb040b2d663ab",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/target/debug/build/libc-763fb040b2d663ab/out",
  "_direct_build_script_child": true,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 47

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17772,
  "ppid": 12512,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:54:10.053756+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 18096,
  "build_script_root_pid": 13564,
  "build_script_related": true,
  "build_script_target_dir": "libc-763fb040b2d663ab",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/target/debug/build/libc-763fb040b2d663ab/out"
}
```

#### Record 48

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15744,
  "ppid": 13048,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:54:10.875828+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\build-script-build.exe",
  "root_cargo_pid": 18096,
  "build_script_root_pid": 15744,
  "build_script_related": true,
  "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
}
```

#### Record 49

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12608,
  "ppid": 15744,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:54:10.960065+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe",
  "root_cargo_pid": 18096,
  "build_script_root_pid": 15744,
  "build_script_related": true,
  "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
}
```

#### Record 50

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 14180,
  "ppid": 12608,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:54:10.969357+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 18096,
  "build_script_root_pid": 15744,
  "build_script_related": true,
  "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
}
```

#### Record 51

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 3324,
  "ppid": 15744,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:54:11.007290+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe",
  "root_cargo_pid": 18096,
  "build_script_root_pid": 15744,
  "build_script_related": true,
  "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
}
```

#### Record 52

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 9624,
  "ppid": 3324,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:54:11.012693+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 18096,
  "build_script_root_pid": 15744,
  "build_script_related": true,
  "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
}
```

#### Record 53

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 10012,
  "ppid": 17784,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
  "time": "2026-07-13T14:54:09.341322+00:00",
  "end_time": "2026-07-13T14:54:09.358794+00:00",
  "start_unix_nanos": 1783954449341321600,
  "end_unix_nanos": 1783954449358794200,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 54

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 17984,
  "ppid": 17784,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
  "time": "2026-07-13T14:54:09.365075+00:00",
  "end_time": "2026-07-13T14:54:09.384401+00:00",
  "start_unix_nanos": 1783954449365075000,
  "end_unix_nanos": 1783954449384400900,
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

#### Record 55

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 17832,
  "ppid": 17784,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
  "time": "2026-07-13T14:54:09.516021+00:00",
  "end_time": "2026-07-13T14:54:09.537987+00:00",
  "start_unix_nanos": 1783954449516020800,
  "end_unix_nanos": 1783954449537986900,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 56

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 16920,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
  "time": "2026-07-13T14:54:09.579759+00:00",
  "end_time": "2026-07-13T14:54:09.598567+00:00",
  "start_unix_nanos": 1783954449579759400,
  "end_unix_nanos": 1783954449598567100,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 57

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 16160,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
  "time": "2026-07-13T14:54:09.605605+00:00",
  "end_time": "2026-07-13T14:54:09.627373+00:00",
  "start_unix_nanos": 1783954449605605300,
  "end_unix_nanos": 1783954449627372500,
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

#### Record 58

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 17480,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
  "time": "2026-07-13T14:54:09.637497+00:00",
  "end_time": "2026-07-13T14:54:09.656539+00:00",
  "start_unix_nanos": 1783954449637496900,
  "end_unix_nanos": 1783954449656539500,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 59

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 868,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "find_msvc_tools",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=a199b1cb5e329831",
    "-C",
    "extra-filename=-824f9ded730dd358",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "find_msvc_tools",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=a199b1cb5e329831",
    "-C",
    "extra-filename=-824f9ded730dd358",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:09.671650+00:00",
  "end_time": "2026-07-13T14:54:10.005609+00:00",
  "start_unix_nanos": 1783954449671650300,
  "end_unix_nanos": 1783954450005608600,
  "crate_name": "find_msvc_tools",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
}
```

#### Record 60

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 11720,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "shlex",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(manual_codegen_check)",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=181708ecadab3b47",
    "-C",
    "extra-filename=-f9df91f0b2c0ecd4",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "shlex",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(manual_codegen_check)",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=181708ecadab3b47",
    "-C",
    "extra-filename=-f9df91f0b2c0ecd4",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:09.673760+00:00",
  "end_time": "2026-07-13T14:54:09.789804+00:00",
  "start_unix_nanos": 1783954449673759700,
  "end_unix_nanos": 1783954449789803900,
  "crate_name": "shlex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
}
```

#### Record 61

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 17484,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=0add1c4e1ef78d62",
    "-C",
    "extra-filename=-763fb040b2d663ab",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=0add1c4e1ef78d62 -C extra-filename=-763fb040b2d663ab --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=0add1c4e1ef78d62",
    "-C",
    "extra-filename=-763fb040b2d663ab",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:09.676137+00:00",
  "end_time": "2026-07-13T14:54:09.955072+00:00",
  "start_unix_nanos": 1783954449676137200,
  "end_unix_nanos": 1783954449955072200,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab"
}
```

#### Record 62

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 12600,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=98547e1a4afb2a03",
    "-C",
    "extra-filename=-24e0405f325d0f68",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=98547e1a4afb2a03",
    "-C",
    "extra-filename=-24e0405f325d0f68",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:09.860023+00:00",
  "end_time": "2026-07-13T14:54:10.423596+00:00",
  "start_unix_nanos": 1783954449860022500,
  "end_unix_nanos": 1783954450423595600,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
}
```

#### Record 63

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 12512,
  "ppid": 13564,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--version"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --version",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--version"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:10.049366+00:00",
  "end_time": "2026-07-13T14:54:10.065354+00:00",
  "start_unix_nanos": 1783954450049365500,
  "end_unix_nanos": 1783954450065353900,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 64

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 12716,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=de34c0666a4c6d46",
    "-C",
    "extra-filename=-751e763eb72b7eae",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--cfg",
    "freebsd12",
    "--check-cfg",
    "cfg(emscripten_old_stat_abi)",
    "--check-cfg",
    "cfg(espidf_picolibc)",
    "--check-cfg",
    "cfg(espidf_time32)",
    "--check-cfg",
    "cfg(freebsd10)",
    "--check-cfg",
    "cfg(freebsd11)",
    "--check-cfg",
    "cfg(freebsd12)",
    "--check-cfg",
    "cfg(freebsd13)",
    "--check-cfg",
    "cfg(freebsd14)",
    "--check-cfg",
    "cfg(freebsd15)",
    "--check-cfg",
    "cfg(gnu_file_offset_bits64)",
    "--check-cfg",
    "cfg(gnu_time_bits64)",
    "--check-cfg",
    "cfg(libc_deny_warnings)",
    "--check-cfg",
    "cfg(linux_time_bits64)",
    "--check-cfg",
    "cfg(musl_v1_2_3)",
    "--check-cfg",
    "cfg(musl32_time64)",
    "--check-cfg",
    "cfg(musl_redir_time64)",
    "--check-cfg",
    "cfg(vxworks_lt_25_09)",
    "--check-cfg",
    "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\",\"qurt\"))",
    "--check-cfg",
    "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
    "--check-cfg",
    "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=de34c0666a4c6d46 -C extra-filename=-751e763eb72b7eae --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --cap-lints allow --cfg freebsd12 --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_picolibc) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(gnu_time_bits64) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(linux_time_bits64) --check-cfg cfg(musl_v1_2_3) --check-cfg cfg(musl32_time64) --check-cfg cfg(musl_redir_time64) --check-cfg cfg(vxworks_lt_25_09) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\",\\\"qurt\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=de34c0666a4c6d46",
    "-C",
    "extra-filename=-751e763eb72b7eae",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--cfg",
    "freebsd12",
    "--check-cfg",
    "cfg(emscripten_old_stat_abi)",
    "--check-cfg",
    "cfg(espidf_picolibc)",
    "--check-cfg",
    "cfg(espidf_time32)",
    "--check-cfg",
    "cfg(freebsd10)",
    "--check-cfg",
    "cfg(freebsd11)",
    "--check-cfg",
    "cfg(freebsd12)",
    "--check-cfg",
    "cfg(freebsd13)",
    "--check-cfg",
    "cfg(freebsd14)",
    "--check-cfg",
    "cfg(freebsd15)",
    "--check-cfg",
    "cfg(gnu_file_offset_bits64)",
    "--check-cfg",
    "cfg(gnu_time_bits64)",
    "--check-cfg",
    "cfg(libc_deny_warnings)",
    "--check-cfg",
    "cfg(linux_time_bits64)",
    "--check-cfg",
    "cfg(musl_v1_2_3)",
    "--check-cfg",
    "cfg(musl32_time64)",
    "--check-cfg",
    "cfg(musl_redir_time64)",
    "--check-cfg",
    "cfg(vxworks_lt_25_09)",
    "--check-cfg",
    "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\",\"qurt\"))",
    "--check-cfg",
    "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
    "--check-cfg",
    "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:10.075680+00:00",
  "end_time": "2026-07-13T14:54:10.151655+00:00",
  "start_unix_nanos": 1783954450075680400,
  "end_unix_nanos": 1783954450151654800,
  "crate_name": "libc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
}
```

#### Record 65

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 16320,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2015",
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
    "cfg(feature, values())",
    "-C",
    "metadata=8b11ae9d94573e3c",
    "-C",
    "extra-filename=-315e6d59d1fc9b3b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=8b11ae9d94573e3c -C extra-filename=-315e6d59d1fc9b3b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2015",
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
    "cfg(feature, values())",
    "-C",
    "metadata=8b11ae9d94573e3c",
    "-C",
    "extra-filename=-315e6d59d1fc9b3b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:10.437330+00:00",
  "end_time": "2026-07-13T14:54:10.749103+00:00",
  "start_unix_nanos": 1783954450437330300,
  "end_unix_nanos": 1783954450749102500,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b"
}
```

#### Record 66

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sys-info:0.9.1:11576",
  "root_process_pid": 18096,
  "pid": 13552,
  "ppid": 13048,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "sys_info",
    "--edition=2015",
    "lib.rs",
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
    "cfg(feature, values())",
    "-C",
    "metadata=b1a578c002890221",
    "-C",
    "extra-filename=-1ef86475f013b331",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
    "-l",
    "static=info",
    "-l",
    "psapi",
    "-l",
    "powrprof"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name sys_info --edition=2015 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=b1a578c002890221 -C extra-filename=-1ef86475f013b331 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out -l static=info -l psapi -l powrprof",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "sys_info",
    "--edition=2015",
    "lib.rs",
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
    "cfg(feature, values())",
    "-C",
    "metadata=b1a578c002890221",
    "-C",
    "extra-filename=-1ef86475f013b331",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
    "-l",
    "static=info",
    "-l",
    "psapi",
    "-l",
    "powrprof"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:11.345302+00:00",
  "end_time": "2026-07-13T14:54:11.793139+00:00",
  "start_unix_nanos": 1783954451345302100,
  "end_unix_nanos": 1783954451793138400,
  "crate_name": "sys_info",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:54:12.880637+00:00",
  "crate": "sys-info",
  "version": "0.9.1",
  "duration_seconds": 25.724457300035283,
  "trace_record_count": 52,
  "trace_owner_summary": {
    "owner_package_count": 5,
    "owner_packages": [
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml"
      },
      {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/Cargo.toml"
      }
    ],
    "attributed_event_count": 42,
    "unattributed_event_count": 10,
    "owners": [
      {
        "crate": "sys-info",
        "version": "0.9.1",
        "event_count": 24,
        "kind_counts": {
          "exec": 5,
          "link": 4,
          "exec_context": 5,
          "resolved_link": 1,
          "used_input": 6,
          "compile": 1,
          "archive": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "event_count": 18,
        "kind_counts": {
          "exec": 1,
          "used_input": 13,
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
          "name": "cc",
          "version": "1.2.67",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
          "name": "sys-info",
          "version": "0.9.1",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "exit_code": 0,
      "kind": "exec",
      "pid": 6820,
      "ppid": 14004,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:af894ce939217790:2049612b3656864f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
      "pid": 6820,
      "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:55756007b9a8cd77:2049612b3656864f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
      "pid": 6820,
      "sha256": "bc10b3d4f9e70cd4b21eeaf3a249f7fe3c94bd8e8d2bbf2d42598ed147ce160b",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:9b2b1045105b045a:2049612b3656864f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
      "pid": 6820,
      "sha256": "ec02ee9a055e4ec6617677d1a0b6c039e4659b89eb2952e9bc9eba87ec772979",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:a7aa5c7e51c39095:2049612b3656864f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
      "pid": 6820,
      "sha256": "ff6efff4075e0da6e4767eda3aabf950aaf5c03d0e10e6a5f00c853fbf3b38eb",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:2e8266d845725bb6:2049612b3656864f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
      "pid": 6820,
      "sha256": "a9cb0655191f6f00d39679a0a0eb749cbf6d83f64b3515275338daaf08a919b7",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:e12f066409b37de4:2049612b3656864f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
      "pid": 6820,
      "sha256": "acdad7f98ed1b9cdbe26be386469cca0a840b203efc6807977f688b63ef3ca21",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2049612b3656864f",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "kernel32.lib",
      "pid": 6820,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2049612b3656864f",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "kernel32.lib",
      "pid": 6820,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2049612b3656864f",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "kernel32.lib",
      "pid": 6820,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:1db9512c4d5c31e6:2049612b3656864f",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "ntdll.lib",
      "pid": 6820,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:861f0814f9c52599:2049612b3656864f",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "userenv.lib",
      "pid": 6820,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:50848825683fdca9:2049612b3656864f",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "ws2_32.lib",
      "pid": 6820,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:df7d4e53c08047f7:2049612b3656864f",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "dbghelp.lib",
      "pid": 6820,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o"
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
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 6820,
      "ppid": 14004,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\rustceHDwd6\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "directories": [
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140039200     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140039250     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140039270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140039288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140039298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400392a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140039340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140039358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140039388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-6820-1783954449852808500.map",
      "pid": 6820,
      "ppid": 14004,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-6820-1783954449852808500.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 9956,
      "ppid": 17684,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 9956,
      "ppid": 17684,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\rustc3TvFHZ\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000300       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000320       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000003f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000418       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000448       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000460       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400cf020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400cf298     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400cf2b0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000300       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400cf300     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000320       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400cf320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400cf338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400cf348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400cf358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000003f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400cf3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400cf408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000418       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400cf418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000448       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400cf448     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000460       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400cf460     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-9956-1783954450556344700.map",
      "pid": 9956,
      "ppid": 17684,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-link-link-9956-1783954450556344700.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 12608,
      "ppid": 15744,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
      ],
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "event_id": "used:cl:87ce22965a1a641d:a186423718ab9414:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c",
      "pid": 12608,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
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
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\12994434347510482861detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
      "pid": 12608,
      "ppid": 15744,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 3324,
      "ppid": 15744,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
      "pid": 3324,
      "ppid": 15744,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
        "-c",
        "c/windows.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17596,
      "ppid": 15744,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
        "-c",
        "c/windows.c"
      ],
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "event_id": "used:cl:87ce22965a1a641d:cdac4496f0d655db:133ccd614ecc9c4b",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
      "path": "c/windows.c",
      "pid": 17596,
      "sha256": "e39e9c5aadffb812b9356e6cac6f72069aba6d6057b16f9f35ef2a4bcf0a147d",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
        "-c",
        "c/windows.c"
      ],
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "event_id": "used:cl:87ce22965a1a641d:cb048c08e5d3cd0f:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
      "pid": 17596,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
        "-c",
        "c/windows.c"
      ],
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "event_id": "used:cl:87ce22965a1a641d:cdac4496f0d655db:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "c/windows.c",
      "pid": 17596,
      "sha256": "e39e9c5aadffb812b9356e6cac6f72069aba6d6057b16f9f35ef2a4bcf0a147d",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
        "-c",
        "c/windows.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
      "src": "c/windows.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
        "-c",
        "c/windows.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
        "c/windows.c"
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
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
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
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
        "-c",
        "c/windows.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
      "pid": 17596,
      "ppid": 15744,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 18236,
      "ppid": 15744,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
      ],
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "event_id": "used:lib:87ce22965a1a641d:133ccd614ecc9c4b:6d888a0a0f2b4077",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
      "pid": 18236,
      "sha256": "1f06117b0d2343964661a00085510ec1fb2d522b679b05ae34eaaf17042db017",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
      ],
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "event_id": "used:lib:87ce22965a1a641d:133ccd614ecc9c4b:c8978c168354fb43",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o",
      "pid": 18236,
      "sha256": "1f06117b0d2343964661a00085510ec1fb2d522b679b05ae34eaaf17042db017",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\libinfo.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out\\a1edd97dd51cd48d-windows.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "cargo_pkg_name": "sys-info",
      "cargo_pkg_version": "0.9.1",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
      "pid": 18236,
      "ppid": 15744,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "sys-info",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "event_id": "bsrun:2601cd5fd2ab4327:f23b4b4446b9576f:ed0f811f16e5d56a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "0.9.1",
      "_owner": {
        "crate": "sys-info",
        "version": "0.9.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1#sys-info@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "bsrun:a733304fa0307800:75ca51b32ed7320d:e73ed18e0674950c",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/target/debug/build/libc-763fb040b2d663ab\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0_6z9gle/src/sys-info-0.9.1/target/debug/build/libc-763fb040b2d663ab/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "success": true,
      "target": null,
      "version": "0.2.186",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
      "raw_event_count": 13802,
      "parsed_event_count": 13802,
      "parse_error_count": 0,
      "command_line_event_count": 13802,
      "build_script_root_event_count": 286,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 1265,
      "dropped_event_count": 7307
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13564,
      "ppid": 13048,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:54:10.034771+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
      "root_cargo_pid": 18096,
      "build_script_root_pid": 13564,
      "build_script_related": true,
      "build_script_target_dir": "libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12512,
      "ppid": 13564,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
      ],
      "comm": "rustc-trace-wrapper.exe",
      "time": "2026-07-13T14:54:10.045300+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "root_cargo_pid": 18096,
      "build_script_root_pid": 13564,
      "build_script_related": true,
      "build_script_target_dir": "libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17772,
      "ppid": 12512,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:54:10.053756+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 18096,
      "build_script_root_pid": 13564,
      "build_script_related": true,
      "build_script_target_dir": "libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15744,
      "ppid": 13048,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:54:10.875828+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b\\build-script-build.exe",
      "root_cargo_pid": 18096,
      "build_script_root_pid": 15744,
      "build_script_related": true,
      "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12608,
      "ppid": 15744,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:54:10.960065+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe",
      "root_cargo_pid": 18096,
      "build_script_root_pid": 15744,
      "build_script_related": true,
      "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 14180,
      "ppid": 12608,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:54:10.969357+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 18096,
      "build_script_root_pid": 15744,
      "build_script_related": true,
      "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 3324,
      "ppid": 15744,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:54:11.007290+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\.tmp\\native-trace-14356-1783954449161\\shims\\cl.exe",
      "root_cargo_pid": 18096,
      "build_script_root_pid": 15744,
      "build_script_related": true,
      "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 9624,
      "ppid": 3324,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:54:11.012693+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 18096,
      "build_script_root_pid": 15744,
      "build_script_related": true,
      "build_script_target_dir": "sys-info-315e6d59d1fc9b3b"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 10012,
      "ppid": 17784,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
      "time": "2026-07-13T14:54:09.341322+00:00",
      "end_time": "2026-07-13T14:54:09.358794+00:00",
      "start_unix_nanos": 1783954449341321600,
      "end_unix_nanos": 1783954449358794200,
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
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 17984,
      "ppid": 17784,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
      "time": "2026-07-13T14:54:09.365075+00:00",
      "end_time": "2026-07-13T14:54:09.384401+00:00",
      "start_unix_nanos": 1783954449365075000,
      "end_unix_nanos": 1783954449384400900,
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
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 17832,
      "ppid": 17784,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
      "time": "2026-07-13T14:54:09.516021+00:00",
      "end_time": "2026-07-13T14:54:09.537987+00:00",
      "start_unix_nanos": 1783954449516020800,
      "end_unix_nanos": 1783954449537986900,
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
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 16920,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
      "time": "2026-07-13T14:54:09.579759+00:00",
      "end_time": "2026-07-13T14:54:09.598567+00:00",
      "start_unix_nanos": 1783954449579759400,
      "end_unix_nanos": 1783954449598567100,
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
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 16160,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
      "time": "2026-07-13T14:54:09.605605+00:00",
      "end_time": "2026-07-13T14:54:09.627373+00:00",
      "start_unix_nanos": 1783954449605605300,
      "end_unix_nanos": 1783954449627372500,
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
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 17480,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
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
      "time": "2026-07-13T14:54:09.637497+00:00",
      "end_time": "2026-07-13T14:54:09.656539+00:00",
      "start_unix_nanos": 1783954449637496900,
      "end_unix_nanos": 1783954449656539500,
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
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 868,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "find_msvc_tools",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=a199b1cb5e329831",
        "-C",
        "extra-filename=-824f9ded730dd358",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "find_msvc_tools",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=a199b1cb5e329831",
        "-C",
        "extra-filename=-824f9ded730dd358",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:09.671650+00:00",
      "end_time": "2026-07-13T14:54:10.005609+00:00",
      "start_unix_nanos": 1783954449671650300,
      "end_unix_nanos": 1783954450005608600,
      "crate_name": "find_msvc_tools",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 11720,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "shlex",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(manual_codegen_check)",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=181708ecadab3b47",
        "-C",
        "extra-filename=-f9df91f0b2c0ecd4",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "shlex",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(manual_codegen_check)",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=181708ecadab3b47",
        "-C",
        "extra-filename=-f9df91f0b2c0ecd4",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:09.673760+00:00",
      "end_time": "2026-07-13T14:54:09.789804+00:00",
      "start_unix_nanos": 1783954449673759700,
      "end_unix_nanos": 1783954449789803900,
      "crate_name": "shlex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 17484,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=0add1c4e1ef78d62",
        "-C",
        "extra-filename=-763fb040b2d663ab",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=0add1c4e1ef78d62 -C extra-filename=-763fb040b2d663ab --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=0add1c4e1ef78d62",
        "-C",
        "extra-filename=-763fb040b2d663ab",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:09.676137+00:00",
      "end_time": "2026-07-13T14:54:09.955072+00:00",
      "start_unix_nanos": 1783954449676137200,
      "end_unix_nanos": 1783954449955072200,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 12600,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=98547e1a4afb2a03",
        "-C",
        "extra-filename=-24e0405f325d0f68",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=98547e1a4afb2a03",
        "-C",
        "extra-filename=-24e0405f325d0f68",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:09.860023+00:00",
      "end_time": "2026-07-13T14:54:10.423596+00:00",
      "start_unix_nanos": 1783954449860022500,
      "end_unix_nanos": 1783954450423595600,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 12512,
      "ppid": 13564,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--version"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --version",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--version"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:10.049366+00:00",
      "end_time": "2026-07-13T14:54:10.065354+00:00",
      "start_unix_nanos": 1783954450049365500,
      "end_unix_nanos": 1783954450065353900,
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
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 12716,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=de34c0666a4c6d46",
        "-C",
        "extra-filename=-751e763eb72b7eae",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--cfg",
        "freebsd12",
        "--check-cfg",
        "cfg(emscripten_old_stat_abi)",
        "--check-cfg",
        "cfg(espidf_picolibc)",
        "--check-cfg",
        "cfg(espidf_time32)",
        "--check-cfg",
        "cfg(freebsd10)",
        "--check-cfg",
        "cfg(freebsd11)",
        "--check-cfg",
        "cfg(freebsd12)",
        "--check-cfg",
        "cfg(freebsd13)",
        "--check-cfg",
        "cfg(freebsd14)",
        "--check-cfg",
        "cfg(freebsd15)",
        "--check-cfg",
        "cfg(gnu_file_offset_bits64)",
        "--check-cfg",
        "cfg(gnu_time_bits64)",
        "--check-cfg",
        "cfg(libc_deny_warnings)",
        "--check-cfg",
        "cfg(linux_time_bits64)",
        "--check-cfg",
        "cfg(musl_v1_2_3)",
        "--check-cfg",
        "cfg(musl32_time64)",
        "--check-cfg",
        "cfg(musl_redir_time64)",
        "--check-cfg",
        "cfg(vxworks_lt_25_09)",
        "--check-cfg",
        "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\",\"qurt\"))",
        "--check-cfg",
        "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
        "--check-cfg",
        "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=de34c0666a4c6d46 -C extra-filename=-751e763eb72b7eae --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --cap-lints allow --cfg freebsd12 --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_picolibc) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(gnu_time_bits64) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(linux_time_bits64) --check-cfg cfg(musl_v1_2_3) --check-cfg cfg(musl32_time64) --check-cfg cfg(musl_redir_time64) --check-cfg cfg(vxworks_lt_25_09) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\",\\\"qurt\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=de34c0666a4c6d46",
        "-C",
        "extra-filename=-751e763eb72b7eae",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--cfg",
        "freebsd12",
        "--check-cfg",
        "cfg(emscripten_old_stat_abi)",
        "--check-cfg",
        "cfg(espidf_picolibc)",
        "--check-cfg",
        "cfg(espidf_time32)",
        "--check-cfg",
        "cfg(freebsd10)",
        "--check-cfg",
        "cfg(freebsd11)",
        "--check-cfg",
        "cfg(freebsd12)",
        "--check-cfg",
        "cfg(freebsd13)",
        "--check-cfg",
        "cfg(freebsd14)",
        "--check-cfg",
        "cfg(freebsd15)",
        "--check-cfg",
        "cfg(gnu_file_offset_bits64)",
        "--check-cfg",
        "cfg(gnu_time_bits64)",
        "--check-cfg",
        "cfg(libc_deny_warnings)",
        "--check-cfg",
        "cfg(linux_time_bits64)",
        "--check-cfg",
        "cfg(musl_v1_2_3)",
        "--check-cfg",
        "cfg(musl32_time64)",
        "--check-cfg",
        "cfg(musl_redir_time64)",
        "--check-cfg",
        "cfg(vxworks_lt_25_09)",
        "--check-cfg",
        "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\",\"qurt\"))",
        "--check-cfg",
        "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
        "--check-cfg",
        "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:10.075680+00:00",
      "end_time": "2026-07-13T14:54:10.151655+00:00",
      "start_unix_nanos": 1783954450075680400,
      "end_unix_nanos": 1783954450151654800,
      "crate_name": "libc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 16320,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2015",
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
        "cfg(feature, values())",
        "-C",
        "metadata=8b11ae9d94573e3c",
        "-C",
        "extra-filename=-315e6d59d1fc9b3b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=8b11ae9d94573e3c -C extra-filename=-315e6d59d1fc9b3b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2015",
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
        "cfg(feature, values())",
        "-C",
        "metadata=8b11ae9d94573e3c",
        "-C",
        "extra-filename=-315e6d59d1fc9b3b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:10.437330+00:00",
      "end_time": "2026-07-13T14:54:10.749103+00:00",
      "start_unix_nanos": 1783954450437330300,
      "end_unix_nanos": 1783954450749102500,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-315e6d59d1fc9b3b"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sys-info:0.9.1:11576",
      "root_process_pid": 18096,
      "pid": 13552,
      "ppid": 13048,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "sys_info",
        "--edition=2015",
        "lib.rs",
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
        "cfg(feature, values())",
        "-C",
        "metadata=b1a578c002890221",
        "-C",
        "extra-filename=-1ef86475f013b331",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
        "-l",
        "static=info",
        "-l",
        "psapi",
        "-l",
        "powrprof"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name sys_info --edition=2015 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=b1a578c002890221 -C extra-filename=-1ef86475f013b331 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out -l static=info -l psapi -l powrprof",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "sys_info",
        "--edition=2015",
        "lib.rs",
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
        "cfg(feature, values())",
        "-C",
        "metadata=b1a578c002890221",
        "-C",
        "extra-filename=-1ef86475f013b331",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\build\\sys-info-c7c214762441b2c0\\out",
        "-l",
        "static=info",
        "-l",
        "psapi",
        "-l",
        "powrprof"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:11.345302+00:00",
      "end_time": "2026-07-13T14:54:11.793139+00:00",
      "start_unix_nanos": 1783954451345302100,
      "end_unix_nanos": 1783954451793138400,
      "crate_name": "sys_info",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0_6z9gle\\src\\sys-info-0.9.1\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 934,
    "crate": "sys-info",
    "version": "0.9.1",
    "crate_id": "1439",
    "version_id": "440895",
    "downloads": 23682384,
    "cumulative_downloads": 87973951497,
    "cumulative_share_of_global": 0.32891429534899636,
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
