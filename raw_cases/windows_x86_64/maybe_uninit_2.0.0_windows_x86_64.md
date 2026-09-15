# `maybe-uninit` `2.0.0`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "maybe-uninit",
    "version": "2.0.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000250       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000340       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 000000014002f200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014002f250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014002f270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014002f288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014002f298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014002f2a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014002f340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014002f358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  000000014002f388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-link-link-17608-1783954347889058500.map",
  "pid": 17608,
  "ppid": 18152,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-link-link-17608-1783954347889058500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "maybe-uninit",
    "version": "2.0.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
      "name": "maybe-uninit",
      "version": "2.0.0",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17608,
  "ppid": 18152,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "maybe-uninit",
    "version": "2.0.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "maybe-uninit",
    "version": "2.0.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "cargo_pkg_name": "maybe-uninit",
  "cargo_pkg_version": "2.0.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 17608,
  "ppid": 18152,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "_owner": {
    "crate": "maybe-uninit",
    "version": "2.0.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000250       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000340       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 000000014002f200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014002f250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014002f270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014002f288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014002f298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014002f2a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014002f340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014002f358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  000000014002f388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-link-link-17608-1783954347889058500.map",
  "pid": 17608,
  "ppid": 18152,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-link-link-17608-1783954347889058500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "maybe-uninit",
    "version": "2.0.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
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
  "raw_event_count": 9938,
  "parsed_event_count": 9938,
  "parse_error_count": 0,
  "command_line_event_count": 9938,
  "build_script_root_event_count": 209,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 811,
  "dropped_event_count": 5257
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 6384,
  "ppid": 5380,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:52:28.191077+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\build-script-build.exe",
  "root_cargo_pid": 10932,
  "build_script_root_pid": 6384,
  "build_script_related": true,
  "build_script_target_dir": "maybe-uninit-55660937fe9dee17"
}
```

#### Record 8

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11492,
  "ppid": 6384,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:52:28.199131+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 10932,
  "build_script_root_pid": 6384,
  "build_script_related": true,
  "build_script_target_dir": "maybe-uninit-55660937fe9dee17"
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
  "run_id": "maybe-uninit:2.0.0:13136",
  "root_process_pid": 10932,
  "pid": 17308,
  "ppid": 13764,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
  "time": "2026-07-13T14:52:27.539809+00:00",
  "end_time": "2026-07-13T14:52:27.570428+00:00",
  "start_unix_nanos": 1783954347539809200,
  "end_unix_nanos": 1783954347570427800,
  "crate_name": null,
  "crate_type": [],
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
  "run_id": "maybe-uninit:2.0.0:13136",
  "root_process_pid": 10932,
  "pid": 17844,
  "ppid": 13764,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
  "time": "2026-07-13T14:52:27.576726+00:00",
  "end_time": "2026-07-13T14:52:27.597008+00:00",
  "start_unix_nanos": 1783954347576726100,
  "end_unix_nanos": 1783954347597008300,
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

#### Record 11

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "maybe-uninit:2.0.0:13136",
  "root_process_pid": 10932,
  "pid": 17552,
  "ppid": 5380,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
  "time": "2026-07-13T14:52:27.635411+00:00",
  "end_time": "2026-07-13T14:52:27.653530+00:00",
  "start_unix_nanos": 1783954347635410600,
  "end_unix_nanos": 1783954347653529900,
  "crate_name": null,
  "crate_type": [],
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
  "run_id": "maybe-uninit:2.0.0:13136",
  "root_process_pid": 10932,
  "pid": 11968,
  "ppid": 5380,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
  "time": "2026-07-13T14:52:27.659859+00:00",
  "end_time": "2026-07-13T14:52:27.679430+00:00",
  "start_unix_nanos": 1783954347659858600,
  "end_unix_nanos": 1783954347679430600,
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

#### Record 13

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "maybe-uninit:2.0.0:13136",
  "root_process_pid": 10932,
  "pid": 8712,
  "ppid": 5380,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
  "time": "2026-07-13T14:52:27.687234+00:00",
  "end_time": "2026-07-13T14:52:27.704084+00:00",
  "start_unix_nanos": 1783954347687233700,
  "end_unix_nanos": 1783954347704083600,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
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
  "run_id": "maybe-uninit:2.0.0:13136",
  "root_process_pid": 10932,
  "pid": 17532,
  "ppid": 5380,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
    "metadata=fc0ea7e20732588d",
    "-C",
    "extra-filename=-55660937fe9dee17",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=fc0ea7e20732588d -C extra-filename=-55660937fe9dee17 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
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
    "metadata=fc0ea7e20732588d",
    "-C",
    "extra-filename=-55660937fe9dee17",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:52:27.717176+00:00",
  "end_time": "2026-07-13T14:52:28.141587+00:00",
  "start_unix_nanos": 1783954347717176500,
  "end_unix_nanos": 1783954348141587100,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17"
}
```

