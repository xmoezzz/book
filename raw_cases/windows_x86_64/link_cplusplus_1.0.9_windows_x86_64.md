# `link-cplusplus` `1.0.9`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
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
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
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
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400cf020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400cf298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400cf2b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400cf300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400cf320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400cf338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400cf348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400cf358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400cf3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400cf408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400cf418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400cf448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400cf460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-link-link-15172-1783954507971443000.map",
  "pid": 15172,
  "ppid": 18092,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-link-link-15172-1783954507971443000.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9/target/debug/build/link-cplusplus-221403ca22f24efd/out/liblink-cplusplus.a`

Owner: `link-cplusplus` `1.0.9`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9/target/debug/build/link-cplusplus-221403ca22f24efd/out/dummy.cc`

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
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "kind": "compile",
  "language": "cxx",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
  "src": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9"
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
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
      "name": "link-cplusplus",
      "version": "1.0.9",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15172,
  "ppid": 18092,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 15172,
  "ppid": 18092,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400cf020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400cf298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400cf2b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400cf300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400cf320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400cf338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400cf348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400cf358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400cf3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400cf408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400cf418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400cf448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400cf460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-link-link-15172-1783954507971443000.map",
  "pid": 15172,
  "ppid": 18092,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-link-link-15172-1783954507971443000.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 6828,
  "ppid": 17804,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
  ],
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "event_id": "used:cl:b7c984f347064422:be1e7112c33713c1:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c",
  "pid": 6828,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
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
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
  "pid": 6828,
  "ppid": 17804,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15316,
  "ppid": 17804,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
  "pid": 15316,
  "ppid": 17804,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15728,
  "ppid": 17804,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
  ],
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "event_id": "used:cl:b7c984f347064422:cf38a82bc494847b:25e19e6daa5bc362",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc",
  "pid": 15728,
  "sha256": "fdcd1ee486192ea41f47d3dde5a554cfd02f52ba70042f64063020b2ca408a7d",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
  ],
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "event_id": "used:cl:b7c984f347064422:7a769cf6a922e6a1:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
  "pid": 15728,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
  ],
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "event_id": "used:cl:b7c984f347064422:cf38a82bc494847b:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc",
  "pid": 15728,
  "sha256": "fdcd1ee486192ea41f47d3dde5a554cfd02f52ba70042f64063020b2ca408a7d",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "kind": "compile",
  "language": "cxx",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
  "src": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
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
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
  "pid": 15728,
  "ppid": 17804,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 13364,
  "ppid": 17804,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "event_id": "used:lib:b7c984f347064422:25e19e6daa5bc362:646c827fd4926687",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
  "pid": 13364,
  "sha256": "5d187422979e19093b2da9ab180c5f1ddbae016c1aa26ad8dd1a3d1bdf9175db",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "event_id": "used:lib:b7c984f347064422:25e19e6daa5bc362:d80b878b9619351d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
  "pid": 13364,
  "sha256": "5d187422979e19093b2da9ab180c5f1ddbae016c1aa26ad8dd1a3d1bdf9175db",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "cargo_pkg_name": "link-cplusplus",
  "cargo_pkg_version": "1.0.9",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
  "pid": 13364,
  "ppid": 17804,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "crate": "link-cplusplus",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "event_id": "bsrun:1fe5a020d9aaab5d:c0a868e0eea8c714:77d6787e78df97df",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "1.0.9",
  "_owner": {
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
    "source": "cwd_prefix"
  }
}
```

#### Record 26

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
  "raw_event_count": 15735,
  "parsed_event_count": 15735,
  "parse_error_count": 0,
  "command_line_event_count": 15735,
  "build_script_root_event_count": 328,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 1525,
  "dropped_event_count": 8298
}
```

