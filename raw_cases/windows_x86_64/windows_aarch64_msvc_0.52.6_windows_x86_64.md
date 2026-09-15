# `windows_aarch64_msvc` `0.52.6`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_aarch64_msvc",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-link-link-14072-1783954072939013500.map",
  "pid": 14072,
  "ppid": 5936,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-link-link-14072-1783954072939013500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "windows_aarch64_msvc",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
      "name": "windows_aarch64_msvc",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "exit_code": 0,
  "kind": "exec",
  "pid": 14072,
  "ppid": 5936,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_aarch64_msvc",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_aarch64_msvc",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "cargo_pkg_name": "windows_aarch64_msvc",
  "cargo_pkg_version": "0.52.6",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 14072,
  "ppid": 5936,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "_owner": {
    "crate": "windows_aarch64_msvc",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-link-link-14072-1783954072939013500.map",
  "pid": 14072,
  "ppid": 5936,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-link-link-14072-1783954072939013500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "windows_aarch64_msvc",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
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
  "raw_event_count": 1124,
  "parsed_event_count": 1124,
  "parse_error_count": 0,
  "command_line_event_count": 1124,
  "build_script_root_event_count": 26,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 85,
  "dropped_event_count": 540
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16780,
  "ppid": 3772,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:47:53.170610+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\build-script-build.exe",
  "root_cargo_pid": 16552,
  "build_script_root_pid": 16780,
  "build_script_related": true,
  "build_script_target_dir": "windows_aarch64_msvc-47738d53126e5d30"
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
  "run_id": "windows_aarch64_msvc:0.52.6:11576",
  "root_process_pid": 16552,
  "pid": 11132,
  "ppid": 16288,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
  "time": "2026-07-13T14:47:51.309422+00:00",
  "end_time": "2026-07-13T14:47:51.328574+00:00",
  "start_unix_nanos": 1783954071309422600,
  "end_unix_nanos": 1783954071328573600,
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
  "run_id": "windows_aarch64_msvc:0.52.6:11576",
  "root_process_pid": 16552,
  "pid": 5860,
  "ppid": 16288,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
  "time": "2026-07-13T14:47:51.334804+00:00",
  "end_time": "2026-07-13T14:47:51.356049+00:00",
  "start_unix_nanos": 1783954071334804100,
  "end_unix_nanos": 1783954071356048800,
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
  "run_id": "windows_aarch64_msvc:0.52.6:11576",
  "root_process_pid": 16552,
  "pid": 5100,
  "ppid": 3772,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
  "time": "2026-07-13T14:47:52.623345+00:00",
  "end_time": "2026-07-13T14:47:52.647756+00:00",
  "start_unix_nanos": 1783954072623344600,
  "end_unix_nanos": 1783954072647756300,
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
  "run_id": "windows_aarch64_msvc:0.52.6:11576",
  "root_process_pid": 16552,
  "pid": 2600,
  "ppid": 3772,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
  "time": "2026-07-13T14:47:52.656160+00:00",
  "end_time": "2026-07-13T14:47:52.681496+00:00",
  "start_unix_nanos": 1783954072656159600,
  "end_unix_nanos": 1783954072681495600,
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
  "run_id": "windows_aarch64_msvc:0.52.6:11576",
  "root_process_pid": 16552,
  "pid": 7236,
  "ppid": 3772,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
  "time": "2026-07-13T14:47:52.702356+00:00",
  "end_time": "2026-07-13T14:47:52.722890+00:00",
  "start_unix_nanos": 1783954072702356000,
  "end_unix_nanos": 1783954072722889600,
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
  "run_id": "windows_aarch64_msvc:0.52.6:11576",
  "root_process_pid": 16552,
  "pid": 12252,
  "ppid": 3772,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
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
    "metadata=422522b7397d5513",
    "-C",
    "extra-filename=-47738d53126e5d30",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=422522b7397d5513 -C extra-filename=-47738d53126e5d30 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
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
    "metadata=422522b7397d5513",
    "-C",
    "extra-filename=-47738d53126e5d30",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:47:52.742008+00:00",
  "end_time": "2026-07-13T14:47:53.105941+00:00",
  "start_unix_nanos": 1783954072742007800,
  "end_unix_nanos": 1783954073105940700,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30"
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
  "run_id": "windows_aarch64_msvc:0.52.6:11576",
  "root_process_pid": 16552,
  "pid": 4620,
  "ppid": 3772,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_aarch64_msvc",
    "--edition=2021",
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
    "metadata=7f4a58e6f80a8568",
    "-C",
    "extra-filename=-6c6423d34af2c85c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\lib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_aarch64_msvc --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=7f4a58e6f80a8568 -C extra-filename=-6c6423d34af2c85c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\lib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_aarch64_msvc",
    "--edition=2021",
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
    "metadata=7f4a58e6f80a8568",
    "-C",
    "extra-filename=-6c6423d34af2c85c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\lib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:47:53.193009+00:00",
  "end_time": "2026-07-13T14:47:53.256631+00:00",
  "start_unix_nanos": 1783954073193009200,
  "end_unix_nanos": 1783954073256630900,
  "crate_name": "windows_aarch64_msvc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:47:55.783250+00:00",
  "crate": "windows_aarch64_msvc",
  "version": "0.52.6",
  "duration_seconds": 27.228909700061195,
  "trace_record_count": 7,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.6",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
          "name": "windows_aarch64_msvc",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "exit_code": 0,
      "kind": "exec",
      "pid": 14072,
      "ppid": 5936,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "cargo_pkg_name": "windows_aarch64_msvc",
      "cargo_pkg_version": "0.52.6",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 14072,
      "ppid": 5936,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "_owner": {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-9980-1783954071140\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\rustclJ1McS\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000148       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000198       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001d0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002b8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000148       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000198       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-link-link-14072-1783954072939013500.map",
      "pid": 14072,
      "ppid": 5936,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\.tmp\\native-trace-link-link-14072-1783954072939013500.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6#windows_aarch64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-0mmtuiz_/src/windows_aarch64_msvc-0.52.6",
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
      "raw_event_count": 1124,
      "parsed_event_count": 1124,
      "parse_error_count": 0,
      "command_line_event_count": 1124,
      "build_script_root_event_count": 26,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 85,
      "dropped_event_count": 540
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16780,
      "ppid": 3772,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:47:53.170610+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30\\build-script-build.exe",
      "root_cargo_pid": 16552,
      "build_script_root_pid": 16780,
      "build_script_related": true,
      "build_script_target_dir": "windows_aarch64_msvc-47738d53126e5d30"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "windows_aarch64_msvc:0.52.6:11576",
      "root_process_pid": 16552,
      "pid": 11132,
      "ppid": 16288,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
      "time": "2026-07-13T14:47:51.309422+00:00",
      "end_time": "2026-07-13T14:47:51.328574+00:00",
      "start_unix_nanos": 1783954071309422600,
      "end_unix_nanos": 1783954071328573600,
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
      "run_id": "windows_aarch64_msvc:0.52.6:11576",
      "root_process_pid": 16552,
      "pid": 5860,
      "ppid": 16288,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
      "time": "2026-07-13T14:47:51.334804+00:00",
      "end_time": "2026-07-13T14:47:51.356049+00:00",
      "start_unix_nanos": 1783954071334804100,
      "end_unix_nanos": 1783954071356048800,
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
      "run_id": "windows_aarch64_msvc:0.52.6:11576",
      "root_process_pid": 16552,
      "pid": 5100,
      "ppid": 3772,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
      "time": "2026-07-13T14:47:52.623345+00:00",
      "end_time": "2026-07-13T14:47:52.647756+00:00",
      "start_unix_nanos": 1783954072623344600,
      "end_unix_nanos": 1783954072647756300,
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
      "run_id": "windows_aarch64_msvc:0.52.6:11576",
      "root_process_pid": 16552,
      "pid": 2600,
      "ppid": 3772,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
      "time": "2026-07-13T14:47:52.656160+00:00",
      "end_time": "2026-07-13T14:47:52.681496+00:00",
      "start_unix_nanos": 1783954072656159600,
      "end_unix_nanos": 1783954072681495600,
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
      "run_id": "windows_aarch64_msvc:0.52.6:11576",
      "root_process_pid": 16552,
      "pid": 7236,
      "ppid": 3772,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
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
      "time": "2026-07-13T14:47:52.702356+00:00",
      "end_time": "2026-07-13T14:47:52.722890+00:00",
      "start_unix_nanos": 1783954072702356000,
      "end_unix_nanos": 1783954072722889600,
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
      "run_id": "windows_aarch64_msvc:0.52.6:11576",
      "root_process_pid": 16552,
      "pid": 12252,
      "ppid": 3772,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
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
        "metadata=422522b7397d5513",
        "-C",
        "extra-filename=-47738d53126e5d30",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=422522b7397d5513 -C extra-filename=-47738d53126e5d30 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
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
        "metadata=422522b7397d5513",
        "-C",
        "extra-filename=-47738d53126e5d30",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:47:52.742008+00:00",
      "end_time": "2026-07-13T14:47:53.105941+00:00",
      "start_unix_nanos": 1783954072742007800,
      "end_unix_nanos": 1783954073105940700,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\build\\windows_aarch64_msvc-47738d53126e5d30"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "windows_aarch64_msvc:0.52.6:11576",
      "root_process_pid": 16552,
      "pid": 4620,
      "ppid": 3772,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_aarch64_msvc",
        "--edition=2021",
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
        "metadata=7f4a58e6f80a8568",
        "-C",
        "extra-filename=-6c6423d34af2c85c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\lib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_aarch64_msvc --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=7f4a58e6f80a8568 -C extra-filename=-6c6423d34af2c85c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\lib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_aarch64_msvc",
        "--edition=2021",
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
        "metadata=7f4a58e6f80a8568",
        "-C",
        "extra-filename=-6c6423d34af2c85c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\lib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:47:53.193009+00:00",
      "end_time": "2026-07-13T14:47:53.256631+00:00",
      "start_unix_nanos": 1783954073193009200,
      "end_unix_nanos": 1783954073256630900,
      "crate_name": "windows_aarch64_msvc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-0mmtuiz_\\src\\windows_aarch64_msvc-0.52.6\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 123,
    "crate": "windows_aarch64_msvc",
    "version": "0.52.6",
    "crate_id": "477460",
    "version_id": "1191985",
    "downloads": 170947084,
    "cumulative_downloads": 31862870135,
    "cumulative_share_of_global": 0.1191279157059063,
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
