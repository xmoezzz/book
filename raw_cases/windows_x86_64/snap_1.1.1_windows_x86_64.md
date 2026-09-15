# `snap` `1.1.1`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "snap",
    "version": "1.1.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000168       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001d8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000210       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002c0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002d8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000168       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000168       \\177KERNEL32_NULL_THUNK_DATA 000000014001e168     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001b8       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001e1b8     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001d8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001e1d8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001f0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001e1f0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000200       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001e200     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000210       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000210       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001e210     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002a8       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001e2a8     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002c0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001e2c0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002d8       \\177ntdll_NULL_THUNK_DATA  000000014001e2d8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-link-link-11580-1783954262118902500.map",
  "pid": 11580,
  "ppid": 6708,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-link-link-11580-1783954262118902500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "snap",
    "version": "1.1.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#doc-comment@0.3.3",
      "name": "doc-comment",
      "version": "0.3.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\doc-comment-0.3.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\doc-comment-0.3.3"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
      "name": "snap",
      "version": "1.1.1",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 11580,
  "ppid": 6708,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "snap",
    "version": "1.1.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "snap",
    "version": "1.1.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "cargo_pkg_name": "snap",
  "cargo_pkg_version": "1.1.1",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 11580,
  "ppid": 6708,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "_owner": {
    "crate": "snap",
    "version": "1.1.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000168       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001d8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000210       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002c0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002d8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000168       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000168       \\177KERNEL32_NULL_THUNK_DATA 000000014001e168     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001b8       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001e1b8     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001d8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001e1d8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001f0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001e1f0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000200       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001e200     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000210       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000210       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001e210     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002a8       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001e2a8     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002c0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001e2c0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002d8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002d8       \\177ntdll_NULL_THUNK_DATA  000000014001e2d8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-link-link-11580-1783954262118902500.map",
  "pid": 11580,
  "ppid": 6708,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-link-link-11580-1783954262118902500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "snap",
    "version": "1.1.1",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
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
  "raw_event_count": 6270,
  "parsed_event_count": 6270,
  "parse_error_count": 0,
  "command_line_event_count": 6270,
  "build_script_root_event_count": 120,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 551,
  "dropped_event_count": 3313
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 3772,
  "ppid": 3740,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:51:02.455611+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\build-script-build.exe",
  "root_cargo_pid": 15476,
  "build_script_root_pid": 3772,
  "build_script_related": true,
  "build_script_target_dir": "snap-10873b4e40745a3d"
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
  "run_id": "snap:1.1.1:11856",
  "root_process_pid": 15476,
  "pid": 8900,
  "ppid": 788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
  "time": "2026-07-13T14:51:01.507900+00:00",
  "end_time": "2026-07-13T14:51:01.532269+00:00",
  "start_unix_nanos": 1783954261507899600,
  "end_unix_nanos": 1783954261532269300,
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
  "run_id": "snap:1.1.1:11856",
  "root_process_pid": 15476,
  "pid": 16104,
  "ppid": 788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
  "time": "2026-07-13T14:51:01.544555+00:00",
  "end_time": "2026-07-13T14:51:01.567764+00:00",
  "start_unix_nanos": 1783954261544554700,
  "end_unix_nanos": 1783954261567764200,
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
  "run_id": "snap:1.1.1:11856",
  "root_process_pid": 15476,
  "pid": 2356,
  "ppid": 3740,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
  "time": "2026-07-13T14:51:01.800608+00:00",
  "end_time": "2026-07-13T14:51:01.820426+00:00",
  "start_unix_nanos": 1783954261800608500,
  "end_unix_nanos": 1783954261820425700,
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
  "run_id": "snap:1.1.1:11856",
  "root_process_pid": 15476,
  "pid": 17172,
  "ppid": 3740,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
  "time": "2026-07-13T14:51:01.827766+00:00",
  "end_time": "2026-07-13T14:51:01.849239+00:00",
  "start_unix_nanos": 1783954261827765700,
  "end_unix_nanos": 1783954261849239200,
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
  "run_id": "snap:1.1.1:11856",
  "root_process_pid": 15476,
  "pid": 9956,
  "ppid": 3740,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
  "time": "2026-07-13T14:51:01.858689+00:00",
  "end_time": "2026-07-13T14:51:01.881415+00:00",
  "start_unix_nanos": 1783954261858688900,
  "end_unix_nanos": 1783954261881415100,
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
  "run_id": "snap:1.1.1:11856",
  "root_process_pid": 15476,
  "pid": 5176,
  "ppid": 3740,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
    "cfg(feature, values())",
    "-C",
    "metadata=8e91b8c51a536bb7",
    "-C",
    "extra-filename=-10873b4e40745a3d",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=8e91b8c51a536bb7 -C extra-filename=-10873b4e40745a3d --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps",
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
    "cfg(feature, values())",
    "-C",
    "metadata=8e91b8c51a536bb7",
    "-C",
    "extra-filename=-10873b4e40745a3d",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:51:01.901283+00:00",
  "end_time": "2026-07-13T14:51:02.390598+00:00",
  "start_unix_nanos": 1783954261901282800,
  "end_unix_nanos": 1783954262390597600,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d"
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
  "run_id": "snap:1.1.1:11856",
  "root_process_pid": 15476,
  "pid": 16152,
  "ppid": 3740,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "snap",
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
    "cfg(feature, values())",
    "-C",
    "metadata=c0ed6344df99f6e7",
    "-C",
    "extra-filename=-251caba80ea7ebfd",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name snap --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=c0ed6344df99f6e7 -C extra-filename=-251caba80ea7ebfd --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "snap",
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
    "cfg(feature, values())",
    "-C",
    "metadata=c0ed6344df99f6e7",
    "-C",
    "extra-filename=-251caba80ea7ebfd",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:51:02.473215+00:00",
  "end_time": "2026-07-13T14:51:03.126513+00:00",
  "start_unix_nanos": 1783954262473215200,
  "end_unix_nanos": 1783954263126513200,
  "crate_name": "snap",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:51:05.680953+00:00",
  "crate": "snap",
  "version": "1.1.1",
  "duration_seconds": 26.933654599939473,
  "trace_record_count": 7,
  "trace_owner_summary": {
    "owner_package_count": 2,
    "owner_packages": [
      {
        "crate": "doc-comment",
        "version": "0.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#doc-comment@0.3.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/doc-comment-0.3.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/doc-comment-0.3.3/Cargo.toml"
      },
      {
        "crate": "snap",
        "version": "1.1.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "snap",
        "version": "1.1.1",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#doc-comment@0.3.3",
          "name": "doc-comment",
          "version": "0.3.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\doc-comment-0.3.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\doc-comment-0.3.3"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
          "name": "snap",
          "version": "1.1.1",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 11580,
      "ppid": 6708,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "snap",
        "version": "1.1.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "snap",
        "version": "1.1.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "cargo_pkg_name": "snap",
      "cargo_pkg_version": "1.1.1",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 11580,
      "ppid": 6708,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "_owner": {
        "crate": "snap",
        "version": "1.1.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-10600-1783954261254\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\rustcfzeo2U\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000168       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001d8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000200       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000210       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002c0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002d8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000168       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000168       \\177KERNEL32_NULL_THUNK_DATA 000000014001e168     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001b8       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001e1b8     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001d8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001d8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001e1d8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000001f0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001e1f0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000200       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001e200     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000210       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:00000210       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001e210     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002a8       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001e2a8     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002c0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002c0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001e2c0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002d8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\0002:000002d8       \\177ntdll_NULL_THUNK_DATA  000000014001e2d8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-link-link-11580-1783954262118902500.map",
      "pid": 11580,
      "ppid": 6708,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\.tmp\\native-trace-link-link-11580-1783954262118902500.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "snap",
        "version": "1.1.1",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1#snap@1.1.1",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w3k4c33u/src/snap-1.1.1",
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
      "raw_event_count": 6270,
      "parsed_event_count": 6270,
      "parse_error_count": 0,
      "command_line_event_count": 6270,
      "build_script_root_event_count": 120,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 551,
      "dropped_event_count": 3313
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 3772,
      "ppid": 3740,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:51:02.455611+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d\\build-script-build.exe",
      "root_cargo_pid": 15476,
      "build_script_root_pid": 3772,
      "build_script_related": true,
      "build_script_target_dir": "snap-10873b4e40745a3d"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "snap:1.1.1:11856",
      "root_process_pid": 15476,
      "pid": 8900,
      "ppid": 788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
      "time": "2026-07-13T14:51:01.507900+00:00",
      "end_time": "2026-07-13T14:51:01.532269+00:00",
      "start_unix_nanos": 1783954261507899600,
      "end_unix_nanos": 1783954261532269300,
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
      "run_id": "snap:1.1.1:11856",
      "root_process_pid": 15476,
      "pid": 16104,
      "ppid": 788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
      "time": "2026-07-13T14:51:01.544555+00:00",
      "end_time": "2026-07-13T14:51:01.567764+00:00",
      "start_unix_nanos": 1783954261544554700,
      "end_unix_nanos": 1783954261567764200,
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
      "run_id": "snap:1.1.1:11856",
      "root_process_pid": 15476,
      "pid": 2356,
      "ppid": 3740,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
      "time": "2026-07-13T14:51:01.800608+00:00",
      "end_time": "2026-07-13T14:51:01.820426+00:00",
      "start_unix_nanos": 1783954261800608500,
      "end_unix_nanos": 1783954261820425700,
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
      "run_id": "snap:1.1.1:11856",
      "root_process_pid": 15476,
      "pid": 17172,
      "ppid": 3740,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
      "time": "2026-07-13T14:51:01.827766+00:00",
      "end_time": "2026-07-13T14:51:01.849239+00:00",
      "start_unix_nanos": 1783954261827765700,
      "end_unix_nanos": 1783954261849239200,
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
      "run_id": "snap:1.1.1:11856",
      "root_process_pid": 15476,
      "pid": 9956,
      "ppid": 3740,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
      "time": "2026-07-13T14:51:01.858689+00:00",
      "end_time": "2026-07-13T14:51:01.881415+00:00",
      "start_unix_nanos": 1783954261858688900,
      "end_unix_nanos": 1783954261881415100,
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
      "run_id": "snap:1.1.1:11856",
      "root_process_pid": 15476,
      "pid": 5176,
      "ppid": 3740,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
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
        "cfg(feature, values())",
        "-C",
        "metadata=8e91b8c51a536bb7",
        "-C",
        "extra-filename=-10873b4e40745a3d",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=8e91b8c51a536bb7 -C extra-filename=-10873b4e40745a3d --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps",
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
        "cfg(feature, values())",
        "-C",
        "metadata=8e91b8c51a536bb7",
        "-C",
        "extra-filename=-10873b4e40745a3d",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:51:01.901283+00:00",
      "end_time": "2026-07-13T14:51:02.390598+00:00",
      "start_unix_nanos": 1783954261901282800,
      "end_unix_nanos": 1783954262390597600,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\build\\snap-10873b4e40745a3d"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "snap:1.1.1:11856",
      "root_process_pid": 15476,
      "pid": 16152,
      "ppid": 3740,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "snap",
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
        "cfg(feature, values())",
        "-C",
        "metadata=c0ed6344df99f6e7",
        "-C",
        "extra-filename=-251caba80ea7ebfd",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name snap --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=c0ed6344df99f6e7 -C extra-filename=-251caba80ea7ebfd --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "snap",
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
        "cfg(feature, values())",
        "-C",
        "metadata=c0ed6344df99f6e7",
        "-C",
        "extra-filename=-251caba80ea7ebfd",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:51:02.473215+00:00",
      "end_time": "2026-07-13T14:51:03.126513+00:00",
      "start_unix_nanos": 1783954262473215200,
      "end_unix_nanos": 1783954263126513200,
      "crate_name": "snap",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-w3k4c33u\\src\\snap-1.1.1\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 576,
    "crate": "snap",
    "version": "1.1.1",
    "crate_id": "5869",
    "version_id": "976354",
    "downloads": 49753098,
    "cumulative_downloads": 75196819930,
    "cumulative_share_of_global": 0.28114355009510683,
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
