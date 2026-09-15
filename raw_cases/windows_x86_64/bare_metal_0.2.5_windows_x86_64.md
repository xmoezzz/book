# `bare-metal` `0.2.5`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "bare-metal",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000250       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000340       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 000000014003a200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014003a250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014003a270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014003a288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014003a298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014003a2a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014003a340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014003a358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  000000014003a388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-link-link-11664-1783961132101529000.map",
  "pid": 11664,
  "ppid": 19584,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-link-link-11664-1783961132101529000.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "bare-metal",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
      "name": "bare-metal",
      "version": "0.2.5",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc_version@0.2.3",
      "name": "rustc_version",
      "version": "0.2.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#semver@0.9.0",
      "name": "semver",
      "version": "0.9.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#semver-parser@0.7.0",
      "name": "semver-parser",
      "version": "0.7.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 11664,
  "ppid": 19584,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "bare-metal",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "bare-metal",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "cargo_pkg_name": "bare-metal",
  "cargo_pkg_version": "0.2.5",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 11664,
  "ppid": 19584,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "_owner": {
    "crate": "bare-metal",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000250       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000340       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 000000014003a200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014003a250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014003a270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014003a288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014003a298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014003a2a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014003a340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014003a358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  000000014003a388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-link-link-11664-1783961132101529000.map",
  "pid": 11664,
  "ppid": 19584,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-link-link-11664-1783961132101529000.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "bare-metal",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
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
  "raw_event_count": 6305,
  "parsed_event_count": 6305,
  "parse_error_count": 0,
  "command_line_event_count": 6305,
  "build_script_root_event_count": 164,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 426,
  "dropped_event_count": 3272
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16004,
  "ppid": 10788,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T16:45:32.413830+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\build-script-build.exe",
  "root_cargo_pid": 2488,
  "build_script_root_pid": 16004,
  "build_script_related": true,
  "build_script_target_dir": "bare-metal-60428df0d32ac8fa"
}
```

#### Record 8

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 5500,
  "ppid": 16004,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T16:45:32.427488+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 2488,
  "build_script_root_pid": 16004,
  "build_script_related": true,
  "build_script_target_dir": "bare-metal-60428df0d32ac8fa"
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
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 9832,
  "ppid": 20548,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
  "time": "2026-07-13T16:45:28.776667+00:00",
  "end_time": "2026-07-13T16:45:28.883126+00:00",
  "start_unix_nanos": 1783961128776667400,
  "end_unix_nanos": 1783961128883125900,
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
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 21220,
  "ppid": 20548,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
  "time": "2026-07-13T16:45:28.934469+00:00",
  "end_time": "2026-07-13T16:45:28.972167+00:00",
  "start_unix_nanos": 1783961128934469000,
  "end_unix_nanos": 1783961128972166900,
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
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 7472,
  "ppid": 20548,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
  "time": "2026-07-13T16:45:30.439730+00:00",
  "end_time": "2026-07-13T16:45:30.459877+00:00",
  "start_unix_nanos": 1783961130439730200,
  "end_unix_nanos": 1783961130459876500,
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
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 18624,
  "ppid": 10788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
  "time": "2026-07-13T16:45:30.868553+00:00",
  "end_time": "2026-07-13T16:45:30.889625+00:00",
  "start_unix_nanos": 1783961130868553000,
  "end_unix_nanos": 1783961130889624900,
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
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 5560,
  "ppid": 10788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
  "time": "2026-07-13T16:45:30.897496+00:00",
  "end_time": "2026-07-13T16:45:30.920083+00:00",
  "start_unix_nanos": 1783961130897495400,
  "end_unix_nanos": 1783961130920083300,
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
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 2428,
  "ppid": 10788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
  "time": "2026-07-13T16:45:30.949672+00:00",
  "end_time": "2026-07-13T16:45:30.977569+00:00",
  "start_unix_nanos": 1783961130949672500,
  "end_unix_nanos": 1783961130977568900,
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
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 20908,
  "ppid": 10788,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "semver_parser",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=e108e08e35ab1b13",
    "-C",
    "extra-filename=-e5f378637bb84211",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name semver_parser --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=e108e08e35ab1b13 -C extra-filename=-e5f378637bb84211 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "semver_parser",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=e108e08e35ab1b13",
    "-C",
    "extra-filename=-e5f378637bb84211",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:45:31.025931+00:00",
  "end_time": "2026-07-13T16:45:31.531173+00:00",
  "start_unix_nanos": 1783961131025931200,
  "end_unix_nanos": 1783961131531173200,
  "crate_name": "semver_parser",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
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
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 19396,
  "ppid": 10788,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "semver",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"ci\", \"default\", \"serde\"))",
    "-C",
    "metadata=fa6af23967400b31",
    "-C",
    "extra-filename=-1b4a03091c8d954e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "--extern",
    "semver_parser=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver_parser-e5f378637bb84211.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name semver --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"ci\\\", \\\"default\\\", \\\"serde\\\"))\" -C metadata=fa6af23967400b31 -C extra-filename=-1b4a03091c8d954e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps --extern semver_parser=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver_parser-e5f378637bb84211.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "semver",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"ci\", \"default\", \"serde\"))",
    "-C",
    "metadata=fa6af23967400b31",
    "-C",
    "extra-filename=-1b4a03091c8d954e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "--extern",
    "semver_parser=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver_parser-e5f378637bb84211.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:45:31.450530+00:00",
  "end_time": "2026-07-13T16:45:31.728925+00:00",
  "start_unix_nanos": 1783961131450530300,
  "end_unix_nanos": 1783961131728924700,
  "crate_name": "semver",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
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
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 14140,
  "ppid": 10788,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "rustc_version",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=df8f6ad20e1b9774",
    "-C",
    "extra-filename=-16a3e0757113f136",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "--extern",
    "semver=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver-1b4a03091c8d954e.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name rustc_version --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=df8f6ad20e1b9774 -C extra-filename=-16a3e0757113f136 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps --extern semver=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver-1b4a03091c8d954e.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "rustc_version",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=df8f6ad20e1b9774",
    "-C",
    "extra-filename=-16a3e0757113f136",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "--extern",
    "semver=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver-1b4a03091c8d954e.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:45:31.658530+00:00",
  "end_time": "2026-07-13T16:45:31.855913+00:00",
  "start_unix_nanos": 1783961131658529700,
  "end_unix_nanos": 1783961131855912700,
  "crate_name": "rustc_version",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
}
```

