# `winapi` `0.3.9`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "winapi",
    "version": "0.3.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002c8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140028148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140028198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400281b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400281d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400281e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400281f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140028288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400282a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002b0       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400282b0     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002c8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002c8       \\177ntdll_NULL_THUNK_DATA  00000001400282c8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-link-link-15976-1783954044323055300.map",
  "pid": 15976,
  "ppid": 16244,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-link-link-15976-1783954044323055300.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "winapi",
    "version": "0.3.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
      "name": "winapi",
      "version": "0.3.9",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
      "name": "winapi-i686-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-i686-pc-windows-gnu-0.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-i686-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
      "name": "winapi-x86_64-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15976,
  "ppid": 16244,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "winapi",
    "version": "0.3.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "winapi",
    "version": "0.3.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "cargo_pkg_name": "winapi",
  "cargo_pkg_version": "0.3.9",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 15976,
  "ppid": 16244,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "_owner": {
    "crate": "winapi",
    "version": "0.3.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002c8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140028148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140028198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400281b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400281d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400281e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400281f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140028288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400282a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002b0       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400282b0     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002c8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002c8       \\177ntdll_NULL_THUNK_DATA  00000001400282c8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-link-link-15976-1783954044323055300.map",
  "pid": 15976,
  "ppid": 16244,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-link-link-15976-1783954044323055300.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "winapi",
    "version": "0.3.9",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
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
  "raw_event_count": 579,
  "parsed_event_count": 579,
  "parse_error_count": 0,
  "command_line_event_count": 579,
  "build_script_root_event_count": 14,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 49,
  "dropped_event_count": 270
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 8900,
  "ppid": 6472,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:47:24.894387+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\build-script-build.exe",
  "root_cargo_pid": 6124,
  "build_script_root_pid": 8900,
  "build_script_related": true,
  "build_script_target_dir": "winapi-15abf94f880dee42"
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
  "run_id": "winapi:0.3.9:2896",
  "root_process_pid": 6124,
  "pid": 15940,
  "ppid": 15576,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
  "time": "2026-07-13T14:47:18.998905+00:00",
  "end_time": "2026-07-13T14:47:19.018018+00:00",
  "start_unix_nanos": 1783954038998905500,
  "end_unix_nanos": 1783954039018018000,
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
  "run_id": "winapi:0.3.9:2896",
  "root_process_pid": 6124,
  "pid": 16288,
  "ppid": 15576,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
  "time": "2026-07-13T14:47:19.024415+00:00",
  "end_time": "2026-07-13T14:47:19.046258+00:00",
  "start_unix_nanos": 1783954039024414800,
  "end_unix_nanos": 1783954039046258200,
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
  "run_id": "winapi:0.3.9:2896",
  "root_process_pid": 6124,
  "pid": 12692,
  "ppid": 15576,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
  "time": "2026-07-13T14:47:23.660790+00:00",
  "end_time": "2026-07-13T14:47:23.680681+00:00",
  "start_unix_nanos": 1783954043660790100,
  "end_unix_nanos": 1783954043680681400,
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
  "run_id": "winapi:0.3.9:2896",
  "root_process_pid": 6124,
  "pid": 372,
  "ppid": 6472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
  "time": "2026-07-13T14:47:23.786823+00:00",
  "end_time": "2026-07-13T14:47:23.807054+00:00",
  "start_unix_nanos": 1783954043786822900,
  "end_unix_nanos": 1783954043807054300,
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
  "run_id": "winapi:0.3.9:2896",
  "root_process_pid": 6124,
  "pid": 4372,
  "ppid": 6472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
  "time": "2026-07-13T14:47:23.813698+00:00",
  "end_time": "2026-07-13T14:47:23.836656+00:00",
  "start_unix_nanos": 1783954043813697800,
  "end_unix_nanos": 1783954043836656400,
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
  "run_id": "winapi:0.3.9:2896",
  "root_process_pid": 6124,
  "pid": 15076,
  "ppid": 6472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
  "time": "2026-07-13T14:47:23.866349+00:00",
  "end_time": "2026-07-13T14:47:23.892097+00:00",
  "start_unix_nanos": 1783954043866348600,
  "end_unix_nanos": 1783954043892096700,
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
  "run_id": "winapi:0.3.9:2896",
  "root_process_pid": 6124,
  "pid": 3768,
  "ppid": 6472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
    "cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\", \"bcrypt\", \"bits\", \"bits10_1\", \"bits1_5\", \"bits2_0\", \"bits2_5\", \"bits3_0\", \"bits4_0\", \"bits5_0\", \"bitscfg\", \"bitsmsg\", \"bluetoothapis\", \"bluetoothleapis\", \"bthdef\", \"bthioctl\", \"bthledef\", \"bthsdpdef\", \"bugcodes\", \"cderr\", \"cfg\", \"cfgmgr32\", \"cguid\", \"combaseapi\", \"coml2api\", \"commapi\", \"commctrl\", \"commdlg\", \"commoncontrols\", \"consoleapi\", \"corecrt\", \"corsym\", \"d2d1\", \"d2d1_1\", \"d2d1_2\", \"d2d1_3\", \"d2d1effectauthor\", \"d2d1effects\", \"d2d1effects_1\", \"d2d1effects_2\", \"d2d1svg\", \"d2dbasetypes\", \"d3d\", \"d3d10\", \"d3d10_1\", \"d3d10_1shader\", \"d3d10effect\", \"d3d10misc\", \"d3d10sdklayers\", \"d3d10shader\", \"d3d11\", \"d3d11_1\", \"d3d11_2\", \"d3d11_3\", \"d3d11_4\", \"d3d11on12\", \"d3d11sdklayers\", \"d3d11shader\", \"d3d11tokenizedprogramformat\", \"d3d12\", \"d3d12sdklayers\", \"d3d12shader\", \"d3d9\", \"d3d9caps\", \"d3d9types\", \"d3dcommon\", \"d3dcompiler\", \"d3dcsx\", \"d3dkmdt\", \"d3dkmthk\", \"d3dukmdt\", \"d3dx10core\", \"d3dx10math\", \"d3dx10mesh\", \"datetimeapi\", \"davclnt\", \"dbghelp\", \"dbt\", \"dcommon\", \"dcomp\", \"dcompanimation\", \"dcomptypes\", \"dde\", \"ddraw\", \"ddrawi\", \"ddrawint\", \"debug\", \"debugapi\", \"devguid\", \"devicetopology\", \"devpkey\", \"devpropdef\", \"dinput\", \"dinputd\", \"dispex\", \"dmksctl\", \"dmusicc\", \"docobj\", \"documenttarget\", \"dot1x\", \"dpa_dsa\", \"dpapi\", \"dsgetdc\", \"dsound\", \"dsrole\", \"dvp\", \"dwmapi\", \"dwrite\", \"dwrite_1\", \"dwrite_2\", \"dwrite_3\", \"dxdiag\", \"dxfile\", \"dxgi\", \"dxgi1_2\", \"dxgi1_3\", \"dxgi1_4\", \"dxgi1_5\", \"dxgi1_6\", \"dxgidebug\", \"dxgiformat\", \"dxgitype\", \"dxva2api\", \"dxvahd\", \"eaptypes\", \"enclaveapi\", \"endpointvolume\", \"errhandlingapi\", \"everything\", \"evntcons\", \"evntprov\", \"evntrace\", \"excpt\", \"exdisp\", \"fibersapi\", \"fileapi\", \"functiondiscoverykeys_devpkey\", \"gl-gl\", \"guiddef\", \"handleapi\", \"heapapi\", \"hidclass\", \"hidpi\", \"hidsdi\", \"hidusage\", \"highlevelmonitorconfigurationapi\", \"hstring\", \"http\", \"ifdef\", \"ifmib\", \"imm\", \"impl-debug\", \"impl-default\", \"in6addr\", \"inaddr\", \"inspectable\", \"interlockedapi\", \"intsafe\", \"ioapiset\", \"ipexport\", \"iphlpapi\", \"ipifcons\", \"ipmib\", \"iprtrmib\", \"iptypes\", \"jobapi\", \"jobapi2\", \"knownfolders\", \"ks\", \"ksmedia\", \"ktmtypes\", \"ktmw32\", \"l2cmn\", \"libloaderapi\", \"limits\", \"lmaccess\", \"lmalert\", \"lmapibuf\", \"lmat\", \"lmcons\", \"lmdfs\", \"lmerrlog\", \"lmjoin\", \"lmmsg\", \"lmremutl\", \"lmrepl\", \"lmserver\", \"lmshare\", \"lmstats\", \"lmsvc\", \"lmuse\", \"lmwksta\", \"lowlevelmonitorconfigurationapi\", \"lsalookup\", \"memoryapi\", \"minschannel\", \"minwinbase\", \"minwindef\", \"mmdeviceapi\", \"mmeapi\", \"mmreg\", \"mmsystem\", \"mprapidef\", \"msaatext\", \"mscat\", \"mschapp\", \"mssip\", \"mstcpip\", \"mswsock\", \"mswsockdef\", \"namedpipeapi\", \"namespaceapi\", \"nb30\", \"ncrypt\", \"netioapi\", \"nldef\", \"ntddndis\", \"ntddscsi\", \"ntddser\", \"ntdef\", \"ntlsa\", \"ntsecapi\", \"ntstatus\", \"oaidl\", \"objbase\", \"objidl\", \"objidlbase\", \"ocidl\", \"ole2\", \"oleauto\", \"olectl\", \"oleidl\", \"opmapi\", \"pdh\", \"perflib\", \"physicalmonitorenumerationapi\", \"playsoundapi\", \"portabledevice\", \"portabledeviceapi\", \"portabledevicetypes\", \"powerbase\", \"powersetting\", \"powrprof\", \"processenv\", \"processsnapshot\", \"processthreadsapi\", \"processtopologyapi\", \"profileapi\", \"propidl\", \"propkey\", \"propkeydef\", \"propsys\", \"prsht\", \"psapi\", \"qos\", \"realtimeapiset\", \"reason\", \"restartmanager\", \"restrictederrorinfo\", \"rmxfguid\", \"roapi\", \"robuffer\", \"roerrorapi\", \"rpc\", \"rpcdce\", \"rpcndr\", \"rtinfo\", \"sapi\", \"sapi51\", \"sapi53\", \"sapiddk\", \"sapiddk51\", \"schannel\", \"sddl\", \"securityappcontainer\", \"securitybaseapi\", \"servprov\", \"setupapi\", \"shellapi\", \"shellscalingapi\", \"shlobj\", \"shobjidl\", \"shobjidl_core\", \"shtypes\", \"softpub\", \"spapidef\", \"spellcheck\", \"sporder\", \"sql\", \"sqlext\", \"sqltypes\", \"sqlucode\", \"sspi\", \"std\", \"stralign\", \"stringapiset\", \"strmif\", \"subauth\", \"synchapi\", \"sysinfoapi\", \"systemtopologyapi\", \"taskschd\", \"tcpestats\", \"tcpmib\", \"textstor\", \"threadpoolapiset\", \"threadpoollegacyapiset\", \"timeapi\", \"timezoneapi\", \"tlhelp32\", \"transportsettingcommon\", \"tvout\", \"udpmib\", \"unknwnbase\", \"urlhist\", \"urlmon\", \"usb\", \"usbioctl\", \"usbiodef\", \"usbscan\", \"usbspec\", \"userenv\", \"usp10\", \"utilapiset\", \"uxtheme\", \"vadefs\", \"vcruntime\", \"vsbackup\", \"vss\", \"vsserror\", \"vswriter\", \"wbemads\", \"wbemcli\", \"wbemdisp\", \"wbemprov\", \"wbemtran\", \"wct\", \"werapi\", \"winbase\", \"wincodec\", \"wincodecsdk\", \"wincon\", \"wincontypes\", \"wincred\", \"wincrypt\", \"windef\", \"windot11\", \"windowsceip\", \"windowsx\", \"winefs\", \"winerror\", \"winevt\", \"wingdi\", \"winhttp\", \"wininet\", \"winineti\", \"winioctl\", \"winnetwk\", \"winnls\", \"winnt\", \"winreg\", \"winsafer\", \"winscard\", \"winsmcrd\", \"winsock2\", \"winspool\", \"winstring\", \"winsvc\", \"wintrust\", \"winusb\", \"winusbio\", \"winuser\", \"winver\", \"wlanapi\", \"wlanihv\", \"wlanihvtypes\", \"wlantypes\", \"wlclient\", \"wmistr\", \"wnnc\", \"wow64apiset\", \"wpdmtpextensions\", \"ws2bth\", \"ws2def\", \"ws2ipdef\", \"ws2spi\", \"ws2tcpip\", \"wtsapi32\", \"wtypes\", \"wtypesbase\", \"xinput\"))",
    "-C",
    "metadata=16b2880941ffbc77",
    "-C",
    "extra-filename=-15abf94f880dee42",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"accctrl\\\", \\\"aclapi\\\", \\\"activation\\\", \\\"adhoc\\\", \\\"appmgmt\\\", \\\"audioclient\\\", \\\"audiosessiontypes\\\", \\\"avrt\\\", \\\"basetsd\\\", \\\"bcrypt\\\", \\\"bits\\\", \\\"bits10_1\\\", \\\"bits1_5\\\", \\\"bits2_0\\\", \\\"bits2_5\\\", \\\"bits3_0\\\", \\\"bits4_0\\\", \\\"bits5_0\\\", \\\"bitscfg\\\", \\\"bitsmsg\\\", \\\"bluetoothapis\\\", \\\"bluetoothleapis\\\", \\\"bthdef\\\", \\\"bthioctl\\\", \\\"bthledef\\\", \\\"bthsdpdef\\\", \\\"bugcodes\\\", \\\"cderr\\\", \\\"cfg\\\", \\\"cfgmgr32\\\", \\\"cguid\\\", \\\"combaseapi\\\", \\\"coml2api\\\", \\\"commapi\\\", \\\"commctrl\\\", \\\"commdlg\\\", \\\"commoncontrols\\\", \\\"consoleapi\\\", \\\"corecrt\\\", \\\"corsym\\\", \\\"d2d1\\\", \\\"d2d1_1\\\", \\\"d2d1_2\\\", \\\"d2d1_3\\\", \\\"d2d1effectauthor\\\", \\\"d2d1effects\\\", \\\"d2d1effects_1\\\", \\\"d2d1effects_2\\\", \\\"d2d1svg\\\", \\\"d2dbasetypes\\\", \\\"d3d\\\", \\\"d3d10\\\", \\\"d3d10_1\\\", \\\"d3d10_1shader\\\", \\\"d3d10effect\\\", \\\"d3d10misc\\\", \\\"d3d10sdklayers\\\", \\\"d3d10shader\\\", \\\"d3d11\\\", \\\"d3d11_1\\\", \\\"d3d11_2\\\", \\\"d3d11_3\\\", \\\"d3d11_4\\\", \\\"d3d11on12\\\", \\\"d3d11sdklayers\\\", \\\"d3d11shader\\\", \\\"d3d11tokenizedprogramformat\\\", \\\"d3d12\\\", \\\"d3d12sdklayers\\\", \\\"d3d12shader\\\", \\\"d3d9\\\", \\\"d3d9caps\\\", \\\"d3d9types\\\", \\\"d3dcommon\\\", \\\"d3dcompiler\\\", \\\"d3dcsx\\\", \\\"d3dkmdt\\\", \\\"d3dkmthk\\\", \\\"d3dukmdt\\\", \\\"d3dx10core\\\", \\\"d3dx10math\\\", \\\"d3dx10mesh\\\", \\\"datetimeapi\\\", \\\"davclnt\\\", \\\"dbghelp\\\", \\\"dbt\\\", \\\"dcommon\\\", \\\"dcomp\\\", \\\"dcompanimation\\\", \\\"dcomptypes\\\", \\\"dde\\\", \\\"ddraw\\\", \\\"ddrawi\\\", \\\"ddrawint\\\", \\\"debug\\\", \\\"debugapi\\\", \\\"devguid\\\", \\\"devicetopology\\\", \\\"devpkey\\\", \\\"devpropdef\\\", \\\"dinput\\\", \\\"dinputd\\\", \\\"dispex\\\", \\\"dmksctl\\\", \\\"dmusicc\\\", \\\"docobj\\\", \\\"documenttarget\\\", \\\"dot1x\\\", \\\"dpa_dsa\\\", \\\"dpapi\\\", \\\"dsgetdc\\\", \\\"dsound\\\", \\\"dsrole\\\", \\\"dvp\\\", \\\"dwmapi\\\", \\\"dwrite\\\", \\\"dwrite_1\\\", \\\"dwrite_2\\\", \\\"dwrite_3\\\", \\\"dxdiag\\\", \\\"dxfile\\\", \\\"dxgi\\\", \\\"dxgi1_2\\\", \\\"dxgi1_3\\\", \\\"dxgi1_4\\\", \\\"dxgi1_5\\\", \\\"dxgi1_6\\\", \\\"dxgidebug\\\", \\\"dxgiformat\\\", \\\"dxgitype\\\", \\\"dxva2api\\\", \\\"dxvahd\\\", \\\"eaptypes\\\", \\\"enclaveapi\\\", \\\"endpointvolume\\\", \\\"errhandlingapi\\\", \\\"everything\\\", \\\"evntcons\\\", \\\"evntprov\\\", \\\"evntrace\\\", \\\"excpt\\\", \\\"exdisp\\\", \\\"fibersapi\\\", \\\"fileapi\\\", \\\"functiondiscoverykeys_devpkey\\\", \\\"gl-gl\\\", \\\"guiddef\\\", \\\"handleapi\\\", \\\"heapapi\\\", \\\"hidclass\\\", \\\"hidpi\\\", \\\"hidsdi\\\", \\\"hidusage\\\", \\\"highlevelmonitorconfigurationapi\\\", \\\"hstring\\\", \\\"http\\\", \\\"ifdef\\\", \\\"ifmib\\\", \\\"imm\\\", \\\"impl-debug\\\", \\\"impl-default\\\", \\\"in6addr\\\", \\\"inaddr\\\", \\\"inspectable\\\", \\\"interlockedapi\\\", \\\"intsafe\\\", \\\"ioapiset\\\", \\\"ipexport\\\", \\\"iphlpapi\\\", \\\"ipifcons\\\", \\\"ipmib\\\", \\\"iprtrmib\\\", \\\"iptypes\\\", \\\"jobapi\\\", \\\"jobapi2\\\", \\\"knownfolders\\\", \\\"ks\\\", \\\"ksmedia\\\", \\\"ktmtypes\\\", \\\"ktmw32\\\", \\\"l2cmn\\\", \\\"libloaderapi\\\", \\\"limits\\\", \\\"lmaccess\\\", \\\"lmalert\\\", \\\"lmapibuf\\\", \\\"lmat\\\", \\\"lmcons\\\", \\\"lmdfs\\\", \\\"lmerrlog\\\", \\\"lmjoin\\\", \\\"lmmsg\\\", \\\"lmremutl\\\", \\\"lmrepl\\\", \\\"lmserver\\\", \\\"lmshare\\\", \\\"lmstats\\\", \\\"lmsvc\\\", \\\"lmuse\\\", \\\"lmwksta\\\", \\\"lowlevelmonitorconfigurationapi\\\", \\\"lsalookup\\\", \\\"memoryapi\\\", \\\"minschannel\\\", \\\"minwinbase\\\", \\\"minwindef\\\", \\\"mmdeviceapi\\\", \\\"mmeapi\\\", \\\"mmreg\\\", \\\"mmsystem\\\", \\\"mprapidef\\\", \\\"msaatext\\\", \\\"mscat\\\", \\\"mschapp\\\", \\\"mssip\\\", \\\"mstcpip\\\", \\\"mswsock\\\", \\\"mswsockdef\\\", \\\"namedpipeapi\\\", \\\"namespaceapi\\\", \\\"nb30\\\", \\\"ncrypt\\\", \\\"netioapi\\\", \\\"nldef\\\", \\\"ntddndis\\\", \\\"ntddscsi\\\", \\\"ntddser\\\", \\\"ntdef\\\", \\\"ntlsa\\\", \\\"ntsecapi\\\", \\\"ntstatus\\\", \\\"oaidl\\\", \\\"objbase\\\", \\\"objidl\\\", \\\"objidlbase\\\", \\\"ocidl\\\", \\\"ole2\\\", \\\"oleauto\\\", \\\"olectl\\\", \\\"oleidl\\\", \\\"opmapi\\\", \\\"pdh\\\", \\\"perflib\\\", \\\"physicalmonitorenumerationapi\\\", \\\"playsoundapi\\\", \\\"portabledevice\\\", \\\"portabledeviceapi\\\", \\\"portabledevicetypes\\\", \\\"powerbase\\\", \\\"powersetting\\\", \\\"powrprof\\\", \\\"processenv\\\", \\\"processsnapshot\\\", \\\"processthreadsapi\\\", \\\"processtopologyapi\\\", \\\"profileapi\\\", \\\"propidl\\\", \\\"propkey\\\", \\\"propkeydef\\\", \\\"propsys\\\", \\\"prsht\\\", \\\"psapi\\\", \\\"qos\\\", \\\"realtimeapiset\\\", \\\"reason\\\", \\\"restartmanager\\\", \\\"restrictederrorinfo\\\", \\\"rmxfguid\\\", \\\"roapi\\\", \\\"robuffer\\\", \\\"roerrorapi\\\", \\\"rpc\\\", \\\"rpcdce\\\", \\\"rpcndr\\\", \\\"rtinfo\\\", \\\"sapi\\\", \\\"sapi51\\\", \\\"sapi53\\\", \\\"sapiddk\\\", \\\"sapiddk51\\\", \\\"schannel\\\", \\\"sddl\\\", \\\"securityappcontainer\\\", \\\"securitybaseapi\\\", \\\"servprov\\\", \\\"setupapi\\\", \\\"shellapi\\\", \\\"shellscalingapi\\\", \\\"shlobj\\\", \\\"shobjidl\\\", \\\"shobjidl_core\\\", \\\"shtypes\\\", \\\"softpub\\\", \\\"spapidef\\\", \\\"spellcheck\\\", \\\"sporder\\\", \\\"sql\\\", \\\"sqlext\\\", \\\"sqltypes\\\", \\\"sqlucode\\\", \\\"sspi\\\", \\\"std\\\", \\\"stralign\\\", \\\"stringapiset\\\", \\\"strmif\\\", \\\"subauth\\\", \\\"synchapi\\\", \\\"sysinfoapi\\\", \\\"systemtopologyapi\\\", \\\"taskschd\\\", \\\"tcpestats\\\", \\\"tcpmib\\\", \\\"textstor\\\", \\\"threadpoolapiset\\\", \\\"threadpoollegacyapiset\\\", \\\"timeapi\\\", \\\"timezoneapi\\\", \\\"tlhelp32\\\", \\\"transportsettingcommon\\\", \\\"tvout\\\", \\\"udpmib\\\", \\\"unknwnbase\\\", \\\"urlhist\\\", \\\"urlmon\\\", \\\"usb\\\", \\\"usbioctl\\\", \\\"usbiodef\\\", \\\"usbscan\\\", \\\"usbspec\\\", \\\"userenv\\\", \\\"usp10\\\", \\\"utilapiset\\\", \\\"uxtheme\\\", \\\"vadefs\\\", \\\"vcruntime\\\", \\\"vsbackup\\\", \\\"vss\\\", \\\"vsserror\\\", \\\"vswriter\\\", \\\"wbemads\\\", \\\"wbemcli\\\", \\\"wbemdisp\\\", \\\"wbemprov\\\", \\\"wbemtran\\\", \\\"wct\\\", \\\"werapi\\\", \\\"winbase\\\", \\\"wincodec\\\", \\\"wincodecsdk\\\", \\\"wincon\\\", \\\"wincontypes\\\", \\\"wincred\\\", \\\"wincrypt\\\", \\\"windef\\\", \\\"windot11\\\", \\\"windowsceip\\\", \\\"windowsx\\\", \\\"winefs\\\", \\\"winerror\\\", \\\"winevt\\\", \\\"wingdi\\\", \\\"winhttp\\\", \\\"wininet\\\", \\\"winineti\\\", \\\"winioctl\\\", \\\"winnetwk\\\", \\\"winnls\\\", \\\"winnt\\\", \\\"winreg\\\", \\\"winsafer\\\", \\\"winscard\\\", \\\"winsmcrd\\\", \\\"winsock2\\\", \\\"winspool\\\", \\\"winstring\\\", \\\"winsvc\\\", \\\"wintrust\\\", \\\"winusb\\\", \\\"winusbio\\\", \\\"winuser\\\", \\\"winver\\\", \\\"wlanapi\\\", \\\"wlanihv\\\", \\\"wlanihvtypes\\\", \\\"wlantypes\\\", \\\"wlclient\\\", \\\"wmistr\\\", \\\"wnnc\\\", \\\"wow64apiset\\\", \\\"wpdmtpextensions\\\", \\\"ws2bth\\\", \\\"ws2def\\\", \\\"ws2ipdef\\\", \\\"ws2spi\\\", \\\"ws2tcpip\\\", \\\"wtsapi32\\\", \\\"wtypes\\\", \\\"wtypesbase\\\", \\\"xinput\\\"))\" -C metadata=16b2880941ffbc77 -C extra-filename=-15abf94f880dee42 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps",
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
    "cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\", \"bcrypt\", \"bits\", \"bits10_1\", \"bits1_5\", \"bits2_0\", \"bits2_5\", \"bits3_0\", \"bits4_0\", \"bits5_0\", \"bitscfg\", \"bitsmsg\", \"bluetoothapis\", \"bluetoothleapis\", \"bthdef\", \"bthioctl\", \"bthledef\", \"bthsdpdef\", \"bugcodes\", \"cderr\", \"cfg\", \"cfgmgr32\", \"cguid\", \"combaseapi\", \"coml2api\", \"commapi\", \"commctrl\", \"commdlg\", \"commoncontrols\", \"consoleapi\", \"corecrt\", \"corsym\", \"d2d1\", \"d2d1_1\", \"d2d1_2\", \"d2d1_3\", \"d2d1effectauthor\", \"d2d1effects\", \"d2d1effects_1\", \"d2d1effects_2\", \"d2d1svg\", \"d2dbasetypes\", \"d3d\", \"d3d10\", \"d3d10_1\", \"d3d10_1shader\", \"d3d10effect\", \"d3d10misc\", \"d3d10sdklayers\", \"d3d10shader\", \"d3d11\", \"d3d11_1\", \"d3d11_2\", \"d3d11_3\", \"d3d11_4\", \"d3d11on12\", \"d3d11sdklayers\", \"d3d11shader\", \"d3d11tokenizedprogramformat\", \"d3d12\", \"d3d12sdklayers\", \"d3d12shader\", \"d3d9\", \"d3d9caps\", \"d3d9types\", \"d3dcommon\", \"d3dcompiler\", \"d3dcsx\", \"d3dkmdt\", \"d3dkmthk\", \"d3dukmdt\", \"d3dx10core\", \"d3dx10math\", \"d3dx10mesh\", \"datetimeapi\", \"davclnt\", \"dbghelp\", \"dbt\", \"dcommon\", \"dcomp\", \"dcompanimation\", \"dcomptypes\", \"dde\", \"ddraw\", \"ddrawi\", \"ddrawint\", \"debug\", \"debugapi\", \"devguid\", \"devicetopology\", \"devpkey\", \"devpropdef\", \"dinput\", \"dinputd\", \"dispex\", \"dmksctl\", \"dmusicc\", \"docobj\", \"documenttarget\", \"dot1x\", \"dpa_dsa\", \"dpapi\", \"dsgetdc\", \"dsound\", \"dsrole\", \"dvp\", \"dwmapi\", \"dwrite\", \"dwrite_1\", \"dwrite_2\", \"dwrite_3\", \"dxdiag\", \"dxfile\", \"dxgi\", \"dxgi1_2\", \"dxgi1_3\", \"dxgi1_4\", \"dxgi1_5\", \"dxgi1_6\", \"dxgidebug\", \"dxgiformat\", \"dxgitype\", \"dxva2api\", \"dxvahd\", \"eaptypes\", \"enclaveapi\", \"endpointvolume\", \"errhandlingapi\", \"everything\", \"evntcons\", \"evntprov\", \"evntrace\", \"excpt\", \"exdisp\", \"fibersapi\", \"fileapi\", \"functiondiscoverykeys_devpkey\", \"gl-gl\", \"guiddef\", \"handleapi\", \"heapapi\", \"hidclass\", \"hidpi\", \"hidsdi\", \"hidusage\", \"highlevelmonitorconfigurationapi\", \"hstring\", \"http\", \"ifdef\", \"ifmib\", \"imm\", \"impl-debug\", \"impl-default\", \"in6addr\", \"inaddr\", \"inspectable\", \"interlockedapi\", \"intsafe\", \"ioapiset\", \"ipexport\", \"iphlpapi\", \"ipifcons\", \"ipmib\", \"iprtrmib\", \"iptypes\", \"jobapi\", \"jobapi2\", \"knownfolders\", \"ks\", \"ksmedia\", \"ktmtypes\", \"ktmw32\", \"l2cmn\", \"libloaderapi\", \"limits\", \"lmaccess\", \"lmalert\", \"lmapibuf\", \"lmat\", \"lmcons\", \"lmdfs\", \"lmerrlog\", \"lmjoin\", \"lmmsg\", \"lmremutl\", \"lmrepl\", \"lmserver\", \"lmshare\", \"lmstats\", \"lmsvc\", \"lmuse\", \"lmwksta\", \"lowlevelmonitorconfigurationapi\", \"lsalookup\", \"memoryapi\", \"minschannel\", \"minwinbase\", \"minwindef\", \"mmdeviceapi\", \"mmeapi\", \"mmreg\", \"mmsystem\", \"mprapidef\", \"msaatext\", \"mscat\", \"mschapp\", \"mssip\", \"mstcpip\", \"mswsock\", \"mswsockdef\", \"namedpipeapi\", \"namespaceapi\", \"nb30\", \"ncrypt\", \"netioapi\", \"nldef\", \"ntddndis\", \"ntddscsi\", \"ntddser\", \"ntdef\", \"ntlsa\", \"ntsecapi\", \"ntstatus\", \"oaidl\", \"objbase\", \"objidl\", \"objidlbase\", \"ocidl\", \"ole2\", \"oleauto\", \"olectl\", \"oleidl\", \"opmapi\", \"pdh\", \"perflib\", \"physicalmonitorenumerationapi\", \"playsoundapi\", \"portabledevice\", \"portabledeviceapi\", \"portabledevicetypes\", \"powerbase\", \"powersetting\", \"powrprof\", \"processenv\", \"processsnapshot\", \"processthreadsapi\", \"processtopologyapi\", \"profileapi\", \"propidl\", \"propkey\", \"propkeydef\", \"propsys\", \"prsht\", \"psapi\", \"qos\", \"realtimeapiset\", \"reason\", \"restartmanager\", \"restrictederrorinfo\", \"rmxfguid\", \"roapi\", \"robuffer\", \"roerrorapi\", \"rpc\", \"rpcdce\", \"rpcndr\", \"rtinfo\", \"sapi\", \"sapi51\", \"sapi53\", \"sapiddk\", \"sapiddk51\", \"schannel\", \"sddl\", \"securityappcontainer\", \"securitybaseapi\", \"servprov\", \"setupapi\", \"shellapi\", \"shellscalingapi\", \"shlobj\", \"shobjidl\", \"shobjidl_core\", \"shtypes\", \"softpub\", \"spapidef\", \"spellcheck\", \"sporder\", \"sql\", \"sqlext\", \"sqltypes\", \"sqlucode\", \"sspi\", \"std\", \"stralign\", \"stringapiset\", \"strmif\", \"subauth\", \"synchapi\", \"sysinfoapi\", \"systemtopologyapi\", \"taskschd\", \"tcpestats\", \"tcpmib\", \"textstor\", \"threadpoolapiset\", \"threadpoollegacyapiset\", \"timeapi\", \"timezoneapi\", \"tlhelp32\", \"transportsettingcommon\", \"tvout\", \"udpmib\", \"unknwnbase\", \"urlhist\", \"urlmon\", \"usb\", \"usbioctl\", \"usbiodef\", \"usbscan\", \"usbspec\", \"userenv\", \"usp10\", \"utilapiset\", \"uxtheme\", \"vadefs\", \"vcruntime\", \"vsbackup\", \"vss\", \"vsserror\", \"vswriter\", \"wbemads\", \"wbemcli\", \"wbemdisp\", \"wbemprov\", \"wbemtran\", \"wct\", \"werapi\", \"winbase\", \"wincodec\", \"wincodecsdk\", \"wincon\", \"wincontypes\", \"wincred\", \"wincrypt\", \"windef\", \"windot11\", \"windowsceip\", \"windowsx\", \"winefs\", \"winerror\", \"winevt\", \"wingdi\", \"winhttp\", \"wininet\", \"winineti\", \"winioctl\", \"winnetwk\", \"winnls\", \"winnt\", \"winreg\", \"winsafer\", \"winscard\", \"winsmcrd\", \"winsock2\", \"winspool\", \"winstring\", \"winsvc\", \"wintrust\", \"winusb\", \"winusbio\", \"winuser\", \"winver\", \"wlanapi\", \"wlanihv\", \"wlanihvtypes\", \"wlantypes\", \"wlclient\", \"wmistr\", \"wnnc\", \"wow64apiset\", \"wpdmtpextensions\", \"ws2bth\", \"ws2def\", \"ws2ipdef\", \"ws2spi\", \"ws2tcpip\", \"wtsapi32\", \"wtypes\", \"wtypesbase\", \"xinput\"))",
    "-C",
    "metadata=16b2880941ffbc77",
    "-C",
    "extra-filename=-15abf94f880dee42",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:47:23.918979+00:00",
  "end_time": "2026-07-13T14:47:24.810106+00:00",
  "start_unix_nanos": 1783954043918979100,
  "end_unix_nanos": 1783954044810105700,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42"
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
  "run_id": "winapi:0.3.9:2896",
  "root_process_pid": 6124,
  "pid": 832,
  "ppid": 6472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "winapi",
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
    "cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\", \"bcrypt\", \"bits\", \"bits10_1\", \"bits1_5\", \"bits2_0\", \"bits2_5\", \"bits3_0\", \"bits4_0\", \"bits5_0\", \"bitscfg\", \"bitsmsg\", \"bluetoothapis\", \"bluetoothleapis\", \"bthdef\", \"bthioctl\", \"bthledef\", \"bthsdpdef\", \"bugcodes\", \"cderr\", \"cfg\", \"cfgmgr32\", \"cguid\", \"combaseapi\", \"coml2api\", \"commapi\", \"commctrl\", \"commdlg\", \"commoncontrols\", \"consoleapi\", \"corecrt\", \"corsym\", \"d2d1\", \"d2d1_1\", \"d2d1_2\", \"d2d1_3\", \"d2d1effectauthor\", \"d2d1effects\", \"d2d1effects_1\", \"d2d1effects_2\", \"d2d1svg\", \"d2dbasetypes\", \"d3d\", \"d3d10\", \"d3d10_1\", \"d3d10_1shader\", \"d3d10effect\", \"d3d10misc\", \"d3d10sdklayers\", \"d3d10shader\", \"d3d11\", \"d3d11_1\", \"d3d11_2\", \"d3d11_3\", \"d3d11_4\", \"d3d11on12\", \"d3d11sdklayers\", \"d3d11shader\", \"d3d11tokenizedprogramformat\", \"d3d12\", \"d3d12sdklayers\", \"d3d12shader\", \"d3d9\", \"d3d9caps\", \"d3d9types\", \"d3dcommon\", \"d3dcompiler\", \"d3dcsx\", \"d3dkmdt\", \"d3dkmthk\", \"d3dukmdt\", \"d3dx10core\", \"d3dx10math\", \"d3dx10mesh\", \"datetimeapi\", \"davclnt\", \"dbghelp\", \"dbt\", \"dcommon\", \"dcomp\", \"dcompanimation\", \"dcomptypes\", \"dde\", \"ddraw\", \"ddrawi\", \"ddrawint\", \"debug\", \"debugapi\", \"devguid\", \"devicetopology\", \"devpkey\", \"devpropdef\", \"dinput\", \"dinputd\", \"dispex\", \"dmksctl\", \"dmusicc\", \"docobj\", \"documenttarget\", \"dot1x\", \"dpa_dsa\", \"dpapi\", \"dsgetdc\", \"dsound\", \"dsrole\", \"dvp\", \"dwmapi\", \"dwrite\", \"dwrite_1\", \"dwrite_2\", \"dwrite_3\", \"dxdiag\", \"dxfile\", \"dxgi\", \"dxgi1_2\", \"dxgi1_3\", \"dxgi1_4\", \"dxgi1_5\", \"dxgi1_6\", \"dxgidebug\", \"dxgiformat\", \"dxgitype\", \"dxva2api\", \"dxvahd\", \"eaptypes\", \"enclaveapi\", \"endpointvolume\", \"errhandlingapi\", \"everything\", \"evntcons\", \"evntprov\", \"evntrace\", \"excpt\", \"exdisp\", \"fibersapi\", \"fileapi\", \"functiondiscoverykeys_devpkey\", \"gl-gl\", \"guiddef\", \"handleapi\", \"heapapi\", \"hidclass\", \"hidpi\", \"hidsdi\", \"hidusage\", \"highlevelmonitorconfigurationapi\", \"hstring\", \"http\", \"ifdef\", \"ifmib\", \"imm\", \"impl-debug\", \"impl-default\", \"in6addr\", \"inaddr\", \"inspectable\", \"interlockedapi\", \"intsafe\", \"ioapiset\", \"ipexport\", \"iphlpapi\", \"ipifcons\", \"ipmib\", \"iprtrmib\", \"iptypes\", \"jobapi\", \"jobapi2\", \"knownfolders\", \"ks\", \"ksmedia\", \"ktmtypes\", \"ktmw32\", \"l2cmn\", \"libloaderapi\", \"limits\", \"lmaccess\", \"lmalert\", \"lmapibuf\", \"lmat\", \"lmcons\", \"lmdfs\", \"lmerrlog\", \"lmjoin\", \"lmmsg\", \"lmremutl\", \"lmrepl\", \"lmserver\", \"lmshare\", \"lmstats\", \"lmsvc\", \"lmuse\", \"lmwksta\", \"lowlevelmonitorconfigurationapi\", \"lsalookup\", \"memoryapi\", \"minschannel\", \"minwinbase\", \"minwindef\", \"mmdeviceapi\", \"mmeapi\", \"mmreg\", \"mmsystem\", \"mprapidef\", \"msaatext\", \"mscat\", \"mschapp\", \"mssip\", \"mstcpip\", \"mswsock\", \"mswsockdef\", \"namedpipeapi\", \"namespaceapi\", \"nb30\", \"ncrypt\", \"netioapi\", \"nldef\", \"ntddndis\", \"ntddscsi\", \"ntddser\", \"ntdef\", \"ntlsa\", \"ntsecapi\", \"ntstatus\", \"oaidl\", \"objbase\", \"objidl\", \"objidlbase\", \"ocidl\", \"ole2\", \"oleauto\", \"olectl\", \"oleidl\", \"opmapi\", \"pdh\", \"perflib\", \"physicalmonitorenumerationapi\", \"playsoundapi\", \"portabledevice\", \"portabledeviceapi\", \"portabledevicetypes\", \"powerbase\", \"powersetting\", \"powrprof\", \"processenv\", \"processsnapshot\", \"processthreadsapi\", \"processtopologyapi\", \"profileapi\", \"propidl\", \"propkey\", \"propkeydef\", \"propsys\", \"prsht\", \"psapi\", \"qos\", \"realtimeapiset\", \"reason\", \"restartmanager\", \"restrictederrorinfo\", \"rmxfguid\", \"roapi\", \"robuffer\", \"roerrorapi\", \"rpc\", \"rpcdce\", \"rpcndr\", \"rtinfo\", \"sapi\", \"sapi51\", \"sapi53\", \"sapiddk\", \"sapiddk51\", \"schannel\", \"sddl\", \"securityappcontainer\", \"securitybaseapi\", \"servprov\", \"setupapi\", \"shellapi\", \"shellscalingapi\", \"shlobj\", \"shobjidl\", \"shobjidl_core\", \"shtypes\", \"softpub\", \"spapidef\", \"spellcheck\", \"sporder\", \"sql\", \"sqlext\", \"sqltypes\", \"sqlucode\", \"sspi\", \"std\", \"stralign\", \"stringapiset\", \"strmif\", \"subauth\", \"synchapi\", \"sysinfoapi\", \"systemtopologyapi\", \"taskschd\", \"tcpestats\", \"tcpmib\", \"textstor\", \"threadpoolapiset\", \"threadpoollegacyapiset\", \"timeapi\", \"timezoneapi\", \"tlhelp32\", \"transportsettingcommon\", \"tvout\", \"udpmib\", \"unknwnbase\", \"urlhist\", \"urlmon\", \"usb\", \"usbioctl\", \"usbiodef\", \"usbscan\", \"usbspec\", \"userenv\", \"usp10\", \"utilapiset\", \"uxtheme\", \"vadefs\", \"vcruntime\", \"vsbackup\", \"vss\", \"vsserror\", \"vswriter\", \"wbemads\", \"wbemcli\", \"wbemdisp\", \"wbemprov\", \"wbemtran\", \"wct\", \"werapi\", \"winbase\", \"wincodec\", \"wincodecsdk\", \"wincon\", \"wincontypes\", \"wincred\", \"wincrypt\", \"windef\", \"windot11\", \"windowsceip\", \"windowsx\", \"winefs\", \"winerror\", \"winevt\", \"wingdi\", \"winhttp\", \"wininet\", \"winineti\", \"winioctl\", \"winnetwk\", \"winnls\", \"winnt\", \"winreg\", \"winsafer\", \"winscard\", \"winsmcrd\", \"winsock2\", \"winspool\", \"winstring\", \"winsvc\", \"wintrust\", \"winusb\", \"winusbio\", \"winuser\", \"winver\", \"wlanapi\", \"wlanihv\", \"wlanihvtypes\", \"wlantypes\", \"wlclient\", \"wmistr\", \"wnnc\", \"wow64apiset\", \"wpdmtpextensions\", \"ws2bth\", \"ws2def\", \"ws2ipdef\", \"ws2spi\", \"ws2tcpip\", \"wtsapi32\", \"wtypes\", \"wtypesbase\", \"xinput\"))",
    "-C",
    "metadata=aefb0aee894e0ada",
    "-C",
    "extra-filename=-1353e99ede147387",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name winapi --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"accctrl\\\", \\\"aclapi\\\", \\\"activation\\\", \\\"adhoc\\\", \\\"appmgmt\\\", \\\"audioclient\\\", \\\"audiosessiontypes\\\", \\\"avrt\\\", \\\"basetsd\\\", \\\"bcrypt\\\", \\\"bits\\\", \\\"bits10_1\\\", \\\"bits1_5\\\", \\\"bits2_0\\\", \\\"bits2_5\\\", \\\"bits3_0\\\", \\\"bits4_0\\\", \\\"bits5_0\\\", \\\"bitscfg\\\", \\\"bitsmsg\\\", \\\"bluetoothapis\\\", \\\"bluetoothleapis\\\", \\\"bthdef\\\", \\\"bthioctl\\\", \\\"bthledef\\\", \\\"bthsdpdef\\\", \\\"bugcodes\\\", \\\"cderr\\\", \\\"cfg\\\", \\\"cfgmgr32\\\", \\\"cguid\\\", \\\"combaseapi\\\", \\\"coml2api\\\", \\\"commapi\\\", \\\"commctrl\\\", \\\"commdlg\\\", \\\"commoncontrols\\\", \\\"consoleapi\\\", \\\"corecrt\\\", \\\"corsym\\\", \\\"d2d1\\\", \\\"d2d1_1\\\", \\\"d2d1_2\\\", \\\"d2d1_3\\\", \\\"d2d1effectauthor\\\", \\\"d2d1effects\\\", \\\"d2d1effects_1\\\", \\\"d2d1effects_2\\\", \\\"d2d1svg\\\", \\\"d2dbasetypes\\\", \\\"d3d\\\", \\\"d3d10\\\", \\\"d3d10_1\\\", \\\"d3d10_1shader\\\", \\\"d3d10effect\\\", \\\"d3d10misc\\\", \\\"d3d10sdklayers\\\", \\\"d3d10shader\\\", \\\"d3d11\\\", \\\"d3d11_1\\\", \\\"d3d11_2\\\", \\\"d3d11_3\\\", \\\"d3d11_4\\\", \\\"d3d11on12\\\", \\\"d3d11sdklayers\\\", \\\"d3d11shader\\\", \\\"d3d11tokenizedprogramformat\\\", \\\"d3d12\\\", \\\"d3d12sdklayers\\\", \\\"d3d12shader\\\", \\\"d3d9\\\", \\\"d3d9caps\\\", \\\"d3d9types\\\", \\\"d3dcommon\\\", \\\"d3dcompiler\\\", \\\"d3dcsx\\\", \\\"d3dkmdt\\\", \\\"d3dkmthk\\\", \\\"d3dukmdt\\\", \\\"d3dx10core\\\", \\\"d3dx10math\\\", \\\"d3dx10mesh\\\", \\\"datetimeapi\\\", \\\"davclnt\\\", \\\"dbghelp\\\", \\\"dbt\\\", \\\"dcommon\\\", \\\"dcomp\\\", \\\"dcompanimation\\\", \\\"dcomptypes\\\", \\\"dde\\\", \\\"ddraw\\\", \\\"ddrawi\\\", \\\"ddrawint\\\", \\\"debug\\\", \\\"debugapi\\\", \\\"devguid\\\", \\\"devicetopology\\\", \\\"devpkey\\\", \\\"devpropdef\\\", \\\"dinput\\\", \\\"dinputd\\\", \\\"dispex\\\", \\\"dmksctl\\\", \\\"dmusicc\\\", \\\"docobj\\\", \\\"documenttarget\\\", \\\"dot1x\\\", \\\"dpa_dsa\\\", \\\"dpapi\\\", \\\"dsgetdc\\\", \\\"dsound\\\", \\\"dsrole\\\", \\\"dvp\\\", \\\"dwmapi\\\", \\\"dwrite\\\", \\\"dwrite_1\\\", \\\"dwrite_2\\\", \\\"dwrite_3\\\", \\\"dxdiag\\\", \\\"dxfile\\\", \\\"dxgi\\\", \\\"dxgi1_2\\\", \\\"dxgi1_3\\\", \\\"dxgi1_4\\\", \\\"dxgi1_5\\\", \\\"dxgi1_6\\\", \\\"dxgidebug\\\", \\\"dxgiformat\\\", \\\"dxgitype\\\", \\\"dxva2api\\\", \\\"dxvahd\\\", \\\"eaptypes\\\", \\\"enclaveapi\\\", \\\"endpointvolume\\\", \\\"errhandlingapi\\\", \\\"everything\\\", \\\"evntcons\\\", \\\"evntprov\\\", \\\"evntrace\\\", \\\"excpt\\\", \\\"exdisp\\\", \\\"fibersapi\\\", \\\"fileapi\\\", \\\"functiondiscoverykeys_devpkey\\\", \\\"gl-gl\\\", \\\"guiddef\\\", \\\"handleapi\\\", \\\"heapapi\\\", \\\"hidclass\\\", \\\"hidpi\\\", \\\"hidsdi\\\", \\\"hidusage\\\", \\\"highlevelmonitorconfigurationapi\\\", \\\"hstring\\\", \\\"http\\\", \\\"ifdef\\\", \\\"ifmib\\\", \\\"imm\\\", \\\"impl-debug\\\", \\\"impl-default\\\", \\\"in6addr\\\", \\\"inaddr\\\", \\\"inspectable\\\", \\\"interlockedapi\\\", \\\"intsafe\\\", \\\"ioapiset\\\", \\\"ipexport\\\", \\\"iphlpapi\\\", \\\"ipifcons\\\", \\\"ipmib\\\", \\\"iprtrmib\\\", \\\"iptypes\\\", \\\"jobapi\\\", \\\"jobapi2\\\", \\\"knownfolders\\\", \\\"ks\\\", \\\"ksmedia\\\", \\\"ktmtypes\\\", \\\"ktmw32\\\", \\\"l2cmn\\\", \\\"libloaderapi\\\", \\\"limits\\\", \\\"lmaccess\\\", \\\"lmalert\\\", \\\"lmapibuf\\\", \\\"lmat\\\", \\\"lmcons\\\", \\\"lmdfs\\\", \\\"lmerrlog\\\", \\\"lmjoin\\\", \\\"lmmsg\\\", \\\"lmremutl\\\", \\\"lmrepl\\\", \\\"lmserver\\\", \\\"lmshare\\\", \\\"lmstats\\\", \\\"lmsvc\\\", \\\"lmuse\\\", \\\"lmwksta\\\", \\\"lowlevelmonitorconfigurationapi\\\", \\\"lsalookup\\\", \\\"memoryapi\\\", \\\"minschannel\\\", \\\"minwinbase\\\", \\\"minwindef\\\", \\\"mmdeviceapi\\\", \\\"mmeapi\\\", \\\"mmreg\\\", \\\"mmsystem\\\", \\\"mprapidef\\\", \\\"msaatext\\\", \\\"mscat\\\", \\\"mschapp\\\", \\\"mssip\\\", \\\"mstcpip\\\", \\\"mswsock\\\", \\\"mswsockdef\\\", \\\"namedpipeapi\\\", \\\"namespaceapi\\\", \\\"nb30\\\", \\\"ncrypt\\\", \\\"netioapi\\\", \\\"nldef\\\", \\\"ntddndis\\\", \\\"ntddscsi\\\", \\\"ntddser\\\", \\\"ntdef\\\", \\\"ntlsa\\\", \\\"ntsecapi\\\", \\\"ntstatus\\\", \\\"oaidl\\\", \\\"objbase\\\", \\\"objidl\\\", \\\"objidlbase\\\", \\\"ocidl\\\", \\\"ole2\\\", \\\"oleauto\\\", \\\"olectl\\\", \\\"oleidl\\\", \\\"opmapi\\\", \\\"pdh\\\", \\\"perflib\\\", \\\"physicalmonitorenumerationapi\\\", \\\"playsoundapi\\\", \\\"portabledevice\\\", \\\"portabledeviceapi\\\", \\\"portabledevicetypes\\\", \\\"powerbase\\\", \\\"powersetting\\\", \\\"powrprof\\\", \\\"processenv\\\", \\\"processsnapshot\\\", \\\"processthreadsapi\\\", \\\"processtopologyapi\\\", \\\"profileapi\\\", \\\"propidl\\\", \\\"propkey\\\", \\\"propkeydef\\\", \\\"propsys\\\", \\\"prsht\\\", \\\"psapi\\\", \\\"qos\\\", \\\"realtimeapiset\\\", \\\"reason\\\", \\\"restartmanager\\\", \\\"restrictederrorinfo\\\", \\\"rmxfguid\\\", \\\"roapi\\\", \\\"robuffer\\\", \\\"roerrorapi\\\", \\\"rpc\\\", \\\"rpcdce\\\", \\\"rpcndr\\\", \\\"rtinfo\\\", \\\"sapi\\\", \\\"sapi51\\\", \\\"sapi53\\\", \\\"sapiddk\\\", \\\"sapiddk51\\\", \\\"schannel\\\", \\\"sddl\\\", \\\"securityappcontainer\\\", \\\"securitybaseapi\\\", \\\"servprov\\\", \\\"setupapi\\\", \\\"shellapi\\\", \\\"shellscalingapi\\\", \\\"shlobj\\\", \\\"shobjidl\\\", \\\"shobjidl_core\\\", \\\"shtypes\\\", \\\"softpub\\\", \\\"spapidef\\\", \\\"spellcheck\\\", \\\"sporder\\\", \\\"sql\\\", \\\"sqlext\\\", \\\"sqltypes\\\", \\\"sqlucode\\\", \\\"sspi\\\", \\\"std\\\", \\\"stralign\\\", \\\"stringapiset\\\", \\\"strmif\\\", \\\"subauth\\\", \\\"synchapi\\\", \\\"sysinfoapi\\\", \\\"systemtopologyapi\\\", \\\"taskschd\\\", \\\"tcpestats\\\", \\\"tcpmib\\\", \\\"textstor\\\", \\\"threadpoolapiset\\\", \\\"threadpoollegacyapiset\\\", \\\"timeapi\\\", \\\"timezoneapi\\\", \\\"tlhelp32\\\", \\\"transportsettingcommon\\\", \\\"tvout\\\", \\\"udpmib\\\", \\\"unknwnbase\\\", \\\"urlhist\\\", \\\"urlmon\\\", \\\"usb\\\", \\\"usbioctl\\\", \\\"usbiodef\\\", \\\"usbscan\\\", \\\"usbspec\\\", \\\"userenv\\\", \\\"usp10\\\", \\\"utilapiset\\\", \\\"uxtheme\\\", \\\"vadefs\\\", \\\"vcruntime\\\", \\\"vsbackup\\\", \\\"vss\\\", \\\"vsserror\\\", \\\"vswriter\\\", \\\"wbemads\\\", \\\"wbemcli\\\", \\\"wbemdisp\\\", \\\"wbemprov\\\", \\\"wbemtran\\\", \\\"wct\\\", \\\"werapi\\\", \\\"winbase\\\", \\\"wincodec\\\", \\\"wincodecsdk\\\", \\\"wincon\\\", \\\"wincontypes\\\", \\\"wincred\\\", \\\"wincrypt\\\", \\\"windef\\\", \\\"windot11\\\", \\\"windowsceip\\\", \\\"windowsx\\\", \\\"winefs\\\", \\\"winerror\\\", \\\"winevt\\\", \\\"wingdi\\\", \\\"winhttp\\\", \\\"wininet\\\", \\\"winineti\\\", \\\"winioctl\\\", \\\"winnetwk\\\", \\\"winnls\\\", \\\"winnt\\\", \\\"winreg\\\", \\\"winsafer\\\", \\\"winscard\\\", \\\"winsmcrd\\\", \\\"winsock2\\\", \\\"winspool\\\", \\\"winstring\\\", \\\"winsvc\\\", \\\"wintrust\\\", \\\"winusb\\\", \\\"winusbio\\\", \\\"winuser\\\", \\\"winver\\\", \\\"wlanapi\\\", \\\"wlanihv\\\", \\\"wlanihvtypes\\\", \\\"wlantypes\\\", \\\"wlclient\\\", \\\"wmistr\\\", \\\"wnnc\\\", \\\"wow64apiset\\\", \\\"wpdmtpextensions\\\", \\\"ws2bth\\\", \\\"ws2def\\\", \\\"ws2ipdef\\\", \\\"ws2spi\\\", \\\"ws2tcpip\\\", \\\"wtsapi32\\\", \\\"wtypes\\\", \\\"wtypesbase\\\", \\\"xinput\\\"))\" -C metadata=aefb0aee894e0ada -C extra-filename=-1353e99ede147387 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "winapi",
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
    "cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\", \"bcrypt\", \"bits\", \"bits10_1\", \"bits1_5\", \"bits2_0\", \"bits2_5\", \"bits3_0\", \"bits4_0\", \"bits5_0\", \"bitscfg\", \"bitsmsg\", \"bluetoothapis\", \"bluetoothleapis\", \"bthdef\", \"bthioctl\", \"bthledef\", \"bthsdpdef\", \"bugcodes\", \"cderr\", \"cfg\", \"cfgmgr32\", \"cguid\", \"combaseapi\", \"coml2api\", \"commapi\", \"commctrl\", \"commdlg\", \"commoncontrols\", \"consoleapi\", \"corecrt\", \"corsym\", \"d2d1\", \"d2d1_1\", \"d2d1_2\", \"d2d1_3\", \"d2d1effectauthor\", \"d2d1effects\", \"d2d1effects_1\", \"d2d1effects_2\", \"d2d1svg\", \"d2dbasetypes\", \"d3d\", \"d3d10\", \"d3d10_1\", \"d3d10_1shader\", \"d3d10effect\", \"d3d10misc\", \"d3d10sdklayers\", \"d3d10shader\", \"d3d11\", \"d3d11_1\", \"d3d11_2\", \"d3d11_3\", \"d3d11_4\", \"d3d11on12\", \"d3d11sdklayers\", \"d3d11shader\", \"d3d11tokenizedprogramformat\", \"d3d12\", \"d3d12sdklayers\", \"d3d12shader\", \"d3d9\", \"d3d9caps\", \"d3d9types\", \"d3dcommon\", \"d3dcompiler\", \"d3dcsx\", \"d3dkmdt\", \"d3dkmthk\", \"d3dukmdt\", \"d3dx10core\", \"d3dx10math\", \"d3dx10mesh\", \"datetimeapi\", \"davclnt\", \"dbghelp\", \"dbt\", \"dcommon\", \"dcomp\", \"dcompanimation\", \"dcomptypes\", \"dde\", \"ddraw\", \"ddrawi\", \"ddrawint\", \"debug\", \"debugapi\", \"devguid\", \"devicetopology\", \"devpkey\", \"devpropdef\", \"dinput\", \"dinputd\", \"dispex\", \"dmksctl\", \"dmusicc\", \"docobj\", \"documenttarget\", \"dot1x\", \"dpa_dsa\", \"dpapi\", \"dsgetdc\", \"dsound\", \"dsrole\", \"dvp\", \"dwmapi\", \"dwrite\", \"dwrite_1\", \"dwrite_2\", \"dwrite_3\", \"dxdiag\", \"dxfile\", \"dxgi\", \"dxgi1_2\", \"dxgi1_3\", \"dxgi1_4\", \"dxgi1_5\", \"dxgi1_6\", \"dxgidebug\", \"dxgiformat\", \"dxgitype\", \"dxva2api\", \"dxvahd\", \"eaptypes\", \"enclaveapi\", \"endpointvolume\", \"errhandlingapi\", \"everything\", \"evntcons\", \"evntprov\", \"evntrace\", \"excpt\", \"exdisp\", \"fibersapi\", \"fileapi\", \"functiondiscoverykeys_devpkey\", \"gl-gl\", \"guiddef\", \"handleapi\", \"heapapi\", \"hidclass\", \"hidpi\", \"hidsdi\", \"hidusage\", \"highlevelmonitorconfigurationapi\", \"hstring\", \"http\", \"ifdef\", \"ifmib\", \"imm\", \"impl-debug\", \"impl-default\", \"in6addr\", \"inaddr\", \"inspectable\", \"interlockedapi\", \"intsafe\", \"ioapiset\", \"ipexport\", \"iphlpapi\", \"ipifcons\", \"ipmib\", \"iprtrmib\", \"iptypes\", \"jobapi\", \"jobapi2\", \"knownfolders\", \"ks\", \"ksmedia\", \"ktmtypes\", \"ktmw32\", \"l2cmn\", \"libloaderapi\", \"limits\", \"lmaccess\", \"lmalert\", \"lmapibuf\", \"lmat\", \"lmcons\", \"lmdfs\", \"lmerrlog\", \"lmjoin\", \"lmmsg\", \"lmremutl\", \"lmrepl\", \"lmserver\", \"lmshare\", \"lmstats\", \"lmsvc\", \"lmuse\", \"lmwksta\", \"lowlevelmonitorconfigurationapi\", \"lsalookup\", \"memoryapi\", \"minschannel\", \"minwinbase\", \"minwindef\", \"mmdeviceapi\", \"mmeapi\", \"mmreg\", \"mmsystem\", \"mprapidef\", \"msaatext\", \"mscat\", \"mschapp\", \"mssip\", \"mstcpip\", \"mswsock\", \"mswsockdef\", \"namedpipeapi\", \"namespaceapi\", \"nb30\", \"ncrypt\", \"netioapi\", \"nldef\", \"ntddndis\", \"ntddscsi\", \"ntddser\", \"ntdef\", \"ntlsa\", \"ntsecapi\", \"ntstatus\", \"oaidl\", \"objbase\", \"objidl\", \"objidlbase\", \"ocidl\", \"ole2\", \"oleauto\", \"olectl\", \"oleidl\", \"opmapi\", \"pdh\", \"perflib\", \"physicalmonitorenumerationapi\", \"playsoundapi\", \"portabledevice\", \"portabledeviceapi\", \"portabledevicetypes\", \"powerbase\", \"powersetting\", \"powrprof\", \"processenv\", \"processsnapshot\", \"processthreadsapi\", \"processtopologyapi\", \"profileapi\", \"propidl\", \"propkey\", \"propkeydef\", \"propsys\", \"prsht\", \"psapi\", \"qos\", \"realtimeapiset\", \"reason\", \"restartmanager\", \"restrictederrorinfo\", \"rmxfguid\", \"roapi\", \"robuffer\", \"roerrorapi\", \"rpc\", \"rpcdce\", \"rpcndr\", \"rtinfo\", \"sapi\", \"sapi51\", \"sapi53\", \"sapiddk\", \"sapiddk51\", \"schannel\", \"sddl\", \"securityappcontainer\", \"securitybaseapi\", \"servprov\", \"setupapi\", \"shellapi\", \"shellscalingapi\", \"shlobj\", \"shobjidl\", \"shobjidl_core\", \"shtypes\", \"softpub\", \"spapidef\", \"spellcheck\", \"sporder\", \"sql\", \"sqlext\", \"sqltypes\", \"sqlucode\", \"sspi\", \"std\", \"stralign\", \"stringapiset\", \"strmif\", \"subauth\", \"synchapi\", \"sysinfoapi\", \"systemtopologyapi\", \"taskschd\", \"tcpestats\", \"tcpmib\", \"textstor\", \"threadpoolapiset\", \"threadpoollegacyapiset\", \"timeapi\", \"timezoneapi\", \"tlhelp32\", \"transportsettingcommon\", \"tvout\", \"udpmib\", \"unknwnbase\", \"urlhist\", \"urlmon\", \"usb\", \"usbioctl\", \"usbiodef\", \"usbscan\", \"usbspec\", \"userenv\", \"usp10\", \"utilapiset\", \"uxtheme\", \"vadefs\", \"vcruntime\", \"vsbackup\", \"vss\", \"vsserror\", \"vswriter\", \"wbemads\", \"wbemcli\", \"wbemdisp\", \"wbemprov\", \"wbemtran\", \"wct\", \"werapi\", \"winbase\", \"wincodec\", \"wincodecsdk\", \"wincon\", \"wincontypes\", \"wincred\", \"wincrypt\", \"windef\", \"windot11\", \"windowsceip\", \"windowsx\", \"winefs\", \"winerror\", \"winevt\", \"wingdi\", \"winhttp\", \"wininet\", \"winineti\", \"winioctl\", \"winnetwk\", \"winnls\", \"winnt\", \"winreg\", \"winsafer\", \"winscard\", \"winsmcrd\", \"winsock2\", \"winspool\", \"winstring\", \"winsvc\", \"wintrust\", \"winusb\", \"winusbio\", \"winuser\", \"winver\", \"wlanapi\", \"wlanihv\", \"wlanihvtypes\", \"wlantypes\", \"wlclient\", \"wmistr\", \"wnnc\", \"wow64apiset\", \"wpdmtpextensions\", \"ws2bth\", \"ws2def\", \"ws2ipdef\", \"ws2spi\", \"ws2tcpip\", \"wtsapi32\", \"wtypes\", \"wtypesbase\", \"xinput\"))",
    "-C",
    "metadata=aefb0aee894e0ada",
    "-C",
    "extra-filename=-1353e99ede147387",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:47:24.913129+00:00",
  "end_time": "2026-07-13T14:47:25.056138+00:00",
  "start_unix_nanos": 1783954044913128700,
  "end_unix_nanos": 1783954045056137700,
  "crate_name": "winapi",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:47:27.118631+00:00",
  "crate": "winapi",
  "version": "0.3.9",
  "duration_seconds": 31.869228499941528,
  "trace_record_count": 7,
  "trace_owner_summary": {
    "owner_package_count": 3,
    "owner_packages": [
      {
        "crate": "winapi-x86_64-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "winapi-i686-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "winapi",
        "version": "0.3.9",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
          "name": "winapi",
          "version": "0.3.9",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
          "name": "winapi-i686-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-i686-pc-windows-gnu-0.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-i686-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
          "name": "winapi-x86_64-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15976,
      "ppid": 16244,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "cargo_pkg_name": "winapi",
      "cargo_pkg_version": "0.3.9",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 15976,
      "ppid": 16244,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "_owner": {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-11652-1783954038803\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\rustcI3SMDO\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000148       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000198       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001d0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002c8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000148       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140028148     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000198       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140028198     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400281b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400281d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400281e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400281f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140028288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400282a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002b0       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400282b0     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002c8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\0002:000002c8       \\177ntdll_NULL_THUNK_DATA  00000001400282c8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-link-link-15976-1783954044323055300.map",
      "pid": 15976,
      "ppid": 16244,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\.tmp\\native-trace-link-link-15976-1783954044323055300.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3tallu1a/src/winapi-0.3.9",
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
      "raw_event_count": 579,
      "parsed_event_count": 579,
      "parse_error_count": 0,
      "command_line_event_count": 579,
      "build_script_root_event_count": 14,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 49,
      "dropped_event_count": 270
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 8900,
      "ppid": 6472,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:47:24.894387+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42\\build-script-build.exe",
      "root_cargo_pid": 6124,
      "build_script_root_pid": 8900,
      "build_script_related": true,
      "build_script_target_dir": "winapi-15abf94f880dee42"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winapi:0.3.9:2896",
      "root_process_pid": 6124,
      "pid": 15940,
      "ppid": 15576,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
      "time": "2026-07-13T14:47:18.998905+00:00",
      "end_time": "2026-07-13T14:47:19.018018+00:00",
      "start_unix_nanos": 1783954038998905500,
      "end_unix_nanos": 1783954039018018000,
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
      "run_id": "winapi:0.3.9:2896",
      "root_process_pid": 6124,
      "pid": 16288,
      "ppid": 15576,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
      "time": "2026-07-13T14:47:19.024415+00:00",
      "end_time": "2026-07-13T14:47:19.046258+00:00",
      "start_unix_nanos": 1783954039024414800,
      "end_unix_nanos": 1783954039046258200,
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
      "run_id": "winapi:0.3.9:2896",
      "root_process_pid": 6124,
      "pid": 12692,
      "ppid": 15576,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
      "time": "2026-07-13T14:47:23.660790+00:00",
      "end_time": "2026-07-13T14:47:23.680681+00:00",
      "start_unix_nanos": 1783954043660790100,
      "end_unix_nanos": 1783954043680681400,
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
      "run_id": "winapi:0.3.9:2896",
      "root_process_pid": 6124,
      "pid": 372,
      "ppid": 6472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
      "time": "2026-07-13T14:47:23.786823+00:00",
      "end_time": "2026-07-13T14:47:23.807054+00:00",
      "start_unix_nanos": 1783954043786822900,
      "end_unix_nanos": 1783954043807054300,
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
      "run_id": "winapi:0.3.9:2896",
      "root_process_pid": 6124,
      "pid": 4372,
      "ppid": 6472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
      "time": "2026-07-13T14:47:23.813698+00:00",
      "end_time": "2026-07-13T14:47:23.836656+00:00",
      "start_unix_nanos": 1783954043813697800,
      "end_unix_nanos": 1783954043836656400,
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
      "run_id": "winapi:0.3.9:2896",
      "root_process_pid": 6124,
      "pid": 15076,
      "ppid": 6472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
      "time": "2026-07-13T14:47:23.866349+00:00",
      "end_time": "2026-07-13T14:47:23.892097+00:00",
      "start_unix_nanos": 1783954043866348600,
      "end_unix_nanos": 1783954043892096700,
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
      "run_id": "winapi:0.3.9:2896",
      "root_process_pid": 6124,
      "pid": 3768,
      "ppid": 6472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
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
        "cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\", \"bcrypt\", \"bits\", \"bits10_1\", \"bits1_5\", \"bits2_0\", \"bits2_5\", \"bits3_0\", \"bits4_0\", \"bits5_0\", \"bitscfg\", \"bitsmsg\", \"bluetoothapis\", \"bluetoothleapis\", \"bthdef\", \"bthioctl\", \"bthledef\", \"bthsdpdef\", \"bugcodes\", \"cderr\", \"cfg\", \"cfgmgr32\", \"cguid\", \"combaseapi\", \"coml2api\", \"commapi\", \"commctrl\", \"commdlg\", \"commoncontrols\", \"consoleapi\", \"corecrt\", \"corsym\", \"d2d1\", \"d2d1_1\", \"d2d1_2\", \"d2d1_3\", \"d2d1effectauthor\", \"d2d1effects\", \"d2d1effects_1\", \"d2d1effects_2\", \"d2d1svg\", \"d2dbasetypes\", \"d3d\", \"d3d10\", \"d3d10_1\", \"d3d10_1shader\", \"d3d10effect\", \"d3d10misc\", \"d3d10sdklayers\", \"d3d10shader\", \"d3d11\", \"d3d11_1\", \"d3d11_2\", \"d3d11_3\", \"d3d11_4\", \"d3d11on12\", \"d3d11sdklayers\", \"d3d11shader\", \"d3d11tokenizedprogramformat\", \"d3d12\", \"d3d12sdklayers\", \"d3d12shader\", \"d3d9\", \"d3d9caps\", \"d3d9types\", \"d3dcommon\", \"d3dcompiler\", \"d3dcsx\", \"d3dkmdt\", \"d3dkmthk\", \"d3dukmdt\", \"d3dx10core\", \"d3dx10math\", \"d3dx10mesh\", \"datetimeapi\", \"davclnt\", \"dbghelp\", \"dbt\", \"dcommon\", \"dcomp\", \"dcompanimation\", \"dcomptypes\", \"dde\", \"ddraw\", \"ddrawi\", \"ddrawint\", \"debug\", \"debugapi\", \"devguid\", \"devicetopology\", \"devpkey\", \"devpropdef\", \"dinput\", \"dinputd\", \"dispex\", \"dmksctl\", \"dmusicc\", \"docobj\", \"documenttarget\", \"dot1x\", \"dpa_dsa\", \"dpapi\", \"dsgetdc\", \"dsound\", \"dsrole\", \"dvp\", \"dwmapi\", \"dwrite\", \"dwrite_1\", \"dwrite_2\", \"dwrite_3\", \"dxdiag\", \"dxfile\", \"dxgi\", \"dxgi1_2\", \"dxgi1_3\", \"dxgi1_4\", \"dxgi1_5\", \"dxgi1_6\", \"dxgidebug\", \"dxgiformat\", \"dxgitype\", \"dxva2api\", \"dxvahd\", \"eaptypes\", \"enclaveapi\", \"endpointvolume\", \"errhandlingapi\", \"everything\", \"evntcons\", \"evntprov\", \"evntrace\", \"excpt\", \"exdisp\", \"fibersapi\", \"fileapi\", \"functiondiscoverykeys_devpkey\", \"gl-gl\", \"guiddef\", \"handleapi\", \"heapapi\", \"hidclass\", \"hidpi\", \"hidsdi\", \"hidusage\", \"highlevelmonitorconfigurationapi\", \"hstring\", \"http\", \"ifdef\", \"ifmib\", \"imm\", \"impl-debug\", \"impl-default\", \"in6addr\", \"inaddr\", \"inspectable\", \"interlockedapi\", \"intsafe\", \"ioapiset\", \"ipexport\", \"iphlpapi\", \"ipifcons\", \"ipmib\", \"iprtrmib\", \"iptypes\", \"jobapi\", \"jobapi2\", \"knownfolders\", \"ks\", \"ksmedia\", \"ktmtypes\", \"ktmw32\", \"l2cmn\", \"libloaderapi\", \"limits\", \"lmaccess\", \"lmalert\", \"lmapibuf\", \"lmat\", \"lmcons\", \"lmdfs\", \"lmerrlog\", \"lmjoin\", \"lmmsg\", \"lmremutl\", \"lmrepl\", \"lmserver\", \"lmshare\", \"lmstats\", \"lmsvc\", \"lmuse\", \"lmwksta\", \"lowlevelmonitorconfigurationapi\", \"lsalookup\", \"memoryapi\", \"minschannel\", \"minwinbase\", \"minwindef\", \"mmdeviceapi\", \"mmeapi\", \"mmreg\", \"mmsystem\", \"mprapidef\", \"msaatext\", \"mscat\", \"mschapp\", \"mssip\", \"mstcpip\", \"mswsock\", \"mswsockdef\", \"namedpipeapi\", \"namespaceapi\", \"nb30\", \"ncrypt\", \"netioapi\", \"nldef\", \"ntddndis\", \"ntddscsi\", \"ntddser\", \"ntdef\", \"ntlsa\", \"ntsecapi\", \"ntstatus\", \"oaidl\", \"objbase\", \"objidl\", \"objidlbase\", \"ocidl\", \"ole2\", \"oleauto\", \"olectl\", \"oleidl\", \"opmapi\", \"pdh\", \"perflib\", \"physicalmonitorenumerationapi\", \"playsoundapi\", \"portabledevice\", \"portabledeviceapi\", \"portabledevicetypes\", \"powerbase\", \"powersetting\", \"powrprof\", \"processenv\", \"processsnapshot\", \"processthreadsapi\", \"processtopologyapi\", \"profileapi\", \"propidl\", \"propkey\", \"propkeydef\", \"propsys\", \"prsht\", \"psapi\", \"qos\", \"realtimeapiset\", \"reason\", \"restartmanager\", \"restrictederrorinfo\", \"rmxfguid\", \"roapi\", \"robuffer\", \"roerrorapi\", \"rpc\", \"rpcdce\", \"rpcndr\", \"rtinfo\", \"sapi\", \"sapi51\", \"sapi53\", \"sapiddk\", \"sapiddk51\", \"schannel\", \"sddl\", \"securityappcontainer\", \"securitybaseapi\", \"servprov\", \"setupapi\", \"shellapi\", \"shellscalingapi\", \"shlobj\", \"shobjidl\", \"shobjidl_core\", \"shtypes\", \"softpub\", \"spapidef\", \"spellcheck\", \"sporder\", \"sql\", \"sqlext\", \"sqltypes\", \"sqlucode\", \"sspi\", \"std\", \"stralign\", \"stringapiset\", \"strmif\", \"subauth\", \"synchapi\", \"sysinfoapi\", \"systemtopologyapi\", \"taskschd\", \"tcpestats\", \"tcpmib\", \"textstor\", \"threadpoolapiset\", \"threadpoollegacyapiset\", \"timeapi\", \"timezoneapi\", \"tlhelp32\", \"transportsettingcommon\", \"tvout\", \"udpmib\", \"unknwnbase\", \"urlhist\", \"urlmon\", \"usb\", \"usbioctl\", \"usbiodef\", \"usbscan\", \"usbspec\", \"userenv\", \"usp10\", \"utilapiset\", \"uxtheme\", \"vadefs\", \"vcruntime\", \"vsbackup\", \"vss\", \"vsserror\", \"vswriter\", \"wbemads\", \"wbemcli\", \"wbemdisp\", \"wbemprov\", \"wbemtran\", \"wct\", \"werapi\", \"winbase\", \"wincodec\", \"wincodecsdk\", \"wincon\", \"wincontypes\", \"wincred\", \"wincrypt\", \"windef\", \"windot11\", \"windowsceip\", \"windowsx\", \"winefs\", \"winerror\", \"winevt\", \"wingdi\", \"winhttp\", \"wininet\", \"winineti\", \"winioctl\", \"winnetwk\", \"winnls\", \"winnt\", \"winreg\", \"winsafer\", \"winscard\", \"winsmcrd\", \"winsock2\", \"winspool\", \"winstring\", \"winsvc\", \"wintrust\", \"winusb\", \"winusbio\", \"winuser\", \"winver\", \"wlanapi\", \"wlanihv\", \"wlanihvtypes\", \"wlantypes\", \"wlclient\", \"wmistr\", \"wnnc\", \"wow64apiset\", \"wpdmtpextensions\", \"ws2bth\", \"ws2def\", \"ws2ipdef\", \"ws2spi\", \"ws2tcpip\", \"wtsapi32\", \"wtypes\", \"wtypesbase\", \"xinput\"))",
        "-C",
        "metadata=16b2880941ffbc77",
        "-C",
        "extra-filename=-15abf94f880dee42",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"accctrl\\\", \\\"aclapi\\\", \\\"activation\\\", \\\"adhoc\\\", \\\"appmgmt\\\", \\\"audioclient\\\", \\\"audiosessiontypes\\\", \\\"avrt\\\", \\\"basetsd\\\", \\\"bcrypt\\\", \\\"bits\\\", \\\"bits10_1\\\", \\\"bits1_5\\\", \\\"bits2_0\\\", \\\"bits2_5\\\", \\\"bits3_0\\\", \\\"bits4_0\\\", \\\"bits5_0\\\", \\\"bitscfg\\\", \\\"bitsmsg\\\", \\\"bluetoothapis\\\", \\\"bluetoothleapis\\\", \\\"bthdef\\\", \\\"bthioctl\\\", \\\"bthledef\\\", \\\"bthsdpdef\\\", \\\"bugcodes\\\", \\\"cderr\\\", \\\"cfg\\\", \\\"cfgmgr32\\\", \\\"cguid\\\", \\\"combaseapi\\\", \\\"coml2api\\\", \\\"commapi\\\", \\\"commctrl\\\", \\\"commdlg\\\", \\\"commoncontrols\\\", \\\"consoleapi\\\", \\\"corecrt\\\", \\\"corsym\\\", \\\"d2d1\\\", \\\"d2d1_1\\\", \\\"d2d1_2\\\", \\\"d2d1_3\\\", \\\"d2d1effectauthor\\\", \\\"d2d1effects\\\", \\\"d2d1effects_1\\\", \\\"d2d1effects_2\\\", \\\"d2d1svg\\\", \\\"d2dbasetypes\\\", \\\"d3d\\\", \\\"d3d10\\\", \\\"d3d10_1\\\", \\\"d3d10_1shader\\\", \\\"d3d10effect\\\", \\\"d3d10misc\\\", \\\"d3d10sdklayers\\\", \\\"d3d10shader\\\", \\\"d3d11\\\", \\\"d3d11_1\\\", \\\"d3d11_2\\\", \\\"d3d11_3\\\", \\\"d3d11_4\\\", \\\"d3d11on12\\\", \\\"d3d11sdklayers\\\", \\\"d3d11shader\\\", \\\"d3d11tokenizedprogramformat\\\", \\\"d3d12\\\", \\\"d3d12sdklayers\\\", \\\"d3d12shader\\\", \\\"d3d9\\\", \\\"d3d9caps\\\", \\\"d3d9types\\\", \\\"d3dcommon\\\", \\\"d3dcompiler\\\", \\\"d3dcsx\\\", \\\"d3dkmdt\\\", \\\"d3dkmthk\\\", \\\"d3dukmdt\\\", \\\"d3dx10core\\\", \\\"d3dx10math\\\", \\\"d3dx10mesh\\\", \\\"datetimeapi\\\", \\\"davclnt\\\", \\\"dbghelp\\\", \\\"dbt\\\", \\\"dcommon\\\", \\\"dcomp\\\", \\\"dcompanimation\\\", \\\"dcomptypes\\\", \\\"dde\\\", \\\"ddraw\\\", \\\"ddrawi\\\", \\\"ddrawint\\\", \\\"debug\\\", \\\"debugapi\\\", \\\"devguid\\\", \\\"devicetopology\\\", \\\"devpkey\\\", \\\"devpropdef\\\", \\\"dinput\\\", \\\"dinputd\\\", \\\"dispex\\\", \\\"dmksctl\\\", \\\"dmusicc\\\", \\\"docobj\\\", \\\"documenttarget\\\", \\\"dot1x\\\", \\\"dpa_dsa\\\", \\\"dpapi\\\", \\\"dsgetdc\\\", \\\"dsound\\\", \\\"dsrole\\\", \\\"dvp\\\", \\\"dwmapi\\\", \\\"dwrite\\\", \\\"dwrite_1\\\", \\\"dwrite_2\\\", \\\"dwrite_3\\\", \\\"dxdiag\\\", \\\"dxfile\\\", \\\"dxgi\\\", \\\"dxgi1_2\\\", \\\"dxgi1_3\\\", \\\"dxgi1_4\\\", \\\"dxgi1_5\\\", \\\"dxgi1_6\\\", \\\"dxgidebug\\\", \\\"dxgiformat\\\", \\\"dxgitype\\\", \\\"dxva2api\\\", \\\"dxvahd\\\", \\\"eaptypes\\\", \\\"enclaveapi\\\", \\\"endpointvolume\\\", \\\"errhandlingapi\\\", \\\"everything\\\", \\\"evntcons\\\", \\\"evntprov\\\", \\\"evntrace\\\", \\\"excpt\\\", \\\"exdisp\\\", \\\"fibersapi\\\", \\\"fileapi\\\", \\\"functiondiscoverykeys_devpkey\\\", \\\"gl-gl\\\", \\\"guiddef\\\", \\\"handleapi\\\", \\\"heapapi\\\", \\\"hidclass\\\", \\\"hidpi\\\", \\\"hidsdi\\\", \\\"hidusage\\\", \\\"highlevelmonitorconfigurationapi\\\", \\\"hstring\\\", \\\"http\\\", \\\"ifdef\\\", \\\"ifmib\\\", \\\"imm\\\", \\\"impl-debug\\\", \\\"impl-default\\\", \\\"in6addr\\\", \\\"inaddr\\\", \\\"inspectable\\\", \\\"interlockedapi\\\", \\\"intsafe\\\", \\\"ioapiset\\\", \\\"ipexport\\\", \\\"iphlpapi\\\", \\\"ipifcons\\\", \\\"ipmib\\\", \\\"iprtrmib\\\", \\\"iptypes\\\", \\\"jobapi\\\", \\\"jobapi2\\\", \\\"knownfolders\\\", \\\"ks\\\", \\\"ksmedia\\\", \\\"ktmtypes\\\", \\\"ktmw32\\\", \\\"l2cmn\\\", \\\"libloaderapi\\\", \\\"limits\\\", \\\"lmaccess\\\", \\\"lmalert\\\", \\\"lmapibuf\\\", \\\"lmat\\\", \\\"lmcons\\\", \\\"lmdfs\\\", \\\"lmerrlog\\\", \\\"lmjoin\\\", \\\"lmmsg\\\", \\\"lmremutl\\\", \\\"lmrepl\\\", \\\"lmserver\\\", \\\"lmshare\\\", \\\"lmstats\\\", \\\"lmsvc\\\", \\\"lmuse\\\", \\\"lmwksta\\\", \\\"lowlevelmonitorconfigurationapi\\\", \\\"lsalookup\\\", \\\"memoryapi\\\", \\\"minschannel\\\", \\\"minwinbase\\\", \\\"minwindef\\\", \\\"mmdeviceapi\\\", \\\"mmeapi\\\", \\\"mmreg\\\", \\\"mmsystem\\\", \\\"mprapidef\\\", \\\"msaatext\\\", \\\"mscat\\\", \\\"mschapp\\\", \\\"mssip\\\", \\\"mstcpip\\\", \\\"mswsock\\\", \\\"mswsockdef\\\", \\\"namedpipeapi\\\", \\\"namespaceapi\\\", \\\"nb30\\\", \\\"ncrypt\\\", \\\"netioapi\\\", \\\"nldef\\\", \\\"ntddndis\\\", \\\"ntddscsi\\\", \\\"ntddser\\\", \\\"ntdef\\\", \\\"ntlsa\\\", \\\"ntsecapi\\\", \\\"ntstatus\\\", \\\"oaidl\\\", \\\"objbase\\\", \\\"objidl\\\", \\\"objidlbase\\\", \\\"ocidl\\\", \\\"ole2\\\", \\\"oleauto\\\", \\\"olectl\\\", \\\"oleidl\\\", \\\"opmapi\\\", \\\"pdh\\\", \\\"perflib\\\", \\\"physicalmonitorenumerationapi\\\", \\\"playsoundapi\\\", \\\"portabledevice\\\", \\\"portabledeviceapi\\\", \\\"portabledevicetypes\\\", \\\"powerbase\\\", \\\"powersetting\\\", \\\"powrprof\\\", \\\"processenv\\\", \\\"processsnapshot\\\", \\\"processthreadsapi\\\", \\\"processtopologyapi\\\", \\\"profileapi\\\", \\\"propidl\\\", \\\"propkey\\\", \\\"propkeydef\\\", \\\"propsys\\\", \\\"prsht\\\", \\\"psapi\\\", \\\"qos\\\", \\\"realtimeapiset\\\", \\\"reason\\\", \\\"restartmanager\\\", \\\"restrictederrorinfo\\\", \\\"rmxfguid\\\", \\\"roapi\\\", \\\"robuffer\\\", \\\"roerrorapi\\\", \\\"rpc\\\", \\\"rpcdce\\\", \\\"rpcndr\\\", \\\"rtinfo\\\", \\\"sapi\\\", \\\"sapi51\\\", \\\"sapi53\\\", \\\"sapiddk\\\", \\\"sapiddk51\\\", \\\"schannel\\\", \\\"sddl\\\", \\\"securityappcontainer\\\", \\\"securitybaseapi\\\", \\\"servprov\\\", \\\"setupapi\\\", \\\"shellapi\\\", \\\"shellscalingapi\\\", \\\"shlobj\\\", \\\"shobjidl\\\", \\\"shobjidl_core\\\", \\\"shtypes\\\", \\\"softpub\\\", \\\"spapidef\\\", \\\"spellcheck\\\", \\\"sporder\\\", \\\"sql\\\", \\\"sqlext\\\", \\\"sqltypes\\\", \\\"sqlucode\\\", \\\"sspi\\\", \\\"std\\\", \\\"stralign\\\", \\\"stringapiset\\\", \\\"strmif\\\", \\\"subauth\\\", \\\"synchapi\\\", \\\"sysinfoapi\\\", \\\"systemtopologyapi\\\", \\\"taskschd\\\", \\\"tcpestats\\\", \\\"tcpmib\\\", \\\"textstor\\\", \\\"threadpoolapiset\\\", \\\"threadpoollegacyapiset\\\", \\\"timeapi\\\", \\\"timezoneapi\\\", \\\"tlhelp32\\\", \\\"transportsettingcommon\\\", \\\"tvout\\\", \\\"udpmib\\\", \\\"unknwnbase\\\", \\\"urlhist\\\", \\\"urlmon\\\", \\\"usb\\\", \\\"usbioctl\\\", \\\"usbiodef\\\", \\\"usbscan\\\", \\\"usbspec\\\", \\\"userenv\\\", \\\"usp10\\\", \\\"utilapiset\\\", \\\"uxtheme\\\", \\\"vadefs\\\", \\\"vcruntime\\\", \\\"vsbackup\\\", \\\"vss\\\", \\\"vsserror\\\", \\\"vswriter\\\", \\\"wbemads\\\", \\\"wbemcli\\\", \\\"wbemdisp\\\", \\\"wbemprov\\\", \\\"wbemtran\\\", \\\"wct\\\", \\\"werapi\\\", \\\"winbase\\\", \\\"wincodec\\\", \\\"wincodecsdk\\\", \\\"wincon\\\", \\\"wincontypes\\\", \\\"wincred\\\", \\\"wincrypt\\\", \\\"windef\\\", \\\"windot11\\\", \\\"windowsceip\\\", \\\"windowsx\\\", \\\"winefs\\\", \\\"winerror\\\", \\\"winevt\\\", \\\"wingdi\\\", \\\"winhttp\\\", \\\"wininet\\\", \\\"winineti\\\", \\\"winioctl\\\", \\\"winnetwk\\\", \\\"winnls\\\", \\\"winnt\\\", \\\"winreg\\\", \\\"winsafer\\\", \\\"winscard\\\", \\\"winsmcrd\\\", \\\"winsock2\\\", \\\"winspool\\\", \\\"winstring\\\", \\\"winsvc\\\", \\\"wintrust\\\", \\\"winusb\\\", \\\"winusbio\\\", \\\"winuser\\\", \\\"winver\\\", \\\"wlanapi\\\", \\\"wlanihv\\\", \\\"wlanihvtypes\\\", \\\"wlantypes\\\", \\\"wlclient\\\", \\\"wmistr\\\", \\\"wnnc\\\", \\\"wow64apiset\\\", \\\"wpdmtpextensions\\\", \\\"ws2bth\\\", \\\"ws2def\\\", \\\"ws2ipdef\\\", \\\"ws2spi\\\", \\\"ws2tcpip\\\", \\\"wtsapi32\\\", \\\"wtypes\\\", \\\"wtypesbase\\\", \\\"xinput\\\"))\" -C metadata=16b2880941ffbc77 -C extra-filename=-15abf94f880dee42 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps",
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
        "cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\", \"bcrypt\", \"bits\", \"bits10_1\", \"bits1_5\", \"bits2_0\", \"bits2_5\", \"bits3_0\", \"bits4_0\", \"bits5_0\", \"bitscfg\", \"bitsmsg\", \"bluetoothapis\", \"bluetoothleapis\", \"bthdef\", \"bthioctl\", \"bthledef\", \"bthsdpdef\", \"bugcodes\", \"cderr\", \"cfg\", \"cfgmgr32\", \"cguid\", \"combaseapi\", \"coml2api\", \"commapi\", \"commctrl\", \"commdlg\", \"commoncontrols\", \"consoleapi\", \"corecrt\", \"corsym\", \"d2d1\", \"d2d1_1\", \"d2d1_2\", \"d2d1_3\", \"d2d1effectauthor\", \"d2d1effects\", \"d2d1effects_1\", \"d2d1effects_2\", \"d2d1svg\", \"d2dbasetypes\", \"d3d\", \"d3d10\", \"d3d10_1\", \"d3d10_1shader\", \"d3d10effect\", \"d3d10misc\", \"d3d10sdklayers\", \"d3d10shader\", \"d3d11\", \"d3d11_1\", \"d3d11_2\", \"d3d11_3\", \"d3d11_4\", \"d3d11on12\", \"d3d11sdklayers\", \"d3d11shader\", \"d3d11tokenizedprogramformat\", \"d3d12\", \"d3d12sdklayers\", \"d3d12shader\", \"d3d9\", \"d3d9caps\", \"d3d9types\", \"d3dcommon\", \"d3dcompiler\", \"d3dcsx\", \"d3dkmdt\", \"d3dkmthk\", \"d3dukmdt\", \"d3dx10core\", \"d3dx10math\", \"d3dx10mesh\", \"datetimeapi\", \"davclnt\", \"dbghelp\", \"dbt\", \"dcommon\", \"dcomp\", \"dcompanimation\", \"dcomptypes\", \"dde\", \"ddraw\", \"ddrawi\", \"ddrawint\", \"debug\", \"debugapi\", \"devguid\", \"devicetopology\", \"devpkey\", \"devpropdef\", \"dinput\", \"dinputd\", \"dispex\", \"dmksctl\", \"dmusicc\", \"docobj\", \"documenttarget\", \"dot1x\", \"dpa_dsa\", \"dpapi\", \"dsgetdc\", \"dsound\", \"dsrole\", \"dvp\", \"dwmapi\", \"dwrite\", \"dwrite_1\", \"dwrite_2\", \"dwrite_3\", \"dxdiag\", \"dxfile\", \"dxgi\", \"dxgi1_2\", \"dxgi1_3\", \"dxgi1_4\", \"dxgi1_5\", \"dxgi1_6\", \"dxgidebug\", \"dxgiformat\", \"dxgitype\", \"dxva2api\", \"dxvahd\", \"eaptypes\", \"enclaveapi\", \"endpointvolume\", \"errhandlingapi\", \"everything\", \"evntcons\", \"evntprov\", \"evntrace\", \"excpt\", \"exdisp\", \"fibersapi\", \"fileapi\", \"functiondiscoverykeys_devpkey\", \"gl-gl\", \"guiddef\", \"handleapi\", \"heapapi\", \"hidclass\", \"hidpi\", \"hidsdi\", \"hidusage\", \"highlevelmonitorconfigurationapi\", \"hstring\", \"http\", \"ifdef\", \"ifmib\", \"imm\", \"impl-debug\", \"impl-default\", \"in6addr\", \"inaddr\", \"inspectable\", \"interlockedapi\", \"intsafe\", \"ioapiset\", \"ipexport\", \"iphlpapi\", \"ipifcons\", \"ipmib\", \"iprtrmib\", \"iptypes\", \"jobapi\", \"jobapi2\", \"knownfolders\", \"ks\", \"ksmedia\", \"ktmtypes\", \"ktmw32\", \"l2cmn\", \"libloaderapi\", \"limits\", \"lmaccess\", \"lmalert\", \"lmapibuf\", \"lmat\", \"lmcons\", \"lmdfs\", \"lmerrlog\", \"lmjoin\", \"lmmsg\", \"lmremutl\", \"lmrepl\", \"lmserver\", \"lmshare\", \"lmstats\", \"lmsvc\", \"lmuse\", \"lmwksta\", \"lowlevelmonitorconfigurationapi\", \"lsalookup\", \"memoryapi\", \"minschannel\", \"minwinbase\", \"minwindef\", \"mmdeviceapi\", \"mmeapi\", \"mmreg\", \"mmsystem\", \"mprapidef\", \"msaatext\", \"mscat\", \"mschapp\", \"mssip\", \"mstcpip\", \"mswsock\", \"mswsockdef\", \"namedpipeapi\", \"namespaceapi\", \"nb30\", \"ncrypt\", \"netioapi\", \"nldef\", \"ntddndis\", \"ntddscsi\", \"ntddser\", \"ntdef\", \"ntlsa\", \"ntsecapi\", \"ntstatus\", \"oaidl\", \"objbase\", \"objidl\", \"objidlbase\", \"ocidl\", \"ole2\", \"oleauto\", \"olectl\", \"oleidl\", \"opmapi\", \"pdh\", \"perflib\", \"physicalmonitorenumerationapi\", \"playsoundapi\", \"portabledevice\", \"portabledeviceapi\", \"portabledevicetypes\", \"powerbase\", \"powersetting\", \"powrprof\", \"processenv\", \"processsnapshot\", \"processthreadsapi\", \"processtopologyapi\", \"profileapi\", \"propidl\", \"propkey\", \"propkeydef\", \"propsys\", \"prsht\", \"psapi\", \"qos\", \"realtimeapiset\", \"reason\", \"restartmanager\", \"restrictederrorinfo\", \"rmxfguid\", \"roapi\", \"robuffer\", \"roerrorapi\", \"rpc\", \"rpcdce\", \"rpcndr\", \"rtinfo\", \"sapi\", \"sapi51\", \"sapi53\", \"sapiddk\", \"sapiddk51\", \"schannel\", \"sddl\", \"securityappcontainer\", \"securitybaseapi\", \"servprov\", \"setupapi\", \"shellapi\", \"shellscalingapi\", \"shlobj\", \"shobjidl\", \"shobjidl_core\", \"shtypes\", \"softpub\", \"spapidef\", \"spellcheck\", \"sporder\", \"sql\", \"sqlext\", \"sqltypes\", \"sqlucode\", \"sspi\", \"std\", \"stralign\", \"stringapiset\", \"strmif\", \"subauth\", \"synchapi\", \"sysinfoapi\", \"systemtopologyapi\", \"taskschd\", \"tcpestats\", \"tcpmib\", \"textstor\", \"threadpoolapiset\", \"threadpoollegacyapiset\", \"timeapi\", \"timezoneapi\", \"tlhelp32\", \"transportsettingcommon\", \"tvout\", \"udpmib\", \"unknwnbase\", \"urlhist\", \"urlmon\", \"usb\", \"usbioctl\", \"usbiodef\", \"usbscan\", \"usbspec\", \"userenv\", \"usp10\", \"utilapiset\", \"uxtheme\", \"vadefs\", \"vcruntime\", \"vsbackup\", \"vss\", \"vsserror\", \"vswriter\", \"wbemads\", \"wbemcli\", \"wbemdisp\", \"wbemprov\", \"wbemtran\", \"wct\", \"werapi\", \"winbase\", \"wincodec\", \"wincodecsdk\", \"wincon\", \"wincontypes\", \"wincred\", \"wincrypt\", \"windef\", \"windot11\", \"windowsceip\", \"windowsx\", \"winefs\", \"winerror\", \"winevt\", \"wingdi\", \"winhttp\", \"wininet\", \"winineti\", \"winioctl\", \"winnetwk\", \"winnls\", \"winnt\", \"winreg\", \"winsafer\", \"winscard\", \"winsmcrd\", \"winsock2\", \"winspool\", \"winstring\", \"winsvc\", \"wintrust\", \"winusb\", \"winusbio\", \"winuser\", \"winver\", \"wlanapi\", \"wlanihv\", \"wlanihvtypes\", \"wlantypes\", \"wlclient\", \"wmistr\", \"wnnc\", \"wow64apiset\", \"wpdmtpextensions\", \"ws2bth\", \"ws2def\", \"ws2ipdef\", \"ws2spi\", \"ws2tcpip\", \"wtsapi32\", \"wtypes\", \"wtypesbase\", \"xinput\"))",
        "-C",
        "metadata=16b2880941ffbc77",
        "-C",
        "extra-filename=-15abf94f880dee42",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:47:23.918979+00:00",
      "end_time": "2026-07-13T14:47:24.810106+00:00",
      "start_unix_nanos": 1783954043918979100,
      "end_unix_nanos": 1783954044810105700,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\build\\winapi-15abf94f880dee42"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winapi:0.3.9:2896",
      "root_process_pid": 6124,
      "pid": 832,
      "ppid": 6472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "winapi",
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
        "cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\", \"bcrypt\", \"bits\", \"bits10_1\", \"bits1_5\", \"bits2_0\", \"bits2_5\", \"bits3_0\", \"bits4_0\", \"bits5_0\", \"bitscfg\", \"bitsmsg\", \"bluetoothapis\", \"bluetoothleapis\", \"bthdef\", \"bthioctl\", \"bthledef\", \"bthsdpdef\", \"bugcodes\", \"cderr\", \"cfg\", \"cfgmgr32\", \"cguid\", \"combaseapi\", \"coml2api\", \"commapi\", \"commctrl\", \"commdlg\", \"commoncontrols\", \"consoleapi\", \"corecrt\", \"corsym\", \"d2d1\", \"d2d1_1\", \"d2d1_2\", \"d2d1_3\", \"d2d1effectauthor\", \"d2d1effects\", \"d2d1effects_1\", \"d2d1effects_2\", \"d2d1svg\", \"d2dbasetypes\", \"d3d\", \"d3d10\", \"d3d10_1\", \"d3d10_1shader\", \"d3d10effect\", \"d3d10misc\", \"d3d10sdklayers\", \"d3d10shader\", \"d3d11\", \"d3d11_1\", \"d3d11_2\", \"d3d11_3\", \"d3d11_4\", \"d3d11on12\", \"d3d11sdklayers\", \"d3d11shader\", \"d3d11tokenizedprogramformat\", \"d3d12\", \"d3d12sdklayers\", \"d3d12shader\", \"d3d9\", \"d3d9caps\", \"d3d9types\", \"d3dcommon\", \"d3dcompiler\", \"d3dcsx\", \"d3dkmdt\", \"d3dkmthk\", \"d3dukmdt\", \"d3dx10core\", \"d3dx10math\", \"d3dx10mesh\", \"datetimeapi\", \"davclnt\", \"dbghelp\", \"dbt\", \"dcommon\", \"dcomp\", \"dcompanimation\", \"dcomptypes\", \"dde\", \"ddraw\", \"ddrawi\", \"ddrawint\", \"debug\", \"debugapi\", \"devguid\", \"devicetopology\", \"devpkey\", \"devpropdef\", \"dinput\", \"dinputd\", \"dispex\", \"dmksctl\", \"dmusicc\", \"docobj\", \"documenttarget\", \"dot1x\", \"dpa_dsa\", \"dpapi\", \"dsgetdc\", \"dsound\", \"dsrole\", \"dvp\", \"dwmapi\", \"dwrite\", \"dwrite_1\", \"dwrite_2\", \"dwrite_3\", \"dxdiag\", \"dxfile\", \"dxgi\", \"dxgi1_2\", \"dxgi1_3\", \"dxgi1_4\", \"dxgi1_5\", \"dxgi1_6\", \"dxgidebug\", \"dxgiformat\", \"dxgitype\", \"dxva2api\", \"dxvahd\", \"eaptypes\", \"enclaveapi\", \"endpointvolume\", \"errhandlingapi\", \"everything\", \"evntcons\", \"evntprov\", \"evntrace\", \"excpt\", \"exdisp\", \"fibersapi\", \"fileapi\", \"functiondiscoverykeys_devpkey\", \"gl-gl\", \"guiddef\", \"handleapi\", \"heapapi\", \"hidclass\", \"hidpi\", \"hidsdi\", \"hidusage\", \"highlevelmonitorconfigurationapi\", \"hstring\", \"http\", \"ifdef\", \"ifmib\", \"imm\", \"impl-debug\", \"impl-default\", \"in6addr\", \"inaddr\", \"inspectable\", \"interlockedapi\", \"intsafe\", \"ioapiset\", \"ipexport\", \"iphlpapi\", \"ipifcons\", \"ipmib\", \"iprtrmib\", \"iptypes\", \"jobapi\", \"jobapi2\", \"knownfolders\", \"ks\", \"ksmedia\", \"ktmtypes\", \"ktmw32\", \"l2cmn\", \"libloaderapi\", \"limits\", \"lmaccess\", \"lmalert\", \"lmapibuf\", \"lmat\", \"lmcons\", \"lmdfs\", \"lmerrlog\", \"lmjoin\", \"lmmsg\", \"lmremutl\", \"lmrepl\", \"lmserver\", \"lmshare\", \"lmstats\", \"lmsvc\", \"lmuse\", \"lmwksta\", \"lowlevelmonitorconfigurationapi\", \"lsalookup\", \"memoryapi\", \"minschannel\", \"minwinbase\", \"minwindef\", \"mmdeviceapi\", \"mmeapi\", \"mmreg\", \"mmsystem\", \"mprapidef\", \"msaatext\", \"mscat\", \"mschapp\", \"mssip\", \"mstcpip\", \"mswsock\", \"mswsockdef\", \"namedpipeapi\", \"namespaceapi\", \"nb30\", \"ncrypt\", \"netioapi\", \"nldef\", \"ntddndis\", \"ntddscsi\", \"ntddser\", \"ntdef\", \"ntlsa\", \"ntsecapi\", \"ntstatus\", \"oaidl\", \"objbase\", \"objidl\", \"objidlbase\", \"ocidl\", \"ole2\", \"oleauto\", \"olectl\", \"oleidl\", \"opmapi\", \"pdh\", \"perflib\", \"physicalmonitorenumerationapi\", \"playsoundapi\", \"portabledevice\", \"portabledeviceapi\", \"portabledevicetypes\", \"powerbase\", \"powersetting\", \"powrprof\", \"processenv\", \"processsnapshot\", \"processthreadsapi\", \"processtopologyapi\", \"profileapi\", \"propidl\", \"propkey\", \"propkeydef\", \"propsys\", \"prsht\", \"psapi\", \"qos\", \"realtimeapiset\", \"reason\", \"restartmanager\", \"restrictederrorinfo\", \"rmxfguid\", \"roapi\", \"robuffer\", \"roerrorapi\", \"rpc\", \"rpcdce\", \"rpcndr\", \"rtinfo\", \"sapi\", \"sapi51\", \"sapi53\", \"sapiddk\", \"sapiddk51\", \"schannel\", \"sddl\", \"securityappcontainer\", \"securitybaseapi\", \"servprov\", \"setupapi\", \"shellapi\", \"shellscalingapi\", \"shlobj\", \"shobjidl\", \"shobjidl_core\", \"shtypes\", \"softpub\", \"spapidef\", \"spellcheck\", \"sporder\", \"sql\", \"sqlext\", \"sqltypes\", \"sqlucode\", \"sspi\", \"std\", \"stralign\", \"stringapiset\", \"strmif\", \"subauth\", \"synchapi\", \"sysinfoapi\", \"systemtopologyapi\", \"taskschd\", \"tcpestats\", \"tcpmib\", \"textstor\", \"threadpoolapiset\", \"threadpoollegacyapiset\", \"timeapi\", \"timezoneapi\", \"tlhelp32\", \"transportsettingcommon\", \"tvout\", \"udpmib\", \"unknwnbase\", \"urlhist\", \"urlmon\", \"usb\", \"usbioctl\", \"usbiodef\", \"usbscan\", \"usbspec\", \"userenv\", \"usp10\", \"utilapiset\", \"uxtheme\", \"vadefs\", \"vcruntime\", \"vsbackup\", \"vss\", \"vsserror\", \"vswriter\", \"wbemads\", \"wbemcli\", \"wbemdisp\", \"wbemprov\", \"wbemtran\", \"wct\", \"werapi\", \"winbase\", \"wincodec\", \"wincodecsdk\", \"wincon\", \"wincontypes\", \"wincred\", \"wincrypt\", \"windef\", \"windot11\", \"windowsceip\", \"windowsx\", \"winefs\", \"winerror\", \"winevt\", \"wingdi\", \"winhttp\", \"wininet\", \"winineti\", \"winioctl\", \"winnetwk\", \"winnls\", \"winnt\", \"winreg\", \"winsafer\", \"winscard\", \"winsmcrd\", \"winsock2\", \"winspool\", \"winstring\", \"winsvc\", \"wintrust\", \"winusb\", \"winusbio\", \"winuser\", \"winver\", \"wlanapi\", \"wlanihv\", \"wlanihvtypes\", \"wlantypes\", \"wlclient\", \"wmistr\", \"wnnc\", \"wow64apiset\", \"wpdmtpextensions\", \"ws2bth\", \"ws2def\", \"ws2ipdef\", \"ws2spi\", \"ws2tcpip\", \"wtsapi32\", \"wtypes\", \"wtypesbase\", \"xinput\"))",
        "-C",
        "metadata=aefb0aee894e0ada",
        "-C",
        "extra-filename=-1353e99ede147387",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name winapi --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"accctrl\\\", \\\"aclapi\\\", \\\"activation\\\", \\\"adhoc\\\", \\\"appmgmt\\\", \\\"audioclient\\\", \\\"audiosessiontypes\\\", \\\"avrt\\\", \\\"basetsd\\\", \\\"bcrypt\\\", \\\"bits\\\", \\\"bits10_1\\\", \\\"bits1_5\\\", \\\"bits2_0\\\", \\\"bits2_5\\\", \\\"bits3_0\\\", \\\"bits4_0\\\", \\\"bits5_0\\\", \\\"bitscfg\\\", \\\"bitsmsg\\\", \\\"bluetoothapis\\\", \\\"bluetoothleapis\\\", \\\"bthdef\\\", \\\"bthioctl\\\", \\\"bthledef\\\", \\\"bthsdpdef\\\", \\\"bugcodes\\\", \\\"cderr\\\", \\\"cfg\\\", \\\"cfgmgr32\\\", \\\"cguid\\\", \\\"combaseapi\\\", \\\"coml2api\\\", \\\"commapi\\\", \\\"commctrl\\\", \\\"commdlg\\\", \\\"commoncontrols\\\", \\\"consoleapi\\\", \\\"corecrt\\\", \\\"corsym\\\", \\\"d2d1\\\", \\\"d2d1_1\\\", \\\"d2d1_2\\\", \\\"d2d1_3\\\", \\\"d2d1effectauthor\\\", \\\"d2d1effects\\\", \\\"d2d1effects_1\\\", \\\"d2d1effects_2\\\", \\\"d2d1svg\\\", \\\"d2dbasetypes\\\", \\\"d3d\\\", \\\"d3d10\\\", \\\"d3d10_1\\\", \\\"d3d10_1shader\\\", \\\"d3d10effect\\\", \\\"d3d10misc\\\", \\\"d3d10sdklayers\\\", \\\"d3d10shader\\\", \\\"d3d11\\\", \\\"d3d11_1\\\", \\\"d3d11_2\\\", \\\"d3d11_3\\\", \\\"d3d11_4\\\", \\\"d3d11on12\\\", \\\"d3d11sdklayers\\\", \\\"d3d11shader\\\", \\\"d3d11tokenizedprogramformat\\\", \\\"d3d12\\\", \\\"d3d12sdklayers\\\", \\\"d3d12shader\\\", \\\"d3d9\\\", \\\"d3d9caps\\\", \\\"d3d9types\\\", \\\"d3dcommon\\\", \\\"d3dcompiler\\\", \\\"d3dcsx\\\", \\\"d3dkmdt\\\", \\\"d3dkmthk\\\", \\\"d3dukmdt\\\", \\\"d3dx10core\\\", \\\"d3dx10math\\\", \\\"d3dx10mesh\\\", \\\"datetimeapi\\\", \\\"davclnt\\\", \\\"dbghelp\\\", \\\"dbt\\\", \\\"dcommon\\\", \\\"dcomp\\\", \\\"dcompanimation\\\", \\\"dcomptypes\\\", \\\"dde\\\", \\\"ddraw\\\", \\\"ddrawi\\\", \\\"ddrawint\\\", \\\"debug\\\", \\\"debugapi\\\", \\\"devguid\\\", \\\"devicetopology\\\", \\\"devpkey\\\", \\\"devpropdef\\\", \\\"dinput\\\", \\\"dinputd\\\", \\\"dispex\\\", \\\"dmksctl\\\", \\\"dmusicc\\\", \\\"docobj\\\", \\\"documenttarget\\\", \\\"dot1x\\\", \\\"dpa_dsa\\\", \\\"dpapi\\\", \\\"dsgetdc\\\", \\\"dsound\\\", \\\"dsrole\\\", \\\"dvp\\\", \\\"dwmapi\\\", \\\"dwrite\\\", \\\"dwrite_1\\\", \\\"dwrite_2\\\", \\\"dwrite_3\\\", \\\"dxdiag\\\", \\\"dxfile\\\", \\\"dxgi\\\", \\\"dxgi1_2\\\", \\\"dxgi1_3\\\", \\\"dxgi1_4\\\", \\\"dxgi1_5\\\", \\\"dxgi1_6\\\", \\\"dxgidebug\\\", \\\"dxgiformat\\\", \\\"dxgitype\\\", \\\"dxva2api\\\", \\\"dxvahd\\\", \\\"eaptypes\\\", \\\"enclaveapi\\\", \\\"endpointvolume\\\", \\\"errhandlingapi\\\", \\\"everything\\\", \\\"evntcons\\\", \\\"evntprov\\\", \\\"evntrace\\\", \\\"excpt\\\", \\\"exdisp\\\", \\\"fibersapi\\\", \\\"fileapi\\\", \\\"functiondiscoverykeys_devpkey\\\", \\\"gl-gl\\\", \\\"guiddef\\\", \\\"handleapi\\\", \\\"heapapi\\\", \\\"hidclass\\\", \\\"hidpi\\\", \\\"hidsdi\\\", \\\"hidusage\\\", \\\"highlevelmonitorconfigurationapi\\\", \\\"hstring\\\", \\\"http\\\", \\\"ifdef\\\", \\\"ifmib\\\", \\\"imm\\\", \\\"impl-debug\\\", \\\"impl-default\\\", \\\"in6addr\\\", \\\"inaddr\\\", \\\"inspectable\\\", \\\"interlockedapi\\\", \\\"intsafe\\\", \\\"ioapiset\\\", \\\"ipexport\\\", \\\"iphlpapi\\\", \\\"ipifcons\\\", \\\"ipmib\\\", \\\"iprtrmib\\\", \\\"iptypes\\\", \\\"jobapi\\\", \\\"jobapi2\\\", \\\"knownfolders\\\", \\\"ks\\\", \\\"ksmedia\\\", \\\"ktmtypes\\\", \\\"ktmw32\\\", \\\"l2cmn\\\", \\\"libloaderapi\\\", \\\"limits\\\", \\\"lmaccess\\\", \\\"lmalert\\\", \\\"lmapibuf\\\", \\\"lmat\\\", \\\"lmcons\\\", \\\"lmdfs\\\", \\\"lmerrlog\\\", \\\"lmjoin\\\", \\\"lmmsg\\\", \\\"lmremutl\\\", \\\"lmrepl\\\", \\\"lmserver\\\", \\\"lmshare\\\", \\\"lmstats\\\", \\\"lmsvc\\\", \\\"lmuse\\\", \\\"lmwksta\\\", \\\"lowlevelmonitorconfigurationapi\\\", \\\"lsalookup\\\", \\\"memoryapi\\\", \\\"minschannel\\\", \\\"minwinbase\\\", \\\"minwindef\\\", \\\"mmdeviceapi\\\", \\\"mmeapi\\\", \\\"mmreg\\\", \\\"mmsystem\\\", \\\"mprapidef\\\", \\\"msaatext\\\", \\\"mscat\\\", \\\"mschapp\\\", \\\"mssip\\\", \\\"mstcpip\\\", \\\"mswsock\\\", \\\"mswsockdef\\\", \\\"namedpipeapi\\\", \\\"namespaceapi\\\", \\\"nb30\\\", \\\"ncrypt\\\", \\\"netioapi\\\", \\\"nldef\\\", \\\"ntddndis\\\", \\\"ntddscsi\\\", \\\"ntddser\\\", \\\"ntdef\\\", \\\"ntlsa\\\", \\\"ntsecapi\\\", \\\"ntstatus\\\", \\\"oaidl\\\", \\\"objbase\\\", \\\"objidl\\\", \\\"objidlbase\\\", \\\"ocidl\\\", \\\"ole2\\\", \\\"oleauto\\\", \\\"olectl\\\", \\\"oleidl\\\", \\\"opmapi\\\", \\\"pdh\\\", \\\"perflib\\\", \\\"physicalmonitorenumerationapi\\\", \\\"playsoundapi\\\", \\\"portabledevice\\\", \\\"portabledeviceapi\\\", \\\"portabledevicetypes\\\", \\\"powerbase\\\", \\\"powersetting\\\", \\\"powrprof\\\", \\\"processenv\\\", \\\"processsnapshot\\\", \\\"processthreadsapi\\\", \\\"processtopologyapi\\\", \\\"profileapi\\\", \\\"propidl\\\", \\\"propkey\\\", \\\"propkeydef\\\", \\\"propsys\\\", \\\"prsht\\\", \\\"psapi\\\", \\\"qos\\\", \\\"realtimeapiset\\\", \\\"reason\\\", \\\"restartmanager\\\", \\\"restrictederrorinfo\\\", \\\"rmxfguid\\\", \\\"roapi\\\", \\\"robuffer\\\", \\\"roerrorapi\\\", \\\"rpc\\\", \\\"rpcdce\\\", \\\"rpcndr\\\", \\\"rtinfo\\\", \\\"sapi\\\", \\\"sapi51\\\", \\\"sapi53\\\", \\\"sapiddk\\\", \\\"sapiddk51\\\", \\\"schannel\\\", \\\"sddl\\\", \\\"securityappcontainer\\\", \\\"securitybaseapi\\\", \\\"servprov\\\", \\\"setupapi\\\", \\\"shellapi\\\", \\\"shellscalingapi\\\", \\\"shlobj\\\", \\\"shobjidl\\\", \\\"shobjidl_core\\\", \\\"shtypes\\\", \\\"softpub\\\", \\\"spapidef\\\", \\\"spellcheck\\\", \\\"sporder\\\", \\\"sql\\\", \\\"sqlext\\\", \\\"sqltypes\\\", \\\"sqlucode\\\", \\\"sspi\\\", \\\"std\\\", \\\"stralign\\\", \\\"stringapiset\\\", \\\"strmif\\\", \\\"subauth\\\", \\\"synchapi\\\", \\\"sysinfoapi\\\", \\\"systemtopologyapi\\\", \\\"taskschd\\\", \\\"tcpestats\\\", \\\"tcpmib\\\", \\\"textstor\\\", \\\"threadpoolapiset\\\", \\\"threadpoollegacyapiset\\\", \\\"timeapi\\\", \\\"timezoneapi\\\", \\\"tlhelp32\\\", \\\"transportsettingcommon\\\", \\\"tvout\\\", \\\"udpmib\\\", \\\"unknwnbase\\\", \\\"urlhist\\\", \\\"urlmon\\\", \\\"usb\\\", \\\"usbioctl\\\", \\\"usbiodef\\\", \\\"usbscan\\\", \\\"usbspec\\\", \\\"userenv\\\", \\\"usp10\\\", \\\"utilapiset\\\", \\\"uxtheme\\\", \\\"vadefs\\\", \\\"vcruntime\\\", \\\"vsbackup\\\", \\\"vss\\\", \\\"vsserror\\\", \\\"vswriter\\\", \\\"wbemads\\\", \\\"wbemcli\\\", \\\"wbemdisp\\\", \\\"wbemprov\\\", \\\"wbemtran\\\", \\\"wct\\\", \\\"werapi\\\", \\\"winbase\\\", \\\"wincodec\\\", \\\"wincodecsdk\\\", \\\"wincon\\\", \\\"wincontypes\\\", \\\"wincred\\\", \\\"wincrypt\\\", \\\"windef\\\", \\\"windot11\\\", \\\"windowsceip\\\", \\\"windowsx\\\", \\\"winefs\\\", \\\"winerror\\\", \\\"winevt\\\", \\\"wingdi\\\", \\\"winhttp\\\", \\\"wininet\\\", \\\"winineti\\\", \\\"winioctl\\\", \\\"winnetwk\\\", \\\"winnls\\\", \\\"winnt\\\", \\\"winreg\\\", \\\"winsafer\\\", \\\"winscard\\\", \\\"winsmcrd\\\", \\\"winsock2\\\", \\\"winspool\\\", \\\"winstring\\\", \\\"winsvc\\\", \\\"wintrust\\\", \\\"winusb\\\", \\\"winusbio\\\", \\\"winuser\\\", \\\"winver\\\", \\\"wlanapi\\\", \\\"wlanihv\\\", \\\"wlanihvtypes\\\", \\\"wlantypes\\\", \\\"wlclient\\\", \\\"wmistr\\\", \\\"wnnc\\\", \\\"wow64apiset\\\", \\\"wpdmtpextensions\\\", \\\"ws2bth\\\", \\\"ws2def\\\", \\\"ws2ipdef\\\", \\\"ws2spi\\\", \\\"ws2tcpip\\\", \\\"wtsapi32\\\", \\\"wtypes\\\", \\\"wtypesbase\\\", \\\"xinput\\\"))\" -C metadata=aefb0aee894e0ada -C extra-filename=-1353e99ede147387 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "winapi",
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
        "cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\", \"bcrypt\", \"bits\", \"bits10_1\", \"bits1_5\", \"bits2_0\", \"bits2_5\", \"bits3_0\", \"bits4_0\", \"bits5_0\", \"bitscfg\", \"bitsmsg\", \"bluetoothapis\", \"bluetoothleapis\", \"bthdef\", \"bthioctl\", \"bthledef\", \"bthsdpdef\", \"bugcodes\", \"cderr\", \"cfg\", \"cfgmgr32\", \"cguid\", \"combaseapi\", \"coml2api\", \"commapi\", \"commctrl\", \"commdlg\", \"commoncontrols\", \"consoleapi\", \"corecrt\", \"corsym\", \"d2d1\", \"d2d1_1\", \"d2d1_2\", \"d2d1_3\", \"d2d1effectauthor\", \"d2d1effects\", \"d2d1effects_1\", \"d2d1effects_2\", \"d2d1svg\", \"d2dbasetypes\", \"d3d\", \"d3d10\", \"d3d10_1\", \"d3d10_1shader\", \"d3d10effect\", \"d3d10misc\", \"d3d10sdklayers\", \"d3d10shader\", \"d3d11\", \"d3d11_1\", \"d3d11_2\", \"d3d11_3\", \"d3d11_4\", \"d3d11on12\", \"d3d11sdklayers\", \"d3d11shader\", \"d3d11tokenizedprogramformat\", \"d3d12\", \"d3d12sdklayers\", \"d3d12shader\", \"d3d9\", \"d3d9caps\", \"d3d9types\", \"d3dcommon\", \"d3dcompiler\", \"d3dcsx\", \"d3dkmdt\", \"d3dkmthk\", \"d3dukmdt\", \"d3dx10core\", \"d3dx10math\", \"d3dx10mesh\", \"datetimeapi\", \"davclnt\", \"dbghelp\", \"dbt\", \"dcommon\", \"dcomp\", \"dcompanimation\", \"dcomptypes\", \"dde\", \"ddraw\", \"ddrawi\", \"ddrawint\", \"debug\", \"debugapi\", \"devguid\", \"devicetopology\", \"devpkey\", \"devpropdef\", \"dinput\", \"dinputd\", \"dispex\", \"dmksctl\", \"dmusicc\", \"docobj\", \"documenttarget\", \"dot1x\", \"dpa_dsa\", \"dpapi\", \"dsgetdc\", \"dsound\", \"dsrole\", \"dvp\", \"dwmapi\", \"dwrite\", \"dwrite_1\", \"dwrite_2\", \"dwrite_3\", \"dxdiag\", \"dxfile\", \"dxgi\", \"dxgi1_2\", \"dxgi1_3\", \"dxgi1_4\", \"dxgi1_5\", \"dxgi1_6\", \"dxgidebug\", \"dxgiformat\", \"dxgitype\", \"dxva2api\", \"dxvahd\", \"eaptypes\", \"enclaveapi\", \"endpointvolume\", \"errhandlingapi\", \"everything\", \"evntcons\", \"evntprov\", \"evntrace\", \"excpt\", \"exdisp\", \"fibersapi\", \"fileapi\", \"functiondiscoverykeys_devpkey\", \"gl-gl\", \"guiddef\", \"handleapi\", \"heapapi\", \"hidclass\", \"hidpi\", \"hidsdi\", \"hidusage\", \"highlevelmonitorconfigurationapi\", \"hstring\", \"http\", \"ifdef\", \"ifmib\", \"imm\", \"impl-debug\", \"impl-default\", \"in6addr\", \"inaddr\", \"inspectable\", \"interlockedapi\", \"intsafe\", \"ioapiset\", \"ipexport\", \"iphlpapi\", \"ipifcons\", \"ipmib\", \"iprtrmib\", \"iptypes\", \"jobapi\", \"jobapi2\", \"knownfolders\", \"ks\", \"ksmedia\", \"ktmtypes\", \"ktmw32\", \"l2cmn\", \"libloaderapi\", \"limits\", \"lmaccess\", \"lmalert\", \"lmapibuf\", \"lmat\", \"lmcons\", \"lmdfs\", \"lmerrlog\", \"lmjoin\", \"lmmsg\", \"lmremutl\", \"lmrepl\", \"lmserver\", \"lmshare\", \"lmstats\", \"lmsvc\", \"lmuse\", \"lmwksta\", \"lowlevelmonitorconfigurationapi\", \"lsalookup\", \"memoryapi\", \"minschannel\", \"minwinbase\", \"minwindef\", \"mmdeviceapi\", \"mmeapi\", \"mmreg\", \"mmsystem\", \"mprapidef\", \"msaatext\", \"mscat\", \"mschapp\", \"mssip\", \"mstcpip\", \"mswsock\", \"mswsockdef\", \"namedpipeapi\", \"namespaceapi\", \"nb30\", \"ncrypt\", \"netioapi\", \"nldef\", \"ntddndis\", \"ntddscsi\", \"ntddser\", \"ntdef\", \"ntlsa\", \"ntsecapi\", \"ntstatus\", \"oaidl\", \"objbase\", \"objidl\", \"objidlbase\", \"ocidl\", \"ole2\", \"oleauto\", \"olectl\", \"oleidl\", \"opmapi\", \"pdh\", \"perflib\", \"physicalmonitorenumerationapi\", \"playsoundapi\", \"portabledevice\", \"portabledeviceapi\", \"portabledevicetypes\", \"powerbase\", \"powersetting\", \"powrprof\", \"processenv\", \"processsnapshot\", \"processthreadsapi\", \"processtopologyapi\", \"profileapi\", \"propidl\", \"propkey\", \"propkeydef\", \"propsys\", \"prsht\", \"psapi\", \"qos\", \"realtimeapiset\", \"reason\", \"restartmanager\", \"restrictederrorinfo\", \"rmxfguid\", \"roapi\", \"robuffer\", \"roerrorapi\", \"rpc\", \"rpcdce\", \"rpcndr\", \"rtinfo\", \"sapi\", \"sapi51\", \"sapi53\", \"sapiddk\", \"sapiddk51\", \"schannel\", \"sddl\", \"securityappcontainer\", \"securitybaseapi\", \"servprov\", \"setupapi\", \"shellapi\", \"shellscalingapi\", \"shlobj\", \"shobjidl\", \"shobjidl_core\", \"shtypes\", \"softpub\", \"spapidef\", \"spellcheck\", \"sporder\", \"sql\", \"sqlext\", \"sqltypes\", \"sqlucode\", \"sspi\", \"std\", \"stralign\", \"stringapiset\", \"strmif\", \"subauth\", \"synchapi\", \"sysinfoapi\", \"systemtopologyapi\", \"taskschd\", \"tcpestats\", \"tcpmib\", \"textstor\", \"threadpoolapiset\", \"threadpoollegacyapiset\", \"timeapi\", \"timezoneapi\", \"tlhelp32\", \"transportsettingcommon\", \"tvout\", \"udpmib\", \"unknwnbase\", \"urlhist\", \"urlmon\", \"usb\", \"usbioctl\", \"usbiodef\", \"usbscan\", \"usbspec\", \"userenv\", \"usp10\", \"utilapiset\", \"uxtheme\", \"vadefs\", \"vcruntime\", \"vsbackup\", \"vss\", \"vsserror\", \"vswriter\", \"wbemads\", \"wbemcli\", \"wbemdisp\", \"wbemprov\", \"wbemtran\", \"wct\", \"werapi\", \"winbase\", \"wincodec\", \"wincodecsdk\", \"wincon\", \"wincontypes\", \"wincred\", \"wincrypt\", \"windef\", \"windot11\", \"windowsceip\", \"windowsx\", \"winefs\", \"winerror\", \"winevt\", \"wingdi\", \"winhttp\", \"wininet\", \"winineti\", \"winioctl\", \"winnetwk\", \"winnls\", \"winnt\", \"winreg\", \"winsafer\", \"winscard\", \"winsmcrd\", \"winsock2\", \"winspool\", \"winstring\", \"winsvc\", \"wintrust\", \"winusb\", \"winusbio\", \"winuser\", \"winver\", \"wlanapi\", \"wlanihv\", \"wlanihvtypes\", \"wlantypes\", \"wlclient\", \"wmistr\", \"wnnc\", \"wow64apiset\", \"wpdmtpextensions\", \"ws2bth\", \"ws2def\", \"ws2ipdef\", \"ws2spi\", \"ws2tcpip\", \"wtsapi32\", \"wtypes\", \"wtypesbase\", \"xinput\"))",
        "-C",
        "metadata=aefb0aee894e0ada",
        "-C",
        "extra-filename=-1353e99ede147387",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:47:24.913129+00:00",
      "end_time": "2026-07-13T14:47:25.056138+00:00",
      "start_unix_nanos": 1783954044913128700,
      "end_unix_nanos": 1783954045056137700,
      "crate_name": "winapi",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3tallu1a\\src\\winapi-0.3.9\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 36,
    "crate": "winapi",
    "version": "0.3.9",
    "crate_id": "429",
    "version_id": "256324",
    "downloads": 278313562,
    "cumulative_downloads": 12924695285,
    "cumulative_share_of_global": 0.04832245192954915,
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