#### Record 27

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17804,
  "ppid": 11960,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:55:08.285524+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\build-script-build.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 28

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 6828,
  "ppid": 17804,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:55:08.351599+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 29

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 6164,
  "ppid": 6828,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:55:08.359882+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 30

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15316,
  "ppid": 17804,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:55:08.391179+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 31

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7748,
  "ppid": 15316,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:55:08.396537+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 32

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15728,
  "ppid": 17804,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:55:08.436855+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 33

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 5544,
  "ppid": 15728,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:55:08.442643+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 34

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13364,
  "ppid": 17804,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\lib.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\lib.exe"
  ],
  "comm": "lib.exe",
  "time": "2026-07-13T14:55:08.551571+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\lib.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 35

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17584,
  "ppid": 13364,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe"
  ],
  "comm": "lib.exe",
  "time": "2026-07-13T14:55:08.560274+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 36

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 14512,
  "ppid": 17584,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
  ],
  "comm": "link.exe",
  "time": "2026-07-13T14:55:08.566505+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "root_cargo_pid": 12168,
  "build_script_root_pid": 17804,
  "build_script_related": true,
  "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
}
```

#### Record 37

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 17472,
  "ppid": 13012,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
  "time": "2026-07-13T14:55:06.538199+00:00",
  "end_time": "2026-07-13T14:55:06.556720+00:00",
  "start_unix_nanos": 1783954506538198700,
  "end_unix_nanos": 1783954506556720400,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 38

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 15728,
  "ppid": 13012,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
  "time": "2026-07-13T14:55:06.563769+00:00",
  "end_time": "2026-07-13T14:55:06.584896+00:00",
  "start_unix_nanos": 1783954506563769000,
  "end_unix_nanos": 1783954506584896000,
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

#### Record 39

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 14460,
  "ppid": 13012,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
  "time": "2026-07-13T14:55:06.699479+00:00",
  "end_time": "2026-07-13T14:55:06.716677+00:00",
  "start_unix_nanos": 1783954506699479400,
  "end_unix_nanos": 1783954506716677500,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 40

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 3292,
  "ppid": 11960,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
  "time": "2026-07-13T14:55:06.761512+00:00",
  "end_time": "2026-07-13T14:55:06.779633+00:00",
  "start_unix_nanos": 1783954506761512300,
  "end_unix_nanos": 1783954506779633200,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 41

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 6460,
  "ppid": 11960,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
  "time": "2026-07-13T14:55:06.787007+00:00",
  "end_time": "2026-07-13T14:55:06.811467+00:00",
  "start_unix_nanos": 1783954506787006500,
  "end_unix_nanos": 1783954506811466700,
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

#### Record 42

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 15976,
  "ppid": 11960,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
  "time": "2026-07-13T14:55:06.822329+00:00",
  "end_time": "2026-07-13T14:55:06.843795+00:00",
  "start_unix_nanos": 1783954506822329300,
  "end_unix_nanos": 1783954506843794800,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 43

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 18052,
  "ppid": 11960,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:55:06.861089+00:00",
  "end_time": "2026-07-13T14:55:06.981150+00:00",
  "start_unix_nanos": 1783954506861089300,
  "end_unix_nanos": 1783954506981149800,
  "crate_name": "shlex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps"
}
```

#### Record 44

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 10600,
  "ppid": 11960,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:55:06.864035+00:00",
  "end_time": "2026-07-13T14:55:07.265709+00:00",
  "start_unix_nanos": 1783954506864035000,
  "end_unix_nanos": 1783954507265709100,
  "crate_name": "find_msvc_tools",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps"
}
```

#### Record 45

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 10220,
  "ppid": 11960,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:55:07.103147+00:00",
  "end_time": "2026-07-13T14:55:07.779373+00:00",
  "start_unix_nanos": 1783954507103146900,
  "end_unix_nanos": 1783954507779373300,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps"
}
```

