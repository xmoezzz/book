# `protobuf` `2.28.0`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "protobuf",
    "version": "2.28.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:000001d8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000228       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000248       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000260       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000280       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000318       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000330       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000358       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:000001d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:000001d8       \\177KERNEL32_NULL_THUNK_DATA 00000001400351d8     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000228       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000228       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140035228     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000248       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000248       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140035248     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000260       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000260       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140035260     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000270       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140035270     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000280       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000280       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 0000000140035280     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000318       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000318       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140035318     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000330       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000330       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140035330     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000358       \\177ntdll_NULL_THUNK_DATA  0000000140035358     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-link-link-16340-1783954262049555700.map",
  "pid": 16340,
  "ppid": 4684,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-link-link-16340-1783954262049555700.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "protobuf",
    "version": "2.28.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
      "name": "protobuf",
      "version": "2.28.0",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 16340,
  "ppid": 4684,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "protobuf",
    "version": "2.28.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "protobuf",
    "version": "2.28.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "cargo_pkg_name": "protobuf",
  "cargo_pkg_version": "2.28.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 16340,
  "ppid": 4684,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "_owner": {
    "crate": "protobuf",
    "version": "2.28.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:000001d8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000228       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000248       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000260       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000280       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000318       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000330       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000358       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:000001d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:000001d8       \\177KERNEL32_NULL_THUNK_DATA 00000001400351d8     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000228       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000228       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140035228     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000248       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000248       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140035248     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000260       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000260       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140035260     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000270       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140035270     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000280       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000280       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 0000000140035280     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000318       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000318       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140035318     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000330       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000330       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140035330     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000358       \\177ntdll_NULL_THUNK_DATA  0000000140035358     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-link-link-16340-1783954262049555700.map",
  "pid": 16340,
  "ppid": 4684,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-link-link-16340-1783954262049555700.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "protobuf",
    "version": "2.28.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
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
  "raw_event_count": 6300,
  "parsed_event_count": 6300,
  "parse_error_count": 0,
  "command_line_event_count": 6300,
  "build_script_root_event_count": 120,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 551,
  "dropped_event_count": 3328
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7560,
  "ppid": 6812,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:51:02.531901+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\build-script-build.exe",
  "root_cargo_pid": 12468,
  "build_script_root_pid": 7560,
  "build_script_related": true,
  "build_script_target_dir": "protobuf-ebd1e8f38bea5464"
}
```

#### Record 8

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 4528,
  "ppid": 7560,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:51:02.539392+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 12468,
  "build_script_root_pid": 7560,
  "build_script_related": true,
  "build_script_target_dir": "protobuf-ebd1e8f38bea5464"
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
  "run_id": "protobuf:2.28.0:2896",
  "root_process_pid": 12468,
  "pid": 6716,
  "ppid": 14932,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
  "time": "2026-07-13T14:50:59.611120+00:00",
  "end_time": "2026-07-13T14:50:59.628922+00:00",
  "start_unix_nanos": 1783954259611119700,
  "end_unix_nanos": 1783954259628921700,
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
  "run_id": "protobuf:2.28.0:2896",
  "root_process_pid": 12468,
  "pid": 1832,
  "ppid": 14932,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
  "time": "2026-07-13T14:50:59.635180+00:00",
  "end_time": "2026-07-13T14:50:59.654710+00:00",
  "start_unix_nanos": 1783954259635179600,
  "end_unix_nanos": 1783954259654709500,
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
  "run_id": "protobuf:2.28.0:2896",
  "root_process_pid": 12468,
  "pid": 12808,
  "ppid": 14932,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
  "time": "2026-07-13T14:51:00.453052+00:00",
  "end_time": "2026-07-13T14:51:00.471611+00:00",
  "start_unix_nanos": 1783954260453052000,
  "end_unix_nanos": 1783954260471610900,
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
  "run_id": "protobuf:2.28.0:2896",
  "root_process_pid": 12468,
  "pid": 688,
  "ppid": 6812,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
  "time": "2026-07-13T14:51:00.544725+00:00",
  "end_time": "2026-07-13T14:51:00.568773+00:00",
  "start_unix_nanos": 1783954260544725500,
  "end_unix_nanos": 1783954260568772700,
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
  "run_id": "protobuf:2.28.0:2896",
  "root_process_pid": 12468,
  "pid": 16896,
  "ppid": 6812,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
  "time": "2026-07-13T14:51:00.577249+00:00",
  "end_time": "2026-07-13T14:51:00.606217+00:00",
  "start_unix_nanos": 1783954260577248500,
  "end_unix_nanos": 1783954260606217500,
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

#### Record 14

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "protobuf:2.28.0:2896",
  "root_process_pid": 12468,
  "pid": 6292,
  "ppid": 6812,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
  "time": "2026-07-13T14:51:01.753795+00:00",
  "end_time": "2026-07-13T14:51:01.773141+00:00",
  "start_unix_nanos": 1783954261753794700,
  "end_unix_nanos": 1783954261773141000,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
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
  "run_id": "protobuf:2.28.0:2896",
  "root_process_pid": 12468,
  "pid": 4520,
  "ppid": 6812,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
    "cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\"))",
    "-C",
    "metadata=e3ea543b6c0c5e22",
    "-C",
    "extra-filename=-ebd1e8f38bea5464",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"bytes\\\", \\\"serde\\\", \\\"serde_derive\\\", \\\"with-bytes\\\", \\\"with-serde\\\"))\" -C metadata=e3ea543b6c0c5e22 -C extra-filename=-ebd1e8f38bea5464 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps",
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
    "cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\"))",
    "-C",
    "metadata=e3ea543b6c0c5e22",
    "-C",
    "extra-filename=-ebd1e8f38bea5464",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:51:01.787317+00:00",
  "end_time": "2026-07-13T14:51:02.455087+00:00",
  "start_unix_nanos": 1783954261787317200,
  "end_unix_nanos": 1783954262455087200,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464"
}
```

