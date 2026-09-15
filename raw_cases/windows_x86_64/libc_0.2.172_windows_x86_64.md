# `libc` `0.2.172`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.172",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000250       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000340       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140037200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140037250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140037270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140037288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140037298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400372a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140037340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140037358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140037388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-link-link-692-1783954240634903300.map",
  "pid": 692,
  "ppid": 3424,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-link-link-692-1783954240634903300.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.172",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
      "name": "libc",
      "version": "0.2.172",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "exit_code": 0,
  "kind": "exec",
  "pid": 692,
  "ppid": 3424,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.172",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.172",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.172",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 692,
  "ppid": 3424,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "_owner": {
    "crate": "libc",
    "version": "0.2.172",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000250       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000340       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140037200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140037250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140037270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140037288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140037298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400372a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140037340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140037358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140037388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-link-link-692-1783954240634903300.map",
  "pid": 692,
  "ppid": 3424,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-link-link-692-1783954240634903300.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.172",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
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
  "raw_event_count": 5700,
  "parsed_event_count": 5700,
  "parse_error_count": 0,
  "command_line_event_count": 5700,
  "build_script_root_event_count": 105,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 511,
  "dropped_event_count": 3017
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11392,
  "ppid": 16976,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:50:41.054345+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\build-script-build.exe",
  "root_cargo_pid": 15616,
  "build_script_root_pid": 11392,
  "build_script_related": true,
  "build_script_target_dir": "libc-229cb9e569ef127c"
}
```

#### Record 8

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13888,
  "ppid": 11392,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
  ],
  "comm": "rustc-trace-wrapper.exe",
  "time": "2026-07-13T14:50:41.063460+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "root_cargo_pid": 15616,
  "build_script_root_pid": 11392,
  "build_script_related": true,
  "build_script_target_dir": "libc-229cb9e569ef127c"
}
```