#### Record 18

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 15796,
  "ppid": 10788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
    "cfg(feature, values(\"const-fn\"))",
    "-C",
    "metadata=a01534796b16e710",
    "-C",
    "extra-filename=-60428df0d32ac8fa",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "--extern",
    "rustc_version=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\librustc_version-16a3e0757113f136.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"const-fn\\\"))\" -C metadata=a01534796b16e710 -C extra-filename=-60428df0d32ac8fa --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps --extern rustc_version=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\librustc_version-16a3e0757113f136.rlib",
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
    "cfg(feature, values(\"const-fn\"))",
    "-C",
    "metadata=a01534796b16e710",
    "-C",
    "extra-filename=-60428df0d32ac8fa",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "--extern",
    "rustc_version=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\librustc_version-16a3e0757113f136.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:45:31.875959+00:00",
  "end_time": "2026-07-13T16:45:32.302005+00:00",
  "start_unix_nanos": 1783961131875959200,
  "end_unix_nanos": 1783961132302004800,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa"
}
```

#### Record 19

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bare-metal:0.2.5:17508",
  "root_process_pid": 2488,
  "pid": 18068,
  "ppid": 10788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "bare_metal",
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
    "cfg(feature, values(\"const-fn\"))",
    "-C",
    "metadata=5b2267d3522f30eb",
    "-C",
    "extra-filename=-7e344d72c39e61b7",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name bare_metal --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"const-fn\\\"))\" -C metadata=5b2267d3522f30eb -C extra-filename=-7e344d72c39e61b7 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "bare_metal",
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
    "cfg(feature, values(\"const-fn\"))",
    "-C",
    "metadata=5b2267d3522f30eb",
    "-C",
    "extra-filename=-7e344d72c39e61b7",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:45:32.465818+00:00",
  "end_time": "2026-07-13T16:45:32.573550+00:00",
  "start_unix_nanos": 1783961132465817600,
  "end_unix_nanos": 1783961132573549400,
  "crate_name": "bare_metal",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T16:45:34.949668+00:00",
  "crate": "bare-metal",
  "version": "0.2.5",
  "duration_seconds": 29.599381300038658,
  "trace_record_count": 8,
  "trace_owner_summary": {
    "owner_package_count": 4,
    "owner_packages": [
      {
        "crate": "rustc_version",
        "version": "0.2.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc_version@0.2.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.2.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.2.3/Cargo.toml"
      },
      {
        "crate": "semver-parser",
        "version": "0.7.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#semver-parser@0.7.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-parser-0.7.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-parser-0.7.0/Cargo.toml"
      },
      {
        "crate": "semver",
        "version": "0.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#semver@0.9.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-0.9.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-0.9.0/Cargo.toml"
      },
      {
        "crate": "bare-metal",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 4,
    "owners": [
      {
        "crate": "bare-metal",
        "version": "0.2.5",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
          "name": "bare-metal",
          "version": "0.2.5",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc_version@0.2.3",
          "name": "rustc_version",
          "version": "0.2.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#semver@0.9.0",
          "name": "semver",
          "version": "0.9.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#semver-parser@0.7.0",
          "name": "semver-parser",
          "version": "0.7.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 11664,
      "ppid": 19584,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "bare-metal",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "bare-metal",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "cargo_pkg_name": "bare-metal",
      "cargo_pkg_version": "0.2.5",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 11664,
      "ppid": 19584,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "_owner": {
        "crate": "bare-metal",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-17996-1783961128342\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\rustcszQO7E\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000200       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000250       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000270       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000340       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 000000014003a200     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000250       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014003a250     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014003a270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014003a288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014003a298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014003a2a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000340       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014003a340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014003a358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  000000014003a388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-link-link-11664-1783961132101529000.map",
      "pid": 11664,
      "ppid": 19584,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\.tmp\\native-trace-link-link-11664-1783961132101529000.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "bare-metal",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5#bare-metal@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-nkfjvrnj/src/bare-metal-0.2.5",
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
      "raw_event_count": 6305,
      "parsed_event_count": 6305,
      "parse_error_count": 0,
      "command_line_event_count": 6305,
      "build_script_root_event_count": 164,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 426,
      "dropped_event_count": 3272
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16004,
      "ppid": 10788,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T16:45:32.413830+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa\\build-script-build.exe",
      "root_cargo_pid": 2488,
      "build_script_root_pid": 16004,
      "build_script_related": true,
      "build_script_target_dir": "bare-metal-60428df0d32ac8fa"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 5500,
      "ppid": 16004,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T16:45:32.427488+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 2488,
      "build_script_root_pid": 16004,
      "build_script_related": true,
      "build_script_target_dir": "bare-metal-60428df0d32ac8fa"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 9832,
      "ppid": 20548,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
      "time": "2026-07-13T16:45:28.776667+00:00",
      "end_time": "2026-07-13T16:45:28.883126+00:00",
      "start_unix_nanos": 1783961128776667400,
      "end_unix_nanos": 1783961128883125900,
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
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 21220,
      "ppid": 20548,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
      "time": "2026-07-13T16:45:28.934469+00:00",
      "end_time": "2026-07-13T16:45:28.972167+00:00",
      "start_unix_nanos": 1783961128934469000,
      "end_unix_nanos": 1783961128972166900,
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
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 7472,
      "ppid": 20548,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
      "time": "2026-07-13T16:45:30.439730+00:00",
      "end_time": "2026-07-13T16:45:30.459877+00:00",
      "start_unix_nanos": 1783961130439730200,
      "end_unix_nanos": 1783961130459876500,
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
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 18624,
      "ppid": 10788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
      "time": "2026-07-13T16:45:30.868553+00:00",
      "end_time": "2026-07-13T16:45:30.889625+00:00",
      "start_unix_nanos": 1783961130868553000,
      "end_unix_nanos": 1783961130889624900,
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
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 5560,
      "ppid": 10788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
      "time": "2026-07-13T16:45:30.897496+00:00",
      "end_time": "2026-07-13T16:45:30.920083+00:00",
      "start_unix_nanos": 1783961130897495400,
      "end_unix_nanos": 1783961130920083300,
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
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 2428,
      "ppid": 10788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
      "time": "2026-07-13T16:45:30.949672+00:00",
      "end_time": "2026-07-13T16:45:30.977569+00:00",
      "start_unix_nanos": 1783961130949672500,
      "end_unix_nanos": 1783961130977568900,
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
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 20908,
      "ppid": 10788,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "semver_parser",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=e108e08e35ab1b13",
        "-C",
        "extra-filename=-e5f378637bb84211",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name semver_parser --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=e108e08e35ab1b13 -C extra-filename=-e5f378637bb84211 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "semver_parser",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-parser-0.7.0\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=e108e08e35ab1b13",
        "-C",
        "extra-filename=-e5f378637bb84211",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:45:31.025931+00:00",
      "end_time": "2026-07-13T16:45:31.531173+00:00",
      "start_unix_nanos": 1783961131025931200,
      "end_unix_nanos": 1783961131531173200,
      "crate_name": "semver_parser",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 19396,
      "ppid": 10788,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "semver",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"ci\", \"default\", \"serde\"))",
        "-C",
        "metadata=fa6af23967400b31",
        "-C",
        "extra-filename=-1b4a03091c8d954e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "--extern",
        "semver_parser=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver_parser-e5f378637bb84211.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name semver --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"ci\\\", \\\"default\\\", \\\"serde\\\"))\" -C metadata=fa6af23967400b31 -C extra-filename=-1b4a03091c8d954e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps --extern semver_parser=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver_parser-e5f378637bb84211.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "semver",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\semver-0.9.0\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"ci\", \"default\", \"serde\"))",
        "-C",
        "metadata=fa6af23967400b31",
        "-C",
        "extra-filename=-1b4a03091c8d954e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "--extern",
        "semver_parser=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver_parser-e5f378637bb84211.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:45:31.450530+00:00",
      "end_time": "2026-07-13T16:45:31.728925+00:00",
      "start_unix_nanos": 1783961131450530300,
      "end_unix_nanos": 1783961131728924700,
      "crate_name": "semver",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 14140,
      "ppid": 10788,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "rustc_version",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=df8f6ad20e1b9774",
        "-C",
        "extra-filename=-16a3e0757113f136",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "--extern",
        "semver=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver-1b4a03091c8d954e.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name rustc_version --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=df8f6ad20e1b9774 -C extra-filename=-16a3e0757113f136 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps --extern semver=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver-1b4a03091c8d954e.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "rustc_version",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc_version-0.2.3\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=df8f6ad20e1b9774",
        "-C",
        "extra-filename=-16a3e0757113f136",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "--extern",
        "semver=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\libsemver-1b4a03091c8d954e.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:45:31.658530+00:00",
      "end_time": "2026-07-13T16:45:31.855913+00:00",
      "start_unix_nanos": 1783961131658529700,
      "end_unix_nanos": 1783961131855912700,
      "crate_name": "rustc_version",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 15796,
      "ppid": 10788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
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
        "cfg(feature, values(\"const-fn\"))",
        "-C",
        "metadata=a01534796b16e710",
        "-C",
        "extra-filename=-60428df0d32ac8fa",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "--extern",
        "rustc_version=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\librustc_version-16a3e0757113f136.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"const-fn\\\"))\" -C metadata=a01534796b16e710 -C extra-filename=-60428df0d32ac8fa --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps --extern rustc_version=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\librustc_version-16a3e0757113f136.rlib",
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
        "cfg(feature, values(\"const-fn\"))",
        "-C",
        "metadata=a01534796b16e710",
        "-C",
        "extra-filename=-60428df0d32ac8fa",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "--extern",
        "rustc_version=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps\\librustc_version-16a3e0757113f136.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:45:31.875959+00:00",
      "end_time": "2026-07-13T16:45:32.302005+00:00",
      "start_unix_nanos": 1783961131875959200,
      "end_unix_nanos": 1783961132302004800,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\build\\bare-metal-60428df0d32ac8fa"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bare-metal:0.2.5:17508",
      "root_process_pid": 2488,
      "pid": 18068,
      "ppid": 10788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "bare_metal",
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
        "cfg(feature, values(\"const-fn\"))",
        "-C",
        "metadata=5b2267d3522f30eb",
        "-C",
        "extra-filename=-7e344d72c39e61b7",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name bare_metal --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"const-fn\\\"))\" -C metadata=5b2267d3522f30eb -C extra-filename=-7e344d72c39e61b7 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "bare_metal",
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
        "cfg(feature, values(\"const-fn\"))",
        "-C",
        "metadata=5b2267d3522f30eb",
        "-C",
        "extra-filename=-7e344d72c39e61b7",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:45:32.465818+00:00",
      "end_time": "2026-07-13T16:45:32.573550+00:00",
      "start_unix_nanos": 1783961132465817600,
      "end_unix_nanos": 1783961132573549400,
      "crate_name": "bare_metal",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-nkfjvrnj\\src\\bare-metal-0.2.5\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 1865,
    "crate": "bare-metal",
    "version": "0.2.5",
    "crate_id": "22243",
    "version_id": "172609",
    "downloads": 8041465,
    "cumulative_downloads": 100708135351,
    "cumulative_share_of_global": 0.37652446901870823,
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
