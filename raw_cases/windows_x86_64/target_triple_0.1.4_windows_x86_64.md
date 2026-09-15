# `target-triple` `0.1.4`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "target-triple",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000170       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001c0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001f8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000208       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000218       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002c8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002e0       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000170       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000170       \\177KERNEL32_NULL_THUNK_DATA 0000000140021170     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001c0       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400211c0     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001e0       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400211e0     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001f8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001f8       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400211f8     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000208       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000208       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140021208     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000218       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000218       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 0000000140021218     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002b0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400212b0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002c8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002c8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400212c8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002e0       \\177ntdll_NULL_THUNK_DATA  00000001400212e0     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-link-link-6944-1783954868008513100.map",
  "pid": 6944,
  "ppid": 20644,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-link-link-6944-1783954868008513100.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "target-triple",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
      "name": "target-triple",
      "version": "0.1.4",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 6944,
  "ppid": 20644,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "target-triple",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "target-triple",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "cargo_pkg_name": "target-triple",
  "cargo_pkg_version": "0.1.4",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 6944,
  "ppid": 20644,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "_owner": {
    "crate": "target-triple",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000170       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001c0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001f8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000208       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000218       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002c8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002e0       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000170       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000170       \\177KERNEL32_NULL_THUNK_DATA 0000000140021170     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001c0       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400211c0     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001e0       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400211e0     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001f8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001f8       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400211f8     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000208       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000208       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140021208     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000218       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000218       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 0000000140021218     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002b0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400212b0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002c8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002c8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400212c8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002e0       \\177ntdll_NULL_THUNK_DATA  00000001400212e0     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-link-link-6944-1783954868008513100.map",
  "pid": 6944,
  "ppid": 20644,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-link-link-6944-1783954868008513100.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "target-triple",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
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
  "raw_event_count": 33236,
  "parsed_event_count": 33236,
  "parse_error_count": 0,
  "command_line_event_count": 33236,
  "build_script_root_event_count": 639,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 5022,
  "dropped_event_count": 17313
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15640,
  "ppid": 18052,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T15:01:08.429678+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\build-script-build.exe",
  "root_cargo_pid": 18180,
  "build_script_root_pid": 15640,
  "build_script_related": true,
  "build_script_target_dir": "target-triple-80d8ee3f1d4e6bf1"
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
  "run_id": "target-triple:0.1.4:11856",
  "root_process_pid": 18180,
  "pid": 3796,
  "ppid": 19384,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
  "time": "2026-07-13T15:01:07.593633+00:00",
  "end_time": "2026-07-13T15:01:07.616110+00:00",
  "start_unix_nanos": 1783954867593633000,
  "end_unix_nanos": 1783954867616109900,
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
  "run_id": "target-triple:0.1.4:11856",
  "root_process_pid": 18180,
  "pid": 17984,
  "ppid": 19384,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
  "time": "2026-07-13T15:01:07.623886+00:00",
  "end_time": "2026-07-13T15:01:07.644860+00:00",
  "start_unix_nanos": 1783954867623886200,
  "end_unix_nanos": 1783954867644860100,
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
  "run_id": "target-triple:0.1.4:11856",
  "root_process_pid": 18180,
  "pid": 9336,
  "ppid": 18052,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
  "time": "2026-07-13T15:01:07.693380+00:00",
  "end_time": "2026-07-13T15:01:07.711913+00:00",
  "start_unix_nanos": 1783954867693379900,
  "end_unix_nanos": 1783954867711912900,
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
  "run_id": "target-triple:0.1.4:11856",
  "root_process_pid": 18180,
  "pid": 19204,
  "ppid": 18052,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
  "time": "2026-07-13T15:01:07.718595+00:00",
  "end_time": "2026-07-13T15:01:07.741154+00:00",
  "start_unix_nanos": 1783954867718594700,
  "end_unix_nanos": 1783954867741154100,
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
  "run_id": "target-triple:0.1.4:11856",
  "root_process_pid": 18180,
  "pid": 5100,
  "ppid": 18052,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
  "time": "2026-07-13T15:01:07.749707+00:00",
  "end_time": "2026-07-13T15:01:07.779181+00:00",
  "start_unix_nanos": 1783954867749706900,
  "end_unix_nanos": 1783954867779181000,
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
  "run_id": "target-triple:0.1.4:11856",
  "root_process_pid": 18180,
  "pid": 19128,
  "ppid": 18052,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
    "metadata=64e79abdc32d6948",
    "-C",
    "extra-filename=-80d8ee3f1d4e6bf1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=64e79abdc32d6948 -C extra-filename=-80d8ee3f1d4e6bf1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
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
    "metadata=64e79abdc32d6948",
    "-C",
    "extra-filename=-80d8ee3f1d4e6bf1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:01:07.793708+00:00",
  "end_time": "2026-07-13T15:01:08.357371+00:00",
  "start_unix_nanos": 1783954867793708400,
  "end_unix_nanos": 1783954868357371100,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1"
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
  "run_id": "target-triple:0.1.4:11856",
  "root_process_pid": 18180,
  "pid": 18756,
  "ppid": 18052,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "target_triple",
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
    "metadata=240333fe1c4800d8",
    "-C",
    "extra-filename=-6e77cde4dd85eefa",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
    "--cfg",
    "host_os=\"windows\"",
    "--check-cfg",
    "cfg(host_os, values(\"windows\"))"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name target_triple --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=240333fe1c4800d8 -C extra-filename=-6e77cde4dd85eefa --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps --cfg \"host_os=\\\"windows\\\"\" --check-cfg \"cfg(host_os, values(\\\"windows\\\"))\"",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "target_triple",
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
    "metadata=240333fe1c4800d8",
    "-C",
    "extra-filename=-6e77cde4dd85eefa",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
    "--cfg",
    "host_os=\"windows\"",
    "--check-cfg",
    "cfg(host_os, values(\"windows\"))"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:01:08.447563+00:00",
  "end_time": "2026-07-13T15:01:08.539317+00:00",
  "start_unix_nanos": 1783954868447563200,
  "end_unix_nanos": 1783954868539317000,
  "crate_name": "target_triple",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T15:01:10.885413+00:00",
  "crate": "target-triple",
  "version": "0.1.4",
  "duration_seconds": 26.04134440002963,
  "trace_record_count": 7,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "target-triple",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "target-triple",
        "version": "0.1.4",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
          "name": "target-triple",
          "version": "0.1.4",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 6944,
      "ppid": 20644,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "target-triple",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "target-triple",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "cargo_pkg_name": "target-triple",
      "cargo_pkg_version": "0.1.4",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 6944,
      "ppid": 20644,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "_owner": {
        "crate": "target-triple",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-6620-1783954867391\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\rustcMU1yYZ\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000170       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001c0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001f8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000208       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000218       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002c8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002e0       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000170       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000170       \\177KERNEL32_NULL_THUNK_DATA 0000000140021170     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001c0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001c0       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400211c0     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001e0       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400211e0     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001f8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000001f8       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400211f8     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000208       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000208       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140021208     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000218       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:00000218       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 0000000140021218     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002b0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400212b0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002c8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002c8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400212c8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\0002:000002e0       \\177ntdll_NULL_THUNK_DATA  00000001400212e0     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-link-link-6944-1783954868008513100.map",
      "pid": 6944,
      "ppid": 20644,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\.tmp\\native-trace-link-link-6944-1783954868008513100.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "target-triple",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4#target-triple@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-gbbxrlxn/src/target-triple-0.1.4",
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
      "raw_event_count": 33236,
      "parsed_event_count": 33236,
      "parse_error_count": 0,
      "command_line_event_count": 33236,
      "build_script_root_event_count": 639,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 5022,
      "dropped_event_count": 17313
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15640,
      "ppid": 18052,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T15:01:08.429678+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1\\build-script-build.exe",
      "root_cargo_pid": 18180,
      "build_script_root_pid": 15640,
      "build_script_related": true,
      "build_script_target_dir": "target-triple-80d8ee3f1d4e6bf1"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "target-triple:0.1.4:11856",
      "root_process_pid": 18180,
      "pid": 3796,
      "ppid": 19384,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
      "time": "2026-07-13T15:01:07.593633+00:00",
      "end_time": "2026-07-13T15:01:07.616110+00:00",
      "start_unix_nanos": 1783954867593633000,
      "end_unix_nanos": 1783954867616109900,
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
      "run_id": "target-triple:0.1.4:11856",
      "root_process_pid": 18180,
      "pid": 17984,
      "ppid": 19384,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
      "time": "2026-07-13T15:01:07.623886+00:00",
      "end_time": "2026-07-13T15:01:07.644860+00:00",
      "start_unix_nanos": 1783954867623886200,
      "end_unix_nanos": 1783954867644860100,
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
      "run_id": "target-triple:0.1.4:11856",
      "root_process_pid": 18180,
      "pid": 9336,
      "ppid": 18052,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
      "time": "2026-07-13T15:01:07.693380+00:00",
      "end_time": "2026-07-13T15:01:07.711913+00:00",
      "start_unix_nanos": 1783954867693379900,
      "end_unix_nanos": 1783954867711912900,
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
      "run_id": "target-triple:0.1.4:11856",
      "root_process_pid": 18180,
      "pid": 19204,
      "ppid": 18052,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
      "time": "2026-07-13T15:01:07.718595+00:00",
      "end_time": "2026-07-13T15:01:07.741154+00:00",
      "start_unix_nanos": 1783954867718594700,
      "end_unix_nanos": 1783954867741154100,
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
      "run_id": "target-triple:0.1.4:11856",
      "root_process_pid": 18180,
      "pid": 5100,
      "ppid": 18052,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
      "time": "2026-07-13T15:01:07.749707+00:00",
      "end_time": "2026-07-13T15:01:07.779181+00:00",
      "start_unix_nanos": 1783954867749706900,
      "end_unix_nanos": 1783954867779181000,
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
      "run_id": "target-triple:0.1.4:11856",
      "root_process_pid": 18180,
      "pid": 19128,
      "ppid": 18052,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
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
        "metadata=64e79abdc32d6948",
        "-C",
        "extra-filename=-80d8ee3f1d4e6bf1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=64e79abdc32d6948 -C extra-filename=-80d8ee3f1d4e6bf1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
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
        "metadata=64e79abdc32d6948",
        "-C",
        "extra-filename=-80d8ee3f1d4e6bf1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:01:07.793708+00:00",
      "end_time": "2026-07-13T15:01:08.357371+00:00",
      "start_unix_nanos": 1783954867793708400,
      "end_unix_nanos": 1783954868357371100,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\build\\target-triple-80d8ee3f1d4e6bf1"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "target-triple:0.1.4:11856",
      "root_process_pid": 18180,
      "pid": 18756,
      "ppid": 18052,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "target_triple",
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
        "metadata=240333fe1c4800d8",
        "-C",
        "extra-filename=-6e77cde4dd85eefa",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
        "--cfg",
        "host_os=\"windows\"",
        "--check-cfg",
        "cfg(host_os, values(\"windows\"))"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name target_triple --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=240333fe1c4800d8 -C extra-filename=-6e77cde4dd85eefa --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps --cfg \"host_os=\\\"windows\\\"\" --check-cfg \"cfg(host_os, values(\\\"windows\\\"))\"",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "target_triple",
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
        "metadata=240333fe1c4800d8",
        "-C",
        "extra-filename=-6e77cde4dd85eefa",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps",
        "--cfg",
        "host_os=\"windows\"",
        "--check-cfg",
        "cfg(host_os, values(\"windows\"))"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:01:08.447563+00:00",
      "end_time": "2026-07-13T15:01:08.539317+00:00",
      "start_unix_nanos": 1783954868447563200,
      "end_unix_nanos": 1783954868539317000,
      "crate_name": "target_triple",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-gbbxrlxn\\src\\target-triple-0.1.4\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 1653,
    "crate": "target-triple",
    "version": "0.1.4",
    "crate_id": "1076256",
    "version_id": "1453078",
    "downloads": 9731823,
    "cumulative_downloads": 98817267618,
    "cumulative_share_of_global": 0.3694549510828331,
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
