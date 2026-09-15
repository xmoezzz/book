# `crunchy` `0.2.2`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "crunchy",
    "version": "0.2.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000168       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001d8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000210       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002c0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002d8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000168       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000168       \\177KERNEL32_NULL_THUNK_DATA 000000014001d168     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001b8       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001d1b8     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001d8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001d1d8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001f0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001d1f0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000200       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001d200     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000210       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000210       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001d210     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002a8       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001d2a8     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002c0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001d2c0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002d8       \\177ntdll_NULL_THUNK_DATA  000000014001d2d8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-link-link-11620-1783954154066921000.map",
  "pid": 11620,
  "ppid": 11996,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-link-link-11620-1783954154066921000.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "crunchy",
    "version": "0.2.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Complete analysis record stream

These are the recovered/enriched/generated records actually supplied to native-flow reconstruction.

### Analysis records

#### Record 1

```json
{
  "event": "native_trace_root_context",
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
      "name": "crunchy",
      "version": "0.2.2",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 11620,
  "ppid": 11996,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "crunchy",
    "version": "0.2.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "crunchy",
    "version": "0.2.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "cargo_pkg_name": "crunchy",
  "cargo_pkg_version": "0.2.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 11620,
  "ppid": 11996,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "_owner": {
    "crate": "crunchy",
    "version": "0.2.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000168       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001d8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000210       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002c0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002d8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000168       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000168       \\177KERNEL32_NULL_THUNK_DATA 000000014001d168     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001b8       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001d1b8     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001d8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001d1d8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001f0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001d1f0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000200       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001d200     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000210       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000210       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001d210     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002a8       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001d2a8     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002c0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001d2c0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002d8       \\177ntdll_NULL_THUNK_DATA  000000014001d2d8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-link-link-11620-1783954154066921000.map",
  "pid": 11620,
  "ppid": 11996,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-link-link-11620-1783954154066921000.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "crunchy",
    "version": "0.2.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

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
  "raw_event_count": 2512,
  "parsed_event_count": 2512,
  "parse_error_count": 0,
  "command_line_event_count": 2512,
  "build_script_root_event_count": 49,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 182,
  "dropped_event_count": 1284
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15864,
  "ppid": 16244,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:49:14.375691+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\build-script-build.exe",
  "root_cargo_pid": 16896,
  "build_script_root_pid": 15864,
  "build_script_related": true,
  "build_script_target_dir": "crunchy-9b35e2f8ad0df3b6"
}
```

#### Record 8

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "crunchy:0.2.2:11328",
  "root_process_pid": 16896,
  "pid": 2772,
  "ppid": 1668,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
  "time": "2026-07-13T14:49:13.074522+00:00",
  "end_time": "2026-07-13T14:49:13.094473+00:00",
  "start_unix_nanos": 1783954153074522400,
  "end_unix_nanos": 1783954153094473100,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 9

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "crunchy:0.2.2:11328",
  "root_process_pid": 16896,
  "pid": 7776,
  "ppid": 1668,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
  "time": "2026-07-13T14:49:13.100683+00:00",
  "end_time": "2026-07-13T14:49:13.122214+00:00",
  "start_unix_nanos": 1783954153100682800,
  "end_unix_nanos": 1783954153122213500,
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

#### Record 10

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "crunchy:0.2.2:11328",
  "root_process_pid": 16896,
  "pid": 14496,
  "ppid": 16244,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
  "time": "2026-07-13T14:49:13.805882+00:00",
  "end_time": "2026-07-13T14:49:13.822270+00:00",
  "start_unix_nanos": 1783954153805882200,
  "end_unix_nanos": 1783954153822270000,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 11

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "crunchy:0.2.2:11328",
  "root_process_pid": 16896,
  "pid": 7624,
  "ppid": 16244,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
  "time": "2026-07-13T14:49:13.828538+00:00",
  "end_time": "2026-07-13T14:49:13.849662+00:00",
  "start_unix_nanos": 1783954153828538000,
  "end_unix_nanos": 1783954153849661500,
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