#### Record 46

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 7300,
  "ppid": 11960,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"libc++\", \"libcxx\", \"libstdc++\", \"libstdcxx\", \"nothing\"))",
    "-C",
    "metadata=79d6fc7528da9f43",
    "-C",
    "extra-filename=-98bd254d8b83213f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"libc++\\\", \\\"libcxx\\\", \\\"libstdc++\\\", \\\"libstdcxx\\\", \\\"nothing\\\"))\" -C metadata=79d6fc7528da9f43 -C extra-filename=-98bd254d8b83213f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
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
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"libc++\", \"libcxx\", \"libstdc++\", \"libstdcxx\", \"nothing\"))",
    "-C",
    "metadata=79d6fc7528da9f43",
    "-C",
    "extra-filename=-98bd254d8b83213f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:55:07.796908+00:00",
  "end_time": "2026-07-13T14:55:08.150671+00:00",
  "start_unix_nanos": 1783954507796908300,
  "end_unix_nanos": 1783954508150671400,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f"
}
```

#### Record 47

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "link-cplusplus:1.0.9:13136",
  "root_process_pid": 12168,
  "pid": 10848,
  "ppid": 11960,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "link_cplusplus",
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
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"libc++\", \"libcxx\", \"libstdc++\", \"libstdcxx\", \"nothing\"))",
    "-C",
    "metadata=6956254047c11d18",
    "-C",
    "extra-filename=-d47e4b82c170040e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
    "-l",
    "static=link-cplusplus"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name link_cplusplus --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"libc++\\\", \\\"libcxx\\\", \\\"libstdc++\\\", \\\"libstdcxx\\\", \\\"nothing\\\"))\" -C metadata=6956254047c11d18 -C extra-filename=-d47e4b82c170040e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out -l static=link-cplusplus",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "link_cplusplus",
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
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"libc++\", \"libcxx\", \"libstdc++\", \"libstdcxx\", \"nothing\"))",
    "-C",
    "metadata=6956254047c11d18",
    "-C",
    "extra-filename=-d47e4b82c170040e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
    "-l",
    "static=link-cplusplus"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:55:08.601803+00:00",
  "end_time": "2026-07-13T14:55:08.687589+00:00",
  "start_unix_nanos": 1783954508601803400,
  "end_unix_nanos": 1783954508687589300,
  "crate_name": "link_cplusplus",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:55:10.670274+00:00",
  "crate": "link-cplusplus",
  "version": "1.0.9",
  "duration_seconds": 26.905445900047198,
  "trace_record_count": 36,
  "trace_owner_summary": {
    "owner_package_count": 4,
    "owner_packages": [
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9/Cargo.toml"
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
      }
    ],
    "attributed_event_count": 24,
    "unattributed_event_count": 12,
    "owners": [
      {
        "crate": "link-cplusplus",
        "version": "1.0.9",
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
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9"
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
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
          "name": "link-cplusplus",
          "version": "1.0.9",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15172,
      "ppid": 18092,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 15172,
      "ppid": 18092,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\rustcAQ6gW5\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000300       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000320       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000003f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000418       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000448       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000460       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400cf020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400cf298     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400cf2b0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000300       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400cf300     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000320       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400cf320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400cf338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400cf348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400cf358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000003f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400cf3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400cf408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000418       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400cf418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000448       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400cf448     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000460       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400cf460     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-link-link-15172-1783954507971443000.map",
      "pid": 15172,
      "ppid": 18092,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-link-link-15172-1783954507971443000.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 6828,
      "ppid": 17804,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
      ],
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "event_id": "used:cl:b7c984f347064422:be1e7112c33713c1:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c",
      "pid": 6828,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
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
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\6911214702016339831detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
      "pid": 6828,
      "ppid": 17804,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15316,
      "ppid": 17804,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
      "pid": 15316,
      "ppid": 17804,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15728,
      "ppid": 17804,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
      ],
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "event_id": "used:cl:b7c984f347064422:cf38a82bc494847b:25e19e6daa5bc362",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc",
      "pid": 15728,
      "sha256": "fdcd1ee486192ea41f47d3dde5a554cfd02f52ba70042f64063020b2ca408a7d",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
      ],
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "event_id": "used:cl:b7c984f347064422:7a769cf6a922e6a1:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
      "pid": 15728,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
      ],
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "event_id": "used:cl:b7c984f347064422:cf38a82bc494847b:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc",
      "pid": 15728,
      "sha256": "fdcd1ee486192ea41f47d3dde5a554cfd02f52ba70042f64063020b2ca408a7d",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "kind": "compile",
      "language": "cxx",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
      "src": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
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
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\dummy.cc"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
      "pid": 15728,
      "ppid": 17804,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 13364,
      "ppid": 17804,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
      ],
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "event_id": "used:lib:b7c984f347064422:25e19e6daa5bc362:646c827fd4926687",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
      "pid": 13364,
      "sha256": "5d187422979e19093b2da9ab180c5f1ddbae016c1aa26ad8dd1a3d1bdf9175db",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
      ],
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "event_id": "used:lib:b7c984f347064422:25e19e6daa5bc362:d80b878b9619351d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o",
      "pid": 13364,
      "sha256": "5d187422979e19093b2da9ab180c5f1ddbae016c1aa26ad8dd1a3d1bdf9175db",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\liblink-cplusplus.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out\\de6246e600fda482-dummy.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "cargo_pkg_name": "link-cplusplus",
      "cargo_pkg_version": "1.0.9",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
      "pid": 13364,
      "ppid": 17804,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "link-cplusplus",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "event_id": "bsrun:1fe5a020d9aaab5d:c0a868e0eea8c714:77d6787e78df97df",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "1.0.9",
      "_owner": {
        "crate": "link-cplusplus",
        "version": "1.0.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9#link-cplusplus@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-5il_e3x9/src/link-cplusplus-1.0.9",
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
      "raw_event_count": 15735,
      "parsed_event_count": 15735,
      "parse_error_count": 0,
      "command_line_event_count": 15735,
      "build_script_root_event_count": 328,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 1525,
      "dropped_event_count": 8298
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17804,
      "ppid": 11960,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:55:08.285524+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f\\build-script-build.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 6828,
      "ppid": 17804,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:55:08.351599+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 6164,
      "ppid": 6828,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:55:08.359882+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15316,
      "ppid": 17804,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:55:08.391179+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7748,
      "ppid": 15316,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:55:08.396537+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15728,
      "ppid": 17804,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:55:08.436855+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\cl.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 5544,
      "ppid": 15728,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:55:08.442643+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13364,
      "ppid": 17804,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\lib.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\lib.exe"
      ],
      "comm": "lib.exe",
      "time": "2026-07-13T14:55:08.551571+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\.tmp\\native-trace-15160-1783954506336\\shims\\lib.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17584,
      "ppid": 13364,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe"
      ],
      "comm": "lib.exe",
      "time": "2026-07-13T14:55:08.560274+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 14512,
      "ppid": 17584,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
      ],
      "comm": "link.exe",
      "time": "2026-07-13T14:55:08.566505+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "root_cargo_pid": 12168,
      "build_script_root_pid": 17804,
      "build_script_related": true,
      "build_script_target_dir": "link-cplusplus-98bd254d8b83213f"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 17472,
      "ppid": 13012,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
      "time": "2026-07-13T14:55:06.538199+00:00",
      "end_time": "2026-07-13T14:55:06.556720+00:00",
      "start_unix_nanos": 1783954506538198700,
      "end_unix_nanos": 1783954506556720400,
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
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 15728,
      "ppid": 13012,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
      "time": "2026-07-13T14:55:06.563769+00:00",
      "end_time": "2026-07-13T14:55:06.584896+00:00",
      "start_unix_nanos": 1783954506563769000,
      "end_unix_nanos": 1783954506584896000,
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
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 14460,
      "ppid": 13012,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
      "time": "2026-07-13T14:55:06.699479+00:00",
      "end_time": "2026-07-13T14:55:06.716677+00:00",
      "start_unix_nanos": 1783954506699479400,
      "end_unix_nanos": 1783954506716677500,
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
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 3292,
      "ppid": 11960,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
      "time": "2026-07-13T14:55:06.761512+00:00",
      "end_time": "2026-07-13T14:55:06.779633+00:00",
      "start_unix_nanos": 1783954506761512300,
      "end_unix_nanos": 1783954506779633200,
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
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 6460,
      "ppid": 11960,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
      "time": "2026-07-13T14:55:06.787007+00:00",
      "end_time": "2026-07-13T14:55:06.811467+00:00",
      "start_unix_nanos": 1783954506787006500,
      "end_unix_nanos": 1783954506811466700,
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
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 15976,
      "ppid": 11960,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
      "time": "2026-07-13T14:55:06.822329+00:00",
      "end_time": "2026-07-13T14:55:06.843795+00:00",
      "start_unix_nanos": 1783954506822329300,
      "end_unix_nanos": 1783954506843794800,
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
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 18052,
      "ppid": 11960,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:55:06.861089+00:00",
      "end_time": "2026-07-13T14:55:06.981150+00:00",
      "start_unix_nanos": 1783954506861089300,
      "end_unix_nanos": 1783954506981149800,
      "crate_name": "shlex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 10600,
      "ppid": 11960,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:55:06.864035+00:00",
      "end_time": "2026-07-13T14:55:07.265709+00:00",
      "start_unix_nanos": 1783954506864035000,
      "end_unix_nanos": 1783954507265709100,
      "crate_name": "find_msvc_tools",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 10220,
      "ppid": 11960,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:55:07.103147+00:00",
      "end_time": "2026-07-13T14:55:07.779373+00:00",
      "start_unix_nanos": 1783954507103146900,
      "end_unix_nanos": 1783954507779373300,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 7300,
      "ppid": 11960,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
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
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"libc++\", \"libcxx\", \"libstdc++\", \"libstdcxx\", \"nothing\"))",
        "-C",
        "metadata=79d6fc7528da9f43",
        "-C",
        "extra-filename=-98bd254d8b83213f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"libc++\\\", \\\"libcxx\\\", \\\"libstdc++\\\", \\\"libstdcxx\\\", \\\"nothing\\\"))\" -C metadata=79d6fc7528da9f43 -C extra-filename=-98bd254d8b83213f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
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
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"libc++\", \"libcxx\", \"libstdc++\", \"libstdcxx\", \"nothing\"))",
        "-C",
        "metadata=79d6fc7528da9f43",
        "-C",
        "extra-filename=-98bd254d8b83213f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:55:07.796908+00:00",
      "end_time": "2026-07-13T14:55:08.150671+00:00",
      "start_unix_nanos": 1783954507796908300,
      "end_unix_nanos": 1783954508150671400,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-98bd254d8b83213f"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "link-cplusplus:1.0.9:13136",
      "root_process_pid": 12168,
      "pid": 10848,
      "ppid": 11960,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "link_cplusplus",
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
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"libc++\", \"libcxx\", \"libstdc++\", \"libstdcxx\", \"nothing\"))",
        "-C",
        "metadata=6956254047c11d18",
        "-C",
        "extra-filename=-d47e4b82c170040e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
        "-l",
        "static=link-cplusplus"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name link_cplusplus --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"libc++\\\", \\\"libcxx\\\", \\\"libstdc++\\\", \\\"libstdcxx\\\", \\\"nothing\\\"))\" -C metadata=6956254047c11d18 -C extra-filename=-d47e4b82c170040e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out -l static=link-cplusplus",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "link_cplusplus",
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
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"libc++\", \"libcxx\", \"libstdc++\", \"libstdcxx\", \"nothing\"))",
        "-C",
        "metadata=6956254047c11d18",
        "-C",
        "extra-filename=-d47e4b82c170040e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\build\\link-cplusplus-221403ca22f24efd\\out",
        "-l",
        "static=link-cplusplus"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:55:08.601803+00:00",
      "end_time": "2026-07-13T14:55:08.687589+00:00",
      "start_unix_nanos": 1783954508601803400,
      "end_unix_nanos": 1783954508687589300,
      "crate_name": "link_cplusplus",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-5il_e3x9\\src\\link-cplusplus-1.0.9\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 1061,
    "crate": "link-cplusplus",
    "version": "1.0.9",
    "crate_id": "201683",
    "version_id": "837899",
    "downloads": 19318115,
    "cumulative_downloads": 90677001987,
    "cumulative_share_of_global": 0.33902037711618205,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "build.rs",
    "build_script_exists": true,
    "package_build_field": null,
    "build_script_reason": "default_build_rs_exists",
    "download_source": "local"
  }
}
```