#### Record 9

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 1096,
  "ppid": 13888,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:50:41.072419+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 15616,
  "build_script_root_pid": 11392,
  "build_script_related": true,
  "build_script_target_dir": "libc-229cb9e569ef127c"
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
  "run_id": "libc:0.2.172:13136",
  "root_process_pid": 15616,
  "pid": 16376,
  "ppid": 6264,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
  "time": "2026-07-13T14:50:40.227107+00:00",
  "end_time": "2026-07-13T14:50:40.257146+00:00",
  "start_unix_nanos": 1783954240227106500,
  "end_unix_nanos": 1783954240257146300,
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
  "run_id": "libc:0.2.172:13136",
  "root_process_pid": 15616,
  "pid": 14072,
  "ppid": 6264,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
  "time": "2026-07-13T14:50:40.263684+00:00",
  "end_time": "2026-07-13T14:50:40.284218+00:00",
  "start_unix_nanos": 1783954240263683500,
  "end_unix_nanos": 1783954240284218200,
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
  "run_id": "libc:0.2.172:13136",
  "root_process_pid": 15616,
  "pid": 11172,
  "ppid": 16976,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
  "time": "2026-07-13T14:50:40.327296+00:00",
  "end_time": "2026-07-13T14:50:40.345524+00:00",
  "start_unix_nanos": 1783954240327296600,
  "end_unix_nanos": 1783954240345523900,
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
  "run_id": "libc:0.2.172:13136",
  "root_process_pid": 15616,
  "pid": 12500,
  "ppid": 16976,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
  "time": "2026-07-13T14:50:40.351635+00:00",
  "end_time": "2026-07-13T14:50:40.372842+00:00",
  "start_unix_nanos": 1783954240351634500,
  "end_unix_nanos": 1783954240372841600,
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
  "run_id": "libc:0.2.172:13136",
  "root_process_pid": 15616,
  "pid": 6384,
  "ppid": 16976,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
  "time": "2026-07-13T14:50:40.381152+00:00",
  "end_time": "2026-07-13T14:50:40.399807+00:00",
  "start_unix_nanos": 1783954240381151800,
  "end_unix_nanos": 1783954240399807200,
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
  "run_id": "libc:0.2.172:13136",
  "root_process_pid": 15616,
  "pid": 15476,
  "ppid": 16976,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=670f7a3322982fe6",
    "-C",
    "extra-filename=-229cb9e569ef127c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=670f7a3322982fe6 -C extra-filename=-229cb9e569ef127c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=670f7a3322982fe6",
    "-C",
    "extra-filename=-229cb9e569ef127c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:40.420995+00:00",
  "end_time": "2026-07-13T14:50:40.972786+00:00",
  "start_unix_nanos": 1783954240420994700,
  "end_unix_nanos": 1783954240972785700,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c"
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
  "run_id": "libc:0.2.172:13136",
  "root_process_pid": 15616,
  "pid": 13888,
  "ppid": 11392,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
  "time": "2026-07-13T14:50:41.067356+00:00",
  "end_time": "2026-07-13T14:50:41.086515+00:00",
  "start_unix_nanos": 1783954241067355800,
  "end_unix_nanos": 1783954241086515000,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 17

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libc:0.2.172:13136",
  "root_process_pid": 15616,
  "pid": 11128,
  "ppid": 16976,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=ffea5feb67a7beb1",
    "-C",
    "extra-filename=-d802697cf63ef110",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
    "--cfg",
    "freebsd11",
    "--cfg",
    "libc_const_extern_fn",
    "--check-cfg",
    "cfg(emscripten_old_stat_abi)",
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
    "cfg(libc_const_extern_fn)",
    "--check-cfg",
    "cfg(libc_deny_warnings)",
    "--check-cfg",
    "cfg(libc_thread_local)",
    "--check-cfg",
    "cfg(libc_ctest)",
    "--check-cfg",
    "cfg(linux_time_bits64)",
    "--check-cfg",
    "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\"))",
    "--check-cfg",
    "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
    "--check-cfg",
    "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=ffea5feb67a7beb1 -C extra-filename=-d802697cf63ef110 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps --cfg freebsd11 --cfg libc_const_extern_fn --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(libc_const_extern_fn) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(libc_thread_local) --check-cfg cfg(libc_ctest) --check-cfg cfg(linux_time_bits64) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=ffea5feb67a7beb1",
    "-C",
    "extra-filename=-d802697cf63ef110",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
    "--cfg",
    "freebsd11",
    "--cfg",
    "libc_const_extern_fn",
    "--check-cfg",
    "cfg(emscripten_old_stat_abi)",
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
    "cfg(libc_const_extern_fn)",
    "--check-cfg",
    "cfg(libc_deny_warnings)",
    "--check-cfg",
    "cfg(libc_thread_local)",
    "--check-cfg",
    "cfg(libc_ctest)",
    "--check-cfg",
    "cfg(linux_time_bits64)",
    "--check-cfg",
    "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\"))",
    "--check-cfg",
    "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
    "--check-cfg",
    "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:41.096944+00:00",
  "end_time": "2026-07-13T14:50:41.203125+00:00",
  "start_unix_nanos": 1783954241096943500,
  "end_unix_nanos": 1783954241203124500,
  "crate_name": "libc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:50:43.823237+00:00",
  "crate": "libc",
  "version": "0.2.172",
  "duration_seconds": 26.4053649000125,
  "trace_record_count": 9,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "libc",
        "version": "0.2.172",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "libc",
        "version": "0.2.172",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
          "name": "libc",
          "version": "0.2.172",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "exit_code": 0,
      "kind": "exec",
      "pid": 692,
      "ppid": 3424,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.172",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.172",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.172",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 692,
      "ppid": 3424,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "_owner": {
        "crate": "libc",
        "version": "0.2.172",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-16792-1783954240054\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\rustc4E5cOj\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000200       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000250       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000270       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000340       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140037200     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000250       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140037250     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140037270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140037288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140037298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400372a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000340       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140037340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140037358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140037388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-link-link-692-1783954240634903300.map",
      "pid": 692,
      "ppid": 3424,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\.tmp\\native-trace-link-link-692-1783954240634903300.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.172",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172#libc@0.2.172",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8os6u3ka/src/libc-0.2.172",
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
      "raw_event_count": 5700,
      "parsed_event_count": 5700,
      "parse_error_count": 0,
      "command_line_event_count": 5700,
      "build_script_root_event_count": 105,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 511,
      "dropped_event_count": 3017
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11392,
      "ppid": 16976,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:50:41.054345+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c\\build-script-build.exe",
      "root_cargo_pid": 15616,
      "build_script_root_pid": 11392,
      "build_script_related": true,
      "build_script_target_dir": "libc-229cb9e569ef127c"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13888,
      "ppid": 11392,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
      ],
      "comm": "rustc-trace-wrapper.exe",
      "time": "2026-07-13T14:50:41.063460+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "root_cargo_pid": 15616,
      "build_script_root_pid": 11392,
      "build_script_related": true,
      "build_script_target_dir": "libc-229cb9e569ef127c"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 1096,
      "ppid": 13888,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:50:41.072419+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 15616,
      "build_script_root_pid": 11392,
      "build_script_related": true,
      "build_script_target_dir": "libc-229cb9e569ef127c"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libc:0.2.172:13136",
      "root_process_pid": 15616,
      "pid": 16376,
      "ppid": 6264,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
      "time": "2026-07-13T14:50:40.227107+00:00",
      "end_time": "2026-07-13T14:50:40.257146+00:00",
      "start_unix_nanos": 1783954240227106500,
      "end_unix_nanos": 1783954240257146300,
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
      "run_id": "libc:0.2.172:13136",
      "root_process_pid": 15616,
      "pid": 14072,
      "ppid": 6264,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
      "time": "2026-07-13T14:50:40.263684+00:00",
      "end_time": "2026-07-13T14:50:40.284218+00:00",
      "start_unix_nanos": 1783954240263683500,
      "end_unix_nanos": 1783954240284218200,
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
      "run_id": "libc:0.2.172:13136",
      "root_process_pid": 15616,
      "pid": 11172,
      "ppid": 16976,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
      "time": "2026-07-13T14:50:40.327296+00:00",
      "end_time": "2026-07-13T14:50:40.345524+00:00",
      "start_unix_nanos": 1783954240327296600,
      "end_unix_nanos": 1783954240345523900,
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
      "run_id": "libc:0.2.172:13136",
      "root_process_pid": 15616,
      "pid": 12500,
      "ppid": 16976,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
      "time": "2026-07-13T14:50:40.351635+00:00",
      "end_time": "2026-07-13T14:50:40.372842+00:00",
      "start_unix_nanos": 1783954240351634500,
      "end_unix_nanos": 1783954240372841600,
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
      "run_id": "libc:0.2.172:13136",
      "root_process_pid": 15616,
      "pid": 6384,
      "ppid": 16976,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
      "time": "2026-07-13T14:50:40.381152+00:00",
      "end_time": "2026-07-13T14:50:40.399807+00:00",
      "start_unix_nanos": 1783954240381151800,
      "end_unix_nanos": 1783954240399807200,
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
      "run_id": "libc:0.2.172:13136",
      "root_process_pid": 15616,
      "pid": 15476,
      "ppid": 16976,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=670f7a3322982fe6",
        "-C",
        "extra-filename=-229cb9e569ef127c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=670f7a3322982fe6 -C extra-filename=-229cb9e569ef127c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=670f7a3322982fe6",
        "-C",
        "extra-filename=-229cb9e569ef127c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:40.420995+00:00",
      "end_time": "2026-07-13T14:50:40.972786+00:00",
      "start_unix_nanos": 1783954240420994700,
      "end_unix_nanos": 1783954240972785700,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\build\\libc-229cb9e569ef127c"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libc:0.2.172:13136",
      "root_process_pid": 15616,
      "pid": 13888,
      "ppid": 11392,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
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
      "time": "2026-07-13T14:50:41.067356+00:00",
      "end_time": "2026-07-13T14:50:41.086515+00:00",
      "start_unix_nanos": 1783954241067355800,
      "end_unix_nanos": 1783954241086515000,
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
      "run_id": "libc:0.2.172:13136",
      "root_process_pid": 15616,
      "pid": 11128,
      "ppid": 16976,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=ffea5feb67a7beb1",
        "-C",
        "extra-filename=-d802697cf63ef110",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
        "--cfg",
        "freebsd11",
        "--cfg",
        "libc_const_extern_fn",
        "--check-cfg",
        "cfg(emscripten_old_stat_abi)",
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
        "cfg(libc_const_extern_fn)",
        "--check-cfg",
        "cfg(libc_deny_warnings)",
        "--check-cfg",
        "cfg(libc_thread_local)",
        "--check-cfg",
        "cfg(libc_ctest)",
        "--check-cfg",
        "cfg(linux_time_bits64)",
        "--check-cfg",
        "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\"))",
        "--check-cfg",
        "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
        "--check-cfg",
        "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=ffea5feb67a7beb1 -C extra-filename=-d802697cf63ef110 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps --cfg freebsd11 --cfg libc_const_extern_fn --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(libc_const_extern_fn) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(libc_thread_local) --check-cfg cfg(libc_ctest) --check-cfg cfg(linux_time_bits64) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=ffea5feb67a7beb1",
        "-C",
        "extra-filename=-d802697cf63ef110",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps",
        "--cfg",
        "freebsd11",
        "--cfg",
        "libc_const_extern_fn",
        "--check-cfg",
        "cfg(emscripten_old_stat_abi)",
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
        "cfg(libc_const_extern_fn)",
        "--check-cfg",
        "cfg(libc_deny_warnings)",
        "--check-cfg",
        "cfg(libc_thread_local)",
        "--check-cfg",
        "cfg(libc_ctest)",
        "--check-cfg",
        "cfg(linux_time_bits64)",
        "--check-cfg",
        "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\"))",
        "--check-cfg",
        "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
        "--check-cfg",
        "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:41.096944+00:00",
      "end_time": "2026-07-13T14:50:41.203125+00:00",
      "start_unix_nanos": 1783954241096943500,
      "end_unix_nanos": 1783954241203124500,
      "crate_name": "libc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8os6u3ka\\src\\libc-0.2.172\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 507,
    "crate": "libc",
    "version": "0.2.172",
    "crate_id": "795",
    "version_id": "1524191",
    "downloads": 59751334,
    "cumulative_downloads": 71438938735,
    "cumulative_share_of_global": 0.2670936998357284,
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