#### Record 12

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "crunchy:0.2.2:11328",
  "root_process_pid": 16896,
  "pid": 14352,
  "ppid": 16244,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
  "time": "2026-07-13T14:49:13.857377+00:00",
  "end_time": "2026-07-13T14:49:13.876269+00:00",
  "start_unix_nanos": 1783954153857376700,
  "end_unix_nanos": 1783954153876269300,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 13

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "crunchy:0.2.2:11328",
  "root_process_pid": 16896,
  "pid": 10788,
  "ppid": 16244,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"limit_128\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"limit_1024\", \"limit_128\", \"limit_2048\", \"limit_256\", \"limit_512\", \"limit_64\", \"std\"))",
    "-C",
    "metadata=a456b3c66fab8617",
    "-C",
    "extra-filename=-9b35e2f8ad0df3b6",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"limit_128\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"limit_1024\\\", \\\"limit_128\\\", \\\"limit_2048\\\", \\\"limit_256\\\", \\\"limit_512\\\", \\\"limit_64\\\", \\\"std\\\"))\" -C metadata=a456b3c66fab8617 -C extra-filename=-9b35e2f8ad0df3b6 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"limit_128\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"limit_1024\", \"limit_128\", \"limit_2048\", \"limit_256\", \"limit_512\", \"limit_64\", \"std\"))",
    "-C",
    "metadata=a456b3c66fab8617",
    "-C",
    "extra-filename=-9b35e2f8ad0df3b6",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:13.889577+00:00",
  "end_time": "2026-07-13T14:49:14.315997+00:00",
  "start_unix_nanos": 1783954153889576600,
  "end_unix_nanos": 1783954154315997000,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6"
}
```

#### Record 14

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "crunchy:0.2.2:11328",
  "root_process_pid": 16896,
  "pid": 16788,
  "ppid": 16244,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "crunchy",
    "--edition=2015",
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
    "--cfg",
    "feature=\"limit_128\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"limit_1024\", \"limit_128\", \"limit_2048\", \"limit_256\", \"limit_512\", \"limit_64\", \"std\"))",
    "-C",
    "metadata=604d3bc02b74d21d",
    "-C",
    "extra-filename=-b015137580330d97",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name crunchy --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"limit_128\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"limit_1024\\\", \\\"limit_128\\\", \\\"limit_2048\\\", \\\"limit_256\\\", \\\"limit_512\\\", \\\"limit_64\\\", \\\"std\\\"))\" -C metadata=604d3bc02b74d21d -C extra-filename=-b015137580330d97 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "crunchy",
    "--edition=2015",
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
    "--cfg",
    "feature=\"limit_128\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"limit_1024\", \"limit_128\", \"limit_2048\", \"limit_256\", \"limit_512\", \"limit_64\", \"std\"))",
    "-C",
    "metadata=604d3bc02b74d21d",
    "-C",
    "extra-filename=-b015137580330d97",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:14.392746+00:00",
  "end_time": "2026-07-13T14:49:14.457786+00:00",
  "start_unix_nanos": 1783954154392746200,
  "end_unix_nanos": 1783954154457786200,
  "crate_name": "crunchy",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:49:16.506953+00:00",
  "crate": "crunchy",
  "version": "0.2.2",
  "duration_seconds": 26.137378399958834,
  "trace_record_count": 7,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "crunchy",
        "version": "0.2.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "crunchy",
        "version": "0.2.2",
        "event_count": 4,
        "kind_counts": {
          "exec": 1,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1
        }
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
          "name": "crunchy",
          "version": "0.2.2",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 11620,
      "ppid": 11996,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "crunchy",
        "version": "0.2.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "crunchy",
        "version": "0.2.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "cargo_pkg_name": "crunchy",
      "cargo_pkg_version": "0.2.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 11620,
      "ppid": 11996,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "_owner": {
        "crate": "crunchy",
        "version": "0.2.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-13684-1783954152903\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\rustcCyzlOF\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000168       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001d8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000200       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000210       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002c0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002d8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000168       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000168       \\177KERNEL32_NULL_THUNK_DATA 000000014001d168     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001b8       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001d1b8     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001d8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001d8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001d1d8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000001f0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001d1f0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000200       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001d200     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000210       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:00000210       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001d210     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002a8       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001d2a8     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002c0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002c0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001d2c0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002d8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\0002:000002d8       \\177ntdll_NULL_THUNK_DATA  000000014001d2d8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-link-link-11620-1783954154066921000.map",
      "pid": 11620,
      "ppid": 11996,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\.tmp\\native-trace-link-link-11620-1783954154066921000.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "crunchy",
        "version": "0.2.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2#crunchy@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_k7pylnx/src/crunchy-0.2.2",
        "source": "cargo_manifest_dir"
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
      "raw_event_count": 2512,
      "parsed_event_count": 2512,
      "parse_error_count": 0,
      "command_line_event_count": 2512,
      "build_script_root_event_count": 49,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 182,
      "dropped_event_count": 1284
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15864,
      "ppid": 16244,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:49:14.375691+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6\\build-script-build.exe",
      "root_cargo_pid": 16896,
      "build_script_root_pid": 15864,
      "build_script_related": true,
      "build_script_target_dir": "crunchy-9b35e2f8ad0df3b6"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "crunchy:0.2.2:11328",
      "root_process_pid": 16896,
      "pid": 2772,
      "ppid": 1668,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
      "time": "2026-07-13T14:49:13.074522+00:00",
      "end_time": "2026-07-13T14:49:13.094473+00:00",
      "start_unix_nanos": 1783954153074522400,
      "end_unix_nanos": 1783954153094473100,
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
      "run_id": "crunchy:0.2.2:11328",
      "root_process_pid": 16896,
      "pid": 7776,
      "ppid": 1668,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
      "time": "2026-07-13T14:49:13.100683+00:00",
      "end_time": "2026-07-13T14:49:13.122214+00:00",
      "start_unix_nanos": 1783954153100682800,
      "end_unix_nanos": 1783954153122213500,
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
      "run_id": "crunchy:0.2.2:11328",
      "root_process_pid": 16896,
      "pid": 14496,
      "ppid": 16244,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
      "time": "2026-07-13T14:49:13.805882+00:00",
      "end_time": "2026-07-13T14:49:13.822270+00:00",
      "start_unix_nanos": 1783954153805882200,
      "end_unix_nanos": 1783954153822270000,
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
      "run_id": "crunchy:0.2.2:11328",
      "root_process_pid": 16896,
      "pid": 7624,
      "ppid": 16244,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
      "time": "2026-07-13T14:49:13.828538+00:00",
      "end_time": "2026-07-13T14:49:13.849662+00:00",
      "start_unix_nanos": 1783954153828538000,
      "end_unix_nanos": 1783954153849661500,
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
      "run_id": "crunchy:0.2.2:11328",
      "root_process_pid": 16896,
      "pid": 14352,
      "ppid": 16244,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
      "time": "2026-07-13T14:49:13.857377+00:00",
      "end_time": "2026-07-13T14:49:13.876269+00:00",
      "start_unix_nanos": 1783954153857376700,
      "end_unix_nanos": 1783954153876269300,
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
      "run_id": "crunchy:0.2.2:11328",
      "root_process_pid": 16896,
      "pid": 10788,
      "ppid": 16244,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"limit_128\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"limit_1024\", \"limit_128\", \"limit_2048\", \"limit_256\", \"limit_512\", \"limit_64\", \"std\"))",
        "-C",
        "metadata=a456b3c66fab8617",
        "-C",
        "extra-filename=-9b35e2f8ad0df3b6",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"limit_128\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"limit_1024\\\", \\\"limit_128\\\", \\\"limit_2048\\\", \\\"limit_256\\\", \\\"limit_512\\\", \\\"limit_64\\\", \\\"std\\\"))\" -C metadata=a456b3c66fab8617 -C extra-filename=-9b35e2f8ad0df3b6 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"limit_128\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"limit_1024\", \"limit_128\", \"limit_2048\", \"limit_256\", \"limit_512\", \"limit_64\", \"std\"))",
        "-C",
        "metadata=a456b3c66fab8617",
        "-C",
        "extra-filename=-9b35e2f8ad0df3b6",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:13.889577+00:00",
      "end_time": "2026-07-13T14:49:14.315997+00:00",
      "start_unix_nanos": 1783954153889576600,
      "end_unix_nanos": 1783954154315997000,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\build\\crunchy-9b35e2f8ad0df3b6"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "crunchy:0.2.2:11328",
      "root_process_pid": 16896,
      "pid": 16788,
      "ppid": 16244,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "crunchy",
        "--edition=2015",
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
        "--cfg",
        "feature=\"limit_128\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"limit_1024\", \"limit_128\", \"limit_2048\", \"limit_256\", \"limit_512\", \"limit_64\", \"std\"))",
        "-C",
        "metadata=604d3bc02b74d21d",
        "-C",
        "extra-filename=-b015137580330d97",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name crunchy --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"limit_128\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"limit_1024\\\", \\\"limit_128\\\", \\\"limit_2048\\\", \\\"limit_256\\\", \\\"limit_512\\\", \\\"limit_64\\\", \\\"std\\\"))\" -C metadata=604d3bc02b74d21d -C extra-filename=-b015137580330d97 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "crunchy",
        "--edition=2015",
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
        "--cfg",
        "feature=\"limit_128\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"limit_1024\", \"limit_128\", \"limit_2048\", \"limit_256\", \"limit_512\", \"limit_64\", \"std\"))",
        "-C",
        "metadata=604d3bc02b74d21d",
        "-C",
        "extra-filename=-b015137580330d97",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:14.392746+00:00",
      "end_time": "2026-07-13T14:49:14.457786+00:00",
      "start_unix_nanos": 1783954154392746200,
      "end_unix_nanos": 1783954154457786200,
      "crate_name": "crunchy",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_k7pylnx\\src\\crunchy-0.2.2\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 211,
    "crate": "crunchy",
    "version": "0.2.2",
    "crate_id": "23927",
    "version_id": "148976",
    "downloads": 129368534,
    "cumulative_downloads": 44983947656,
    "cumulative_share_of_global": 0.16818459547987827,
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
