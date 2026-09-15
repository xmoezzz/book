# `scratch` `1.0.7`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "scratch",
    "version": "1.0.7",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000190       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000218       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000228       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000238       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002e8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000308       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000190       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000190       \\177KERNEL32_NULL_THUNK_DATA 000000014001a190     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000001e0       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001a1e0     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000200       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001a200     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000218       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000218       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001a218     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000228       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000228       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001a228     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000238       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000238       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001a238     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002d0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001a2d0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002e8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002e8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001a2e8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000308       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000308       \\177ntdll_NULL_THUNK_DATA  000000014001a308     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-link-link-7660-1783954537198978200.map",
  "pid": 7660,
  "ppid": 17420,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-link-link-7660-1783954537198978200.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "scratch",
    "version": "1.0.7",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fs2@0.4.3",
      "name": "fs2",
      "version": "0.4.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fs2-0.4.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fs2-0.4.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
      "name": "scratch",
      "version": "1.0.7",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
      "name": "winapi",
      "version": "0.3.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-0.3.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-0.3.9"
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "exit_code": 0,
  "kind": "exec",
  "pid": 7660,
  "ppid": 17420,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "scratch",
    "version": "1.0.7",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "scratch",
    "version": "1.0.7",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "cargo_pkg_name": "scratch",
  "cargo_pkg_version": "1.0.7",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 7660,
  "ppid": 17420,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "_owner": {
    "crate": "scratch",
    "version": "1.0.7",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000190       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000218       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000228       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000238       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002e8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000308       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000190       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000190       \\177KERNEL32_NULL_THUNK_DATA 000000014001a190     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000001e0       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001a1e0     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000200       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001a200     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000218       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000218       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001a218     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000228       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000228       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001a228     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000238       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000238       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001a238     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002d0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001a2d0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002e8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002e8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001a2e8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000308       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000308       \\177ntdll_NULL_THUNK_DATA  000000014001a308     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-link-link-7660-1783954537198978200.map",
  "pid": 7660,
  "ppid": 17420,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-link-link-7660-1783954537198978200.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "scratch",
    "version": "1.0.7",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
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
  "raw_event_count": 17482,
  "parsed_event_count": 17481,
  "parse_error_count": 0,
  "command_line_event_count": 17481,
  "build_script_root_event_count": 344,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 2110,
  "dropped_event_count": 9163
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 5744,
  "ppid": 17744,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:55:38.197285+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\build-script-build.exe",
  "root_cargo_pid": 14460,
  "build_script_root_pid": 5744,
  "build_script_related": true,
  "build_script_target_dir": "scratch-a46b9c7867519e97"
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
  "run_id": "scratch:1.0.7:2896",
  "root_process_pid": 14460,
  "pid": 10604,
  "ppid": 10360,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
  "time": "2026-07-13T14:55:35.229958+00:00",
  "end_time": "2026-07-13T14:55:35.321534+00:00",
  "start_unix_nanos": 1783954535229957800,
  "end_unix_nanos": 1783954535321533900,
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
  "run_id": "scratch:1.0.7:2896",
  "root_process_pid": 14460,
  "pid": 16248,
  "ppid": 10360,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
  "time": "2026-07-13T14:55:35.347668+00:00",
  "end_time": "2026-07-13T14:55:35.456939+00:00",
  "start_unix_nanos": 1783954535347667600,
  "end_unix_nanos": 1783954535456939000,
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
  "run_id": "scratch:1.0.7:2896",
  "root_process_pid": 14460,
  "pid": 16888,
  "ppid": 10360,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
  "time": "2026-07-13T14:55:35.791143+00:00",
  "end_time": "2026-07-13T14:55:35.889173+00:00",
  "start_unix_nanos": 1783954535791143300,
  "end_unix_nanos": 1783954535889172600,
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
  "run_id": "scratch:1.0.7:2896",
  "root_process_pid": 14460,
  "pid": 12800,
  "ppid": 17744,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
  "time": "2026-07-13T14:55:36.378252+00:00",
  "end_time": "2026-07-13T14:55:36.444068+00:00",
  "start_unix_nanos": 1783954536378251700,
  "end_unix_nanos": 1783954536444067600,
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
  "run_id": "scratch:1.0.7:2896",
  "root_process_pid": 14460,
  "pid": 15512,
  "ppid": 17744,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
  "time": "2026-07-13T14:55:36.465518+00:00",
  "end_time": "2026-07-13T14:55:36.563768+00:00",
  "start_unix_nanos": 1783954536465518100,
  "end_unix_nanos": 1783954536563767600,
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
  "run_id": "scratch:1.0.7:2896",
  "root_process_pid": 14460,
  "pid": 16504,
  "ppid": 17744,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
  "time": "2026-07-13T14:55:36.602524+00:00",
  "end_time": "2026-07-13T14:55:36.685817+00:00",
  "start_unix_nanos": 1783954536602524000,
  "end_unix_nanos": 1783954536685817500,
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
  "run_id": "scratch:1.0.7:2896",
  "root_process_pid": 14460,
  "pid": 17900,
  "ppid": 17744,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
    "metadata=097cb1d93c650fdc",
    "-C",
    "extra-filename=-a46b9c7867519e97",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=097cb1d93c650fdc -C extra-filename=-a46b9c7867519e97 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps",
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
    "metadata=097cb1d93c650fdc",
    "-C",
    "extra-filename=-a46b9c7867519e97",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:55:36.733846+00:00",
  "end_time": "2026-07-13T14:55:38.106641+00:00",
  "start_unix_nanos": 1783954536733845600,
  "end_unix_nanos": 1783954538106641300,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97"
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
  "run_id": "scratch:1.0.7:2896",
  "root_process_pid": 14460,
  "pid": 5760,
  "ppid": 17744,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "scratch",
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
    "metadata=7500b6b374f44efa",
    "-C",
    "extra-filename=-870d3513d01c93c1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name scratch --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=7500b6b374f44efa -C extra-filename=-870d3513d01c93c1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "scratch",
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
    "metadata=7500b6b374f44efa",
    "-C",
    "extra-filename=-870d3513d01c93c1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:55:38.254201+00:00",
  "end_time": "2026-07-13T14:55:38.715405+00:00",
  "start_unix_nanos": 1783954538254200800,
  "end_unix_nanos": 1783954538715405100,
  "crate_name": "scratch",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:55:40.705594+00:00",
  "crate": "scratch",
  "version": "1.0.7",
  "duration_seconds": 29.63080209994223,
  "trace_record_count": 7,
  "trace_owner_summary": {
    "owner_package_count": 6,
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
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "fs2",
        "version": "0.4.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fs2@0.4.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fs2-0.4.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fs2-0.4.3/Cargo.toml"
      },
      {
        "crate": "scratch",
        "version": "1.0.7",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "scratch",
        "version": "1.0.7",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fs2@0.4.3",
          "name": "fs2",
          "version": "0.4.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fs2-0.4.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fs2-0.4.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
          "name": "scratch",
          "version": "1.0.7",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
          "name": "winapi",
          "version": "0.3.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-0.3.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-0.3.9"
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "exit_code": 0,
      "kind": "exec",
      "pid": 7660,
      "ppid": 17420,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "scratch",
        "version": "1.0.7",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "scratch",
        "version": "1.0.7",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "cargo_pkg_name": "scratch",
      "cargo_pkg_version": "1.0.7",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 7660,
      "ppid": 17420,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "_owner": {
        "crate": "scratch",
        "version": "1.0.7",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-12044-1783954534853\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\rustc4CBaqC\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000190       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000200       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000218       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000228       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000238       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002d0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002e8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000308       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000190       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000190       \\177KERNEL32_NULL_THUNK_DATA 000000014001a190     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000001e0       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001a1e0     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000200       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001a200     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000218       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000218       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001a218     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000228       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000228       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001a228     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000238       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000238       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001a238     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002d0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001a2d0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002e8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:000002e8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001a2e8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000308       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\0002:00000308       \\177ntdll_NULL_THUNK_DATA  000000014001a308     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-link-link-7660-1783954537198978200.map",
      "pid": 7660,
      "ppid": 17420,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\.tmp\\native-trace-link-link-7660-1783954537198978200.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "scratch",
        "version": "1.0.7",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7#scratch@1.0.7",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-v6ddvdzk/src/scratch-1.0.7",
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
      "raw_event_count": 17482,
      "parsed_event_count": 17481,
      "parse_error_count": 0,
      "command_line_event_count": 17481,
      "build_script_root_event_count": 344,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 2110,
      "dropped_event_count": 9163
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 5744,
      "ppid": 17744,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:55:38.197285+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97\\build-script-build.exe",
      "root_cargo_pid": 14460,
      "build_script_root_pid": 5744,
      "build_script_related": true,
      "build_script_target_dir": "scratch-a46b9c7867519e97"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "scratch:1.0.7:2896",
      "root_process_pid": 14460,
      "pid": 10604,
      "ppid": 10360,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
      "time": "2026-07-13T14:55:35.229958+00:00",
      "end_time": "2026-07-13T14:55:35.321534+00:00",
      "start_unix_nanos": 1783954535229957800,
      "end_unix_nanos": 1783954535321533900,
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
      "run_id": "scratch:1.0.7:2896",
      "root_process_pid": 14460,
      "pid": 16248,
      "ppid": 10360,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
      "time": "2026-07-13T14:55:35.347668+00:00",
      "end_time": "2026-07-13T14:55:35.456939+00:00",
      "start_unix_nanos": 1783954535347667600,
      "end_unix_nanos": 1783954535456939000,
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
      "run_id": "scratch:1.0.7:2896",
      "root_process_pid": 14460,
      "pid": 16888,
      "ppid": 10360,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
      "time": "2026-07-13T14:55:35.791143+00:00",
      "end_time": "2026-07-13T14:55:35.889173+00:00",
      "start_unix_nanos": 1783954535791143300,
      "end_unix_nanos": 1783954535889172600,
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
      "run_id": "scratch:1.0.7:2896",
      "root_process_pid": 14460,
      "pid": 12800,
      "ppid": 17744,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
      "time": "2026-07-13T14:55:36.378252+00:00",
      "end_time": "2026-07-13T14:55:36.444068+00:00",
      "start_unix_nanos": 1783954536378251700,
      "end_unix_nanos": 1783954536444067600,
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
      "run_id": "scratch:1.0.7:2896",
      "root_process_pid": 14460,
      "pid": 15512,
      "ppid": 17744,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
      "time": "2026-07-13T14:55:36.465518+00:00",
      "end_time": "2026-07-13T14:55:36.563768+00:00",
      "start_unix_nanos": 1783954536465518100,
      "end_unix_nanos": 1783954536563767600,
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
      "run_id": "scratch:1.0.7:2896",
      "root_process_pid": 14460,
      "pid": 16504,
      "ppid": 17744,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
      "time": "2026-07-13T14:55:36.602524+00:00",
      "end_time": "2026-07-13T14:55:36.685817+00:00",
      "start_unix_nanos": 1783954536602524000,
      "end_unix_nanos": 1783954536685817500,
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
      "run_id": "scratch:1.0.7:2896",
      "root_process_pid": 14460,
      "pid": 17900,
      "ppid": 17744,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
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
        "metadata=097cb1d93c650fdc",
        "-C",
        "extra-filename=-a46b9c7867519e97",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=097cb1d93c650fdc -C extra-filename=-a46b9c7867519e97 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps",
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
        "metadata=097cb1d93c650fdc",
        "-C",
        "extra-filename=-a46b9c7867519e97",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:55:36.733846+00:00",
      "end_time": "2026-07-13T14:55:38.106641+00:00",
      "start_unix_nanos": 1783954536733845600,
      "end_unix_nanos": 1783954538106641300,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\build\\scratch-a46b9c7867519e97"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "scratch:1.0.7:2896",
      "root_process_pid": 14460,
      "pid": 5760,
      "ppid": 17744,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "scratch",
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
        "metadata=7500b6b374f44efa",
        "-C",
        "extra-filename=-870d3513d01c93c1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name scratch --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=7500b6b374f44efa -C extra-filename=-870d3513d01c93c1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "scratch",
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
        "metadata=7500b6b374f44efa",
        "-C",
        "extra-filename=-870d3513d01c93c1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:55:38.254201+00:00",
      "end_time": "2026-07-13T14:55:38.715405+00:00",
      "start_unix_nanos": 1783954538254200800,
      "end_unix_nanos": 1783954538715405100,
      "crate_name": "scratch",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-v6ddvdzk\\src\\scratch-1.0.7\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 1139,
    "crate": "scratch",
    "version": "1.0.7",
    "crate_id": "289671",
    "version_id": "847054",
    "downloads": 16975898,
    "cumulative_downloads": 92084672523,
    "cumulative_share_of_global": 0.344283332281357,
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