#### Record 16

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "protobuf:2.28.0:2896",
  "root_process_pid": 12468,
  "pid": 17028,
  "ppid": 6812,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "protobuf",
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
    "cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\"))",
    "-C",
    "metadata=362eee3c643bf5ad",
    "-C",
    "extra-filename=-500e10330eafa956",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name protobuf --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"bytes\\\", \\\"serde\\\", \\\"serde_derive\\\", \\\"with-bytes\\\", \\\"with-serde\\\"))\" -C metadata=362eee3c643bf5ad -C extra-filename=-500e10330eafa956 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "protobuf",
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
    "cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\"))",
    "-C",
    "metadata=362eee3c643bf5ad",
    "-C",
    "extra-filename=-500e10330eafa956",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:51:02.560519+00:00",
  "end_time": "2026-07-13T14:51:07.110257+00:00",
  "start_unix_nanos": 1783954262560518900,
  "end_unix_nanos": 1783954267110256600,
  "crate_name": "protobuf",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:51:08.036861+00:00",
  "crate": "protobuf",
  "version": "2.28.0",
  "duration_seconds": 31.180412800051272,
  "trace_record_count": 8,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "protobuf",
        "version": "2.28.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 4,
    "owners": [
      {
        "crate": "protobuf",
        "version": "2.28.0",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
          "name": "protobuf",
          "version": "2.28.0",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 16340,
      "ppid": 4684,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "protobuf",
        "version": "2.28.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "protobuf",
        "version": "2.28.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "cargo_pkg_name": "protobuf",
      "cargo_pkg_version": "2.28.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 16340,
      "ppid": 4684,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "_owner": {
        "crate": "protobuf",
        "version": "2.28.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-5728-1783954259405\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\rustcwEvSss\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:000001d8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000228       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000248       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000260       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000270       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000280       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000318       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000330       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000358       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:000001d8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:000001d8       \\177KERNEL32_NULL_THUNK_DATA 00000001400351d8     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000228       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000228       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140035228     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000248       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000248       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140035248     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000260       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000260       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140035260     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000270       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140035270     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000280       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000280       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 0000000140035280     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000318       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000318       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140035318     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000330       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000330       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140035330     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\0002:00000358       \\177ntdll_NULL_THUNK_DATA  0000000140035358     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-link-link-16340-1783954262049555700.map",
      "pid": 16340,
      "ppid": 4684,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\.tmp\\native-trace-link-link-16340-1783954262049555700.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "protobuf",
        "version": "2.28.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0#protobuf@2.28.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-vz7bzpnl/src/protobuf-2.28.0",
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
      "raw_event_count": 6300,
      "parsed_event_count": 6300,
      "parse_error_count": 0,
      "command_line_event_count": 6300,
      "build_script_root_event_count": 120,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 551,
      "dropped_event_count": 3328
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7560,
      "ppid": 6812,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:51:02.531901+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464\\build-script-build.exe",
      "root_cargo_pid": 12468,
      "build_script_root_pid": 7560,
      "build_script_related": true,
      "build_script_target_dir": "protobuf-ebd1e8f38bea5464"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 4528,
      "ppid": 7560,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:51:02.539392+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 12468,
      "build_script_root_pid": 7560,
      "build_script_related": true,
      "build_script_target_dir": "protobuf-ebd1e8f38bea5464"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "protobuf:2.28.0:2896",
      "root_process_pid": 12468,
      "pid": 6716,
      "ppid": 14932,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
      "time": "2026-07-13T14:50:59.611120+00:00",
      "end_time": "2026-07-13T14:50:59.628922+00:00",
      "start_unix_nanos": 1783954259611119700,
      "end_unix_nanos": 1783954259628921700,
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
      "run_id": "protobuf:2.28.0:2896",
      "root_process_pid": 12468,
      "pid": 1832,
      "ppid": 14932,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
      "time": "2026-07-13T14:50:59.635180+00:00",
      "end_time": "2026-07-13T14:50:59.654710+00:00",
      "start_unix_nanos": 1783954259635179600,
      "end_unix_nanos": 1783954259654709500,
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
      "run_id": "protobuf:2.28.0:2896",
      "root_process_pid": 12468,
      "pid": 12808,
      "ppid": 14932,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
      "time": "2026-07-13T14:51:00.453052+00:00",
      "end_time": "2026-07-13T14:51:00.471611+00:00",
      "start_unix_nanos": 1783954260453052000,
      "end_unix_nanos": 1783954260471610900,
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
      "run_id": "protobuf:2.28.0:2896",
      "root_process_pid": 12468,
      "pid": 688,
      "ppid": 6812,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
      "time": "2026-07-13T14:51:00.544725+00:00",
      "end_time": "2026-07-13T14:51:00.568773+00:00",
      "start_unix_nanos": 1783954260544725500,
      "end_unix_nanos": 1783954260568772700,
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
      "run_id": "protobuf:2.28.0:2896",
      "root_process_pid": 12468,
      "pid": 16896,
      "ppid": 6812,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
      "time": "2026-07-13T14:51:00.577249+00:00",
      "end_time": "2026-07-13T14:51:00.606217+00:00",
      "start_unix_nanos": 1783954260577248500,
      "end_unix_nanos": 1783954260606217500,
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
      "run_id": "protobuf:2.28.0:2896",
      "root_process_pid": 12468,
      "pid": 6292,
      "ppid": 6812,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
      "time": "2026-07-13T14:51:01.753795+00:00",
      "end_time": "2026-07-13T14:51:01.773141+00:00",
      "start_unix_nanos": 1783954261753794700,
      "end_unix_nanos": 1783954261773141000,
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
      "run_id": "protobuf:2.28.0:2896",
      "root_process_pid": 12468,
      "pid": 4520,
      "ppid": 6812,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
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
        "cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\"))",
        "-C",
        "metadata=e3ea543b6c0c5e22",
        "-C",
        "extra-filename=-ebd1e8f38bea5464",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"bytes\\\", \\\"serde\\\", \\\"serde_derive\\\", \\\"with-bytes\\\", \\\"with-serde\\\"))\" -C metadata=e3ea543b6c0c5e22 -C extra-filename=-ebd1e8f38bea5464 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps",
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
        "cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\"))",
        "-C",
        "metadata=e3ea543b6c0c5e22",
        "-C",
        "extra-filename=-ebd1e8f38bea5464",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:51:01.787317+00:00",
      "end_time": "2026-07-13T14:51:02.455087+00:00",
      "start_unix_nanos": 1783954261787317200,
      "end_unix_nanos": 1783954262455087200,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\build\\protobuf-ebd1e8f38bea5464"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "protobuf:2.28.0:2896",
      "root_process_pid": 12468,
      "pid": 17028,
      "ppid": 6812,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "protobuf",
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
        "cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\"))",
        "-C",
        "metadata=362eee3c643bf5ad",
        "-C",
        "extra-filename=-500e10330eafa956",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name protobuf --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"bytes\\\", \\\"serde\\\", \\\"serde_derive\\\", \\\"with-bytes\\\", \\\"with-serde\\\"))\" -C metadata=362eee3c643bf5ad -C extra-filename=-500e10330eafa956 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "protobuf",
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
        "cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\"))",
        "-C",
        "metadata=362eee3c643bf5ad",
        "-C",
        "extra-filename=-500e10330eafa956",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:51:02.560519+00:00",
      "end_time": "2026-07-13T14:51:07.110257+00:00",
      "start_unix_nanos": 1783954262560518900,
      "end_unix_nanos": 1783954267110256600,
      "crate_name": "protobuf",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-vz7bzpnl\\src\\protobuf-2.28.0\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 534,
    "crate": "protobuf",
    "version": "2.28.0",
    "crate_id": "198",
    "version_id": "628748",
    "downloads": 55378687,
    "cumulative_downloads": 72980633350,
    "cumulative_share_of_global": 0.27285774009204633,
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
