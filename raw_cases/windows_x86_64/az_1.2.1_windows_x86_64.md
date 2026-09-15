# `az` `1.2.1`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "az",
    "version": "1.2.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000208       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000258       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000278       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000290       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000360       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000208       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000208       \\177KERNEL32_NULL_THUNK_DATA 0000000140031208     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000258       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000258       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140031258     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000278       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000278       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140031278     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000290       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000290       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140031290     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002a0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400312a0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002b0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400312b0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000348       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140031348     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000360       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000360       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140031360     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140031388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-link-link-7444-1783954631698450500.map",
  "pid": 7444,
  "ppid": 18448,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-link-link-7444-1783954631698450500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "az",
    "version": "1.2.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
      "name": "az",
      "version": "1.2.1",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 7444,
  "ppid": 18448,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "az",
    "version": "1.2.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "az",
    "version": "1.2.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "cargo_pkg_name": "az",
  "cargo_pkg_version": "1.2.1",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 7444,
  "ppid": 18448,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "_owner": {
    "crate": "az",
    "version": "1.2.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000208       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000258       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000278       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000290       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000360       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000208       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000208       \\177KERNEL32_NULL_THUNK_DATA 0000000140031208     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000258       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000258       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140031258     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000278       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000278       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140031278     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000290       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000290       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140031290     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002a0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400312a0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002b0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400312b0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000348       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140031348     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000360       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000360       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140031360     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140031388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-link-link-7444-1783954631698450500.map",
  "pid": 7444,
  "ppid": 18448,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-link-link-7444-1783954631698450500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "az",
    "version": "1.2.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
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
  "raw_event_count": 22980,
  "parsed_event_count": 22980,
  "parse_error_count": 0,
  "command_line_event_count": 22980,
  "build_script_root_event_count": 409,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 3651,
  "dropped_event_count": 12005
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17600,
  "ppid": 8952,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:57:12.072886+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\build-script-build.exe",
  "root_cargo_pid": 9320,
  "build_script_root_pid": 17600,
  "build_script_related": true,
  "build_script_target_dir": "az-b3fff3f43d787dcd"
}
```

#### Record 8

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11336,
  "ppid": 17600,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:57:12.081526+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 9320,
  "build_script_root_pid": 17600,
  "build_script_related": true,
  "build_script_target_dir": "az-b3fff3f43d787dcd"
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
  "run_id": "az:1.2.1:13136",
  "root_process_pid": 9320,
  "pid": 18900,
  "ppid": 18804,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
  "time": "2026-07-13T14:57:11.319932+00:00",
  "end_time": "2026-07-13T14:57:11.342520+00:00",
  "start_unix_nanos": 1783954631319932200,
  "end_unix_nanos": 1783954631342520000,
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
  "run_id": "az:1.2.1:13136",
  "root_process_pid": 9320,
  "pid": 14312,
  "ppid": 18804,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
  "time": "2026-07-13T14:57:11.349487+00:00",
  "end_time": "2026-07-13T14:57:11.372054+00:00",
  "start_unix_nanos": 1783954631349486800,
  "end_unix_nanos": 1783954631372053700,
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
  "run_id": "az:1.2.1:13136",
  "root_process_pid": 9320,
  "pid": 18492,
  "ppid": 8952,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
  "time": "2026-07-13T14:57:11.412489+00:00",
  "end_time": "2026-07-13T14:57:11.431944+00:00",
  "start_unix_nanos": 1783954631412489300,
  "end_unix_nanos": 1783954631431943800,
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
  "run_id": "az:1.2.1:13136",
  "root_process_pid": 9320,
  "pid": 18984,
  "ppid": 8952,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
  "time": "2026-07-13T14:57:11.438635+00:00",
  "end_time": "2026-07-13T14:57:11.461191+00:00",
  "start_unix_nanos": 1783954631438634900,
  "end_unix_nanos": 1783954631461190600,
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
  "run_id": "az:1.2.1:13136",
  "root_process_pid": 9320,
  "pid": 19220,
  "ppid": 8952,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
  "time": "2026-07-13T14:57:11.469153+00:00",
  "end_time": "2026-07-13T14:57:11.488737+00:00",
  "start_unix_nanos": 1783954631469153200,
  "end_unix_nanos": 1783954631488736800,
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
  "run_id": "az:1.2.1:13136",
  "root_process_pid": 9320,
  "pid": 16240,
  "ppid": 8952,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
    "cfg(feature, values(\"fail-on-warnings\"))",
    "-C",
    "metadata=47567ab5d982b783",
    "-C",
    "extra-filename=-b3fff3f43d787dcd",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"fail-on-warnings\\\"))\" -C metadata=47567ab5d982b783 -C extra-filename=-b3fff3f43d787dcd --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
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
    "cfg(feature, values(\"fail-on-warnings\"))",
    "-C",
    "metadata=47567ab5d982b783",
    "-C",
    "extra-filename=-b3fff3f43d787dcd",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:57:11.502760+00:00",
  "end_time": "2026-07-13T14:57:11.993574+00:00",
  "start_unix_nanos": 1783954631502760500,
  "end_unix_nanos": 1783954631993574200,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd"
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
  "run_id": "az:1.2.1:13136",
  "root_process_pid": 9320,
  "pid": 16788,
  "ppid": 8952,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "az",
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
    "cfg(feature, values(\"fail-on-warnings\"))",
    "-C",
    "metadata=ce9e0da5e0fe3ba7",
    "-C",
    "extra-filename=-a7a9a220bc8dc925",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
    "--cfg",
    "track_caller"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name az --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"fail-on-warnings\\\"))\" -C metadata=ce9e0da5e0fe3ba7 -C extra-filename=-a7a9a220bc8dc925 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps --cfg track_caller",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "az",
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
    "cfg(feature, values(\"fail-on-warnings\"))",
    "-C",
    "metadata=ce9e0da5e0fe3ba7",
    "-C",
    "extra-filename=-a7a9a220bc8dc925",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
    "--cfg",
    "track_caller"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:57:12.130050+00:00",
  "end_time": "2026-07-13T14:57:12.845060+00:00",
  "start_unix_nanos": 1783954632130050300,
  "end_unix_nanos": 1783954632845059700,
  "crate_name": "az",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:57:14.339602+00:00",
  "crate": "az",
  "version": "1.2.1",
  "duration_seconds": 25.690273899934255,
  "trace_record_count": 8,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "az",
        "version": "1.2.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 4,
    "owners": [
      {
        "crate": "az",
        "version": "1.2.1",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
          "name": "az",
          "version": "1.2.1",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 7444,
      "ppid": 18448,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "az",
        "version": "1.2.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "az",
        "version": "1.2.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "cargo_pkg_name": "az",
      "cargo_pkg_version": "1.2.1",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 7444,
      "ppid": 18448,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "_owner": {
        "crate": "az",
        "version": "1.2.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-3424-1783954631126\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\rustc2CY0IY\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000208       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000258       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000278       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000290       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000360       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000208       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000208       \\177KERNEL32_NULL_THUNK_DATA 0000000140031208     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000258       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000258       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140031258     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000278       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000278       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140031278     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000290       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000290       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140031290     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002a0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400312a0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:000002b0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400312b0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000348       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140031348     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000360       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000360       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140031360     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140031388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-link-link-7444-1783954631698450500.map",
      "pid": 7444,
      "ppid": 18448,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\.tmp\\native-trace-link-link-7444-1783954631698450500.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "az",
        "version": "1.2.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1#az@1.2.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-_lqggf65/src/az-1.2.1",
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
      "raw_event_count": 22980,
      "parsed_event_count": 22980,
      "parse_error_count": 0,
      "command_line_event_count": 22980,
      "build_script_root_event_count": 409,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 3651,
      "dropped_event_count": 12005
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17600,
      "ppid": 8952,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:57:12.072886+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd\\build-script-build.exe",
      "root_cargo_pid": 9320,
      "build_script_root_pid": 17600,
      "build_script_related": true,
      "build_script_target_dir": "az-b3fff3f43d787dcd"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11336,
      "ppid": 17600,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:57:12.081526+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 9320,
      "build_script_root_pid": 17600,
      "build_script_related": true,
      "build_script_target_dir": "az-b3fff3f43d787dcd"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "az:1.2.1:13136",
      "root_process_pid": 9320,
      "pid": 18900,
      "ppid": 18804,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
      "time": "2026-07-13T14:57:11.319932+00:00",
      "end_time": "2026-07-13T14:57:11.342520+00:00",
      "start_unix_nanos": 1783954631319932200,
      "end_unix_nanos": 1783954631342520000,
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
      "run_id": "az:1.2.1:13136",
      "root_process_pid": 9320,
      "pid": 14312,
      "ppid": 18804,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
      "time": "2026-07-13T14:57:11.349487+00:00",
      "end_time": "2026-07-13T14:57:11.372054+00:00",
      "start_unix_nanos": 1783954631349486800,
      "end_unix_nanos": 1783954631372053700,
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
      "run_id": "az:1.2.1:13136",
      "root_process_pid": 9320,
      "pid": 18492,
      "ppid": 8952,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
      "time": "2026-07-13T14:57:11.412489+00:00",
      "end_time": "2026-07-13T14:57:11.431944+00:00",
      "start_unix_nanos": 1783954631412489300,
      "end_unix_nanos": 1783954631431943800,
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
      "run_id": "az:1.2.1:13136",
      "root_process_pid": 9320,
      "pid": 18984,
      "ppid": 8952,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
      "time": "2026-07-13T14:57:11.438635+00:00",
      "end_time": "2026-07-13T14:57:11.461191+00:00",
      "start_unix_nanos": 1783954631438634900,
      "end_unix_nanos": 1783954631461190600,
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
      "run_id": "az:1.2.1:13136",
      "root_process_pid": 9320,
      "pid": 19220,
      "ppid": 8952,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
      "time": "2026-07-13T14:57:11.469153+00:00",
      "end_time": "2026-07-13T14:57:11.488737+00:00",
      "start_unix_nanos": 1783954631469153200,
      "end_unix_nanos": 1783954631488736800,
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
      "run_id": "az:1.2.1:13136",
      "root_process_pid": 9320,
      "pid": 16240,
      "ppid": 8952,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
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
        "cfg(feature, values(\"fail-on-warnings\"))",
        "-C",
        "metadata=47567ab5d982b783",
        "-C",
        "extra-filename=-b3fff3f43d787dcd",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"fail-on-warnings\\\"))\" -C metadata=47567ab5d982b783 -C extra-filename=-b3fff3f43d787dcd --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
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
        "cfg(feature, values(\"fail-on-warnings\"))",
        "-C",
        "metadata=47567ab5d982b783",
        "-C",
        "extra-filename=-b3fff3f43d787dcd",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:57:11.502760+00:00",
      "end_time": "2026-07-13T14:57:11.993574+00:00",
      "start_unix_nanos": 1783954631502760500,
      "end_unix_nanos": 1783954631993574200,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\build\\az-b3fff3f43d787dcd"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "az:1.2.1:13136",
      "root_process_pid": 9320,
      "pid": 16788,
      "ppid": 8952,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "az",
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
        "cfg(feature, values(\"fail-on-warnings\"))",
        "-C",
        "metadata=ce9e0da5e0fe3ba7",
        "-C",
        "extra-filename=-a7a9a220bc8dc925",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
        "--cfg",
        "track_caller"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name az --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"fail-on-warnings\\\"))\" -C metadata=ce9e0da5e0fe3ba7 -C extra-filename=-a7a9a220bc8dc925 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps --cfg track_caller",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "az",
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
        "cfg(feature, values(\"fail-on-warnings\"))",
        "-C",
        "metadata=ce9e0da5e0fe3ba7",
        "-C",
        "extra-filename=-a7a9a220bc8dc925",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps",
        "--cfg",
        "track_caller"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:57:12.130050+00:00",
      "end_time": "2026-07-13T14:57:12.845060+00:00",
      "start_unix_nanos": 1783954632130050300,
      "end_unix_nanos": 1783954632845059700,
      "crate_name": "az",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-_lqggf65\\src\\az-1.2.1\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 1314,
    "crate": "az",
    "version": "1.2.1",
    "crate_id": "162946",
    "version_id": "590854",
    "downloads": 14089963,
    "cumulative_downloads": 94799441609,
    "cumulative_share_of_global": 0.35443322717368064,
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