#### Record 15

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "maybe-uninit:2.0.0:13136",
  "root_process_pid": 10932,
  "pid": 7440,
  "ppid": 5380,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "maybe_uninit",
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
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=0262630d016b3bdf",
    "-C",
    "extra-filename=-59b09366752004d0",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
    "--cfg",
    "derive_copy",
    "--cfg",
    "repr_transparent",
    "--cfg",
    "native_uninit"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name maybe_uninit --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=0262630d016b3bdf -C extra-filename=-59b09366752004d0 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps --cfg derive_copy --cfg repr_transparent --cfg native_uninit",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "maybe_uninit",
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
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=0262630d016b3bdf",
    "-C",
    "extra-filename=-59b09366752004d0",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
    "--cfg",
    "derive_copy",
    "--cfg",
    "repr_transparent",
    "--cfg",
    "native_uninit"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:52:28.221653+00:00",
  "end_time": "2026-07-13T14:52:28.279315+00:00",
  "start_unix_nanos": 1783954348221653100,
  "end_unix_nanos": 1783954348279314600,
  "crate_name": "maybe_uninit",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:52:31.134790+00:00",
  "crate": "maybe-uninit",
  "version": "2.0.0",
  "duration_seconds": 26.38310169999022,
  "trace_record_count": 8,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "maybe-uninit",
        "version": "2.0.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 4,
    "owners": [
      {
        "crate": "maybe-uninit",
        "version": "2.0.0",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
          "name": "maybe-uninit",
          "version": "2.0.0",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17608,
      "ppid": 18152,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "maybe-uninit",
        "version": "2.0.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "maybe-uninit",
        "version": "2.0.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "cargo_pkg_name": "maybe-uninit",
      "cargo_pkg_version": "2.0.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 17608,
      "ppid": 18152,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "_owner": {
        "crate": "maybe-uninit",
        "version": "2.0.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-6372-1783954347359\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\rustca3fkED\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000200       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000250       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000270       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000340       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 000000014002f200     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000250       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014002f250     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014002f270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014002f288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014002f298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014002f2a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000340       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014002f340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014002f358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  000000014002f388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-link-link-17608-1783954347889058500.map",
      "pid": 17608,
      "ppid": 18152,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\.tmp\\native-trace-link-link-17608-1783954347889058500.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "maybe-uninit",
        "version": "2.0.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0#maybe-uninit@2.0.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3pn7lakt/src/maybe-uninit-2.0.0",
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
      "raw_event_count": 9938,
      "parsed_event_count": 9938,
      "parse_error_count": 0,
      "command_line_event_count": 9938,
      "build_script_root_event_count": 209,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 811,
      "dropped_event_count": 5257
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 6384,
      "ppid": 5380,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:52:28.191077+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17\\build-script-build.exe",
      "root_cargo_pid": 10932,
      "build_script_root_pid": 6384,
      "build_script_related": true,
      "build_script_target_dir": "maybe-uninit-55660937fe9dee17"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11492,
      "ppid": 6384,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:52:28.199131+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 10932,
      "build_script_root_pid": 6384,
      "build_script_related": true,
      "build_script_target_dir": "maybe-uninit-55660937fe9dee17"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "maybe-uninit:2.0.0:13136",
      "root_process_pid": 10932,
      "pid": 17308,
      "ppid": 13764,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
      "time": "2026-07-13T14:52:27.539809+00:00",
      "end_time": "2026-07-13T14:52:27.570428+00:00",
      "start_unix_nanos": 1783954347539809200,
      "end_unix_nanos": 1783954347570427800,
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
      "run_id": "maybe-uninit:2.0.0:13136",
      "root_process_pid": 10932,
      "pid": 17844,
      "ppid": 13764,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
      "time": "2026-07-13T14:52:27.576726+00:00",
      "end_time": "2026-07-13T14:52:27.597008+00:00",
      "start_unix_nanos": 1783954347576726100,
      "end_unix_nanos": 1783954347597008300,
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
      "run_id": "maybe-uninit:2.0.0:13136",
      "root_process_pid": 10932,
      "pid": 17552,
      "ppid": 5380,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
      "time": "2026-07-13T14:52:27.635411+00:00",
      "end_time": "2026-07-13T14:52:27.653530+00:00",
      "start_unix_nanos": 1783954347635410600,
      "end_unix_nanos": 1783954347653529900,
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
      "run_id": "maybe-uninit:2.0.0:13136",
      "root_process_pid": 10932,
      "pid": 11968,
      "ppid": 5380,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
      "time": "2026-07-13T14:52:27.659859+00:00",
      "end_time": "2026-07-13T14:52:27.679430+00:00",
      "start_unix_nanos": 1783954347659858600,
      "end_unix_nanos": 1783954347679430600,
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
      "run_id": "maybe-uninit:2.0.0:13136",
      "root_process_pid": 10932,
      "pid": 8712,
      "ppid": 5380,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
      "time": "2026-07-13T14:52:27.687234+00:00",
      "end_time": "2026-07-13T14:52:27.704084+00:00",
      "start_unix_nanos": 1783954347687233700,
      "end_unix_nanos": 1783954347704083600,
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
      "run_id": "maybe-uninit:2.0.0:13136",
      "root_process_pid": 10932,
      "pid": 17532,
      "ppid": 5380,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
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
        "metadata=fc0ea7e20732588d",
        "-C",
        "extra-filename=-55660937fe9dee17",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=fc0ea7e20732588d -C extra-filename=-55660937fe9dee17 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
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
        "metadata=fc0ea7e20732588d",
        "-C",
        "extra-filename=-55660937fe9dee17",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:52:27.717176+00:00",
      "end_time": "2026-07-13T14:52:28.141587+00:00",
      "start_unix_nanos": 1783954347717176500,
      "end_unix_nanos": 1783954348141587100,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\build\\maybe-uninit-55660937fe9dee17"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "maybe-uninit:2.0.0:13136",
      "root_process_pid": 10932,
      "pid": 7440,
      "ppid": 5380,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "maybe_uninit",
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
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=0262630d016b3bdf",
        "-C",
        "extra-filename=-59b09366752004d0",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
        "--cfg",
        "derive_copy",
        "--cfg",
        "repr_transparent",
        "--cfg",
        "native_uninit"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name maybe_uninit --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=0262630d016b3bdf -C extra-filename=-59b09366752004d0 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps --cfg derive_copy --cfg repr_transparent --cfg native_uninit",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "maybe_uninit",
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
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=0262630d016b3bdf",
        "-C",
        "extra-filename=-59b09366752004d0",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps",
        "--cfg",
        "derive_copy",
        "--cfg",
        "repr_transparent",
        "--cfg",
        "native_uninit"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:52:28.221653+00:00",
      "end_time": "2026-07-13T14:52:28.279315+00:00",
      "start_unix_nanos": 1783954348221653100,
      "end_unix_nanos": 1783954348279314600,
      "crate_name": "maybe_uninit",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3pn7lakt\\src\\maybe-uninit-2.0.0\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 680,
    "crate": "maybe-uninit",
    "version": "2.0.0",
    "crate_id": "147730",
    "version_id": "162171",
    "downloads": 40980880,
    "cumulative_downloads": 79894104285,
    "cumulative_share_of_global": 0.29870561190304296,
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
