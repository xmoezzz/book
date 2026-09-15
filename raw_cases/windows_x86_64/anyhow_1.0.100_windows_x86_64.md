# `anyhow` `1.0.100`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "anyhow",
    "version": "1.0.100",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000238       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002c0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000378       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000390       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000003c0       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000238       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000238       \\177KERNEL32_NULL_THUNK_DATA 0000000140037238     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000288       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140037288     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002a8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400372a8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002c0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400372c0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002d0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400372d0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002e0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400372e0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000378       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000378       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140037378     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000390       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000390       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140037390     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000003c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000003c0       \\177ntdll_NULL_THUNK_DATA  00000001400373c0     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-link-link-10364-1783954210552287800.map",
  "pid": 10364,
  "ppid": 4188,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-link-link-10364-1783954210552287800.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "anyhow",
    "version": "1.0.100",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
      "name": "anyhow",
      "version": "1.0.100",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#dissimilar@1.0.10",
      "name": "dissimilar",
      "version": "1.0.10",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dissimilar-1.0.10\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dissimilar-1.0.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
      "name": "equivalent",
      "version": "1.0.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures@0.3.31",
      "name": "futures",
      "version": "0.3.31",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-0.3.31\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-0.3.31"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-channel@0.3.31",
      "name": "futures-channel",
      "version": "0.3.31",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-channel-0.3.31\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-channel-0.3.31"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.31",
      "name": "futures-core",
      "version": "0.3.31",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.31\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.31"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.31",
      "name": "futures-io",
      "version": "0.3.31",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-io-0.3.31\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-io-0.3.31"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-sink@0.3.31",
      "name": "futures-sink",
      "version": "0.3.31",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-sink-0.3.31\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-sink-0.3.31"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.31",
      "name": "futures-task",
      "version": "0.3.31",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.31\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.31"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.31",
      "name": "futures-util",
      "version": "0.3.31",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.31\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.31"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.3",
      "name": "glob",
      "version": "0.3.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\glob-0.3.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\glob-0.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.16.0",
      "name": "hashbrown",
      "version": "0.16.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.16.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.16.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.11.4",
      "name": "indexmap",
      "version": "2.11.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.11.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.11.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.15",
      "name": "itoa",
      "version": "1.0.15",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.15\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.5",
      "name": "memchr",
      "version": "2.7.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.16",
      "name": "pin-project-lite",
      "version": "0.2.16",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.16\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-utils@0.1.0",
      "name": "pin-utils",
      "version": "0.1.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-utils-0.1.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-utils-0.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.101",
      "name": "proc-macro2",
      "version": "1.0.101",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.101\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.101"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.40",
      "name": "quote",
      "version": "1.0.40",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.40\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.40"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.22",
      "name": "rustversion",
      "version": "1.0.22",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.22\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.22"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.20",
      "name": "ryu",
      "version": "1.0.20",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.20\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.225",
      "name": "serde",
      "version": "1.0.225",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.225\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.225"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.225",
      "name": "serde_core",
      "version": "1.0.225",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_core-1.0.225\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_core-1.0.225"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.225",
      "name": "serde_derive",
      "version": "1.0.225",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.225\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.225"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.145",
      "name": "serde_json",
      "version": "1.0.145",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.145\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.145"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_spanned@1.0.2",
      "name": "serde_spanned",
      "version": "1.0.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_spanned-1.0.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_spanned-1.0.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.106",
      "name": "syn",
      "version": "2.0.106",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.106\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.106"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-triple@0.1.4",
      "name": "target-triple",
      "version": "0.1.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\target-triple-0.1.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\target-triple-0.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
      "name": "termcolor",
      "version": "1.4.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\termcolor-1.4.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\termcolor-1.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror@2.0.16",
      "name": "thiserror",
      "version": "2.0.16",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-2.0.16\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-2.0.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror-impl@2.0.16",
      "name": "thiserror-impl",
      "version": "2.0.16",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-2.0.16\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-2.0.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml@0.9.7",
      "name": "toml",
      "version": "0.9.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml-0.9.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml-0.9.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@0.7.2",
      "name": "toml_datetime",
      "version": "0.7.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_datetime-0.7.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_datetime-0.7.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_parser@1.0.3",
      "name": "toml_parser",
      "version": "1.0.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_parser-1.0.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_parser-1.0.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_writer@1.0.3",
      "name": "toml_writer",
      "version": "1.0.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_writer-1.0.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_writer-1.0.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.111",
      "name": "trybuild",
      "version": "1.0.111",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\trybuild-1.0.111\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\trybuild-1.0.111"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.19",
      "name": "unicode-ident",
      "version": "1.0.19",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.19\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
      "name": "winapi-util",
      "version": "0.1.11",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.11\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.0",
      "name": "windows-link",
      "version": "0.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-link-0.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-link-0.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.0",
      "name": "windows-sys",
      "version": "0.61.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.61.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.61.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@0.7.13",
      "name": "winnow",
      "version": "0.7.13",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winnow-0.7.13\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winnow-0.7.13"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "exit_code": 0,
  "kind": "exec",
  "pid": 10364,
  "ppid": 4188,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "anyhow",
    "version": "1.0.100",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "anyhow",
    "version": "1.0.100",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "cargo_pkg_name": "anyhow",
  "cargo_pkg_version": "1.0.100",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 10364,
  "ppid": 4188,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "_owner": {
    "crate": "anyhow",
    "version": "1.0.100",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000238       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002c0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000378       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000390       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000003c0       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000238       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000238       \\177KERNEL32_NULL_THUNK_DATA 0000000140037238     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000288       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140037288     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002a8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400372a8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002c0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400372c0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002d0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400372d0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002e0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400372e0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000378       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000378       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140037378     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000390       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000390       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140037390     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000003c0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000003c0       \\177ntdll_NULL_THUNK_DATA  00000001400373c0     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-link-link-10364-1783954210552287800.map",
  "pid": 10364,
  "ppid": 4188,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-link-link-10364-1783954210552287800.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "anyhow",
    "version": "1.0.100",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
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
  "raw_event_count": 4444,
  "parsed_event_count": 4444,
  "parse_error_count": 0,
  "command_line_event_count": 4444,
  "build_script_root_event_count": 84,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 360,
  "dropped_event_count": 2331
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15720,
  "ppid": 788,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:50:10.886340+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\build-script-build.exe",
  "root_cargo_pid": 15400,
  "build_script_root_pid": 15720,
  "build_script_related": true,
  "build_script_target_dir": "anyhow-d65ddc231fdac38b"
}
```

#### Record 8

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 10244,
  "ppid": 15720,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
  ],
  "comm": "rustc-trace-wrapper.exe",
  "time": "2026-07-13T14:50:10.894256+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "root_cargo_pid": 15400,
  "build_script_root_pid": 15720,
  "build_script_related": true,
  "build_script_target_dir": "anyhow-d65ddc231fdac38b"
}
```

#### Record 9

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7440,
  "ppid": 10244,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:50:10.902019+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 15400,
  "build_script_root_pid": 15720,
  "build_script_related": true,
  "build_script_target_dir": "anyhow-d65ddc231fdac38b"
}
```

#### Record 10

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12896,
  "ppid": 15720,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:50:10.943178+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 15400,
  "build_script_root_pid": 15720,
  "build_script_related": true,
  "build_script_target_dir": "anyhow-d65ddc231fdac38b"
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
  "run_id": "anyhow:1.0.100:11856",
  "root_process_pid": 15400,
  "pid": 10256,
  "ppid": 15712,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
  "time": "2026-07-13T14:50:10.142553+00:00",
  "end_time": "2026-07-13T14:50:10.158258+00:00",
  "start_unix_nanos": 1783954210142553000,
  "end_unix_nanos": 1783954210158257900,
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
  "run_id": "anyhow:1.0.100:11856",
  "root_process_pid": 15400,
  "pid": 16984,
  "ppid": 15712,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
  "time": "2026-07-13T14:50:10.164627+00:00",
  "end_time": "2026-07-13T14:50:10.181706+00:00",
  "start_unix_nanos": 1783954210164626900,
  "end_unix_nanos": 1783954210181706500,
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
  "run_id": "anyhow:1.0.100:11856",
  "root_process_pid": 15400,
  "pid": 556,
  "ppid": 788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
  "time": "2026-07-13T14:50:10.262834+00:00",
  "end_time": "2026-07-13T14:50:10.279981+00:00",
  "start_unix_nanos": 1783954210262834300,
  "end_unix_nanos": 1783954210279980700,
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
  "run_id": "anyhow:1.0.100:11856",
  "root_process_pid": 15400,
  "pid": 15832,
  "ppid": 788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
  "time": "2026-07-13T14:50:10.286267+00:00",
  "end_time": "2026-07-13T14:50:10.305378+00:00",
  "start_unix_nanos": 1783954210286267000,
  "end_unix_nanos": 1783954210305378100,
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

#### Record 15

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "anyhow:1.0.100:11856",
  "root_process_pid": 15400,
  "pid": 16920,
  "ppid": 788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
  "time": "2026-07-13T14:50:10.320337+00:00",
  "end_time": "2026-07-13T14:50:10.335009+00:00",
  "start_unix_nanos": 1783954210320336900,
  "end_unix_nanos": 1783954210335008800,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
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
  "run_id": "anyhow:1.0.100:11856",
  "root_process_pid": 15400,
  "pid": 4436,
  "ppid": 788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"backtrace\", \"default\", \"std\"))",
    "-C",
    "metadata=d1f383fe84be0ef8",
    "-C",
    "extra-filename=-d65ddc231fdac38b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"backtrace\\\", \\\"default\\\", \\\"std\\\"))\" -C metadata=d1f383fe84be0ef8 -C extra-filename=-d65ddc231fdac38b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"backtrace\", \"default\", \"std\"))",
    "-C",
    "metadata=d1f383fe84be0ef8",
    "-C",
    "extra-filename=-d65ddc231fdac38b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:10.350640+00:00",
  "end_time": "2026-07-13T14:50:10.812969+00:00",
  "start_unix_nanos": 1783954210350640100,
  "end_unix_nanos": 1783954210812968700,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b"
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
  "run_id": "anyhow:1.0.100:11856",
  "root_process_pid": 15400,
  "pid": 10244,
  "ppid": 15720,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--cfg=anyhow_build_probe",
    "--edition=2018",
    "--crate-name=anyhow",
    "--crate-type=lib",
    "--cap-lints=allow",
    "--emit=dep-info,metadata",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-7e0b65d942635ec5\\out\\probe",
    "src\\nightly.rs",
    "--target",
    "x86_64-pc-windows-msvc"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --cfg=anyhow_build_probe --edition=2018 --crate-name=anyhow --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-7e0b65d942635ec5\\out\\probe src\\nightly.rs --target x86_64-pc-windows-msvc",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--cfg=anyhow_build_probe",
    "--edition=2018",
    "--crate-name=anyhow",
    "--crate-type=lib",
    "--cap-lints=allow",
    "--emit=dep-info,metadata",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-7e0b65d942635ec5\\out\\probe",
    "src\\nightly.rs",
    "--target",
    "x86_64-pc-windows-msvc"
  ],
  "exit_code": 1,
  "success": false,
  "time": "2026-07-13T14:50:10.898442+00:00",
  "end_time": "2026-07-13T14:50:10.940492+00:00",
  "start_unix_nanos": 1783954210898441700,
  "end_unix_nanos": 1783954210940492200,
  "crate_name": "anyhow",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-7e0b65d942635ec5\\out\\probe"
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
  "run_id": "anyhow:1.0.100:11856",
  "root_process_pid": 15400,
  "pid": 16300,
  "ppid": 788,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "anyhow",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"backtrace\", \"default\", \"std\"))",
    "-C",
    "metadata=c5367ae446b17772",
    "-C",
    "extra-filename=-71377cde20d2ee82",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
    "--cfg",
    "std_backtrace",
    "--check-cfg",
    "cfg(anyhow_build_probe)",
    "--check-cfg",
    "cfg(anyhow_nightly_testing)",
    "--check-cfg",
    "cfg(anyhow_no_clippy_format_args)",
    "--check-cfg",
    "cfg(anyhow_no_core_error)",
    "--check-cfg",
    "cfg(anyhow_no_core_unwind_safe)",
    "--check-cfg",
    "cfg(anyhow_no_fmt_arguments_as_str)",
    "--check-cfg",
    "cfg(anyhow_no_ptr_addr_of)",
    "--check-cfg",
    "cfg(anyhow_no_unsafe_op_in_unsafe_fn_lint)",
    "--check-cfg",
    "cfg(error_generic_member_access)",
    "--check-cfg",
    "cfg(std_backtrace)"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name anyhow --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"backtrace\\\", \\\"default\\\", \\\"std\\\"))\" -C metadata=c5367ae446b17772 -C extra-filename=-71377cde20d2ee82 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps --cfg std_backtrace --check-cfg cfg(anyhow_build_probe) --check-cfg cfg(anyhow_nightly_testing) --check-cfg cfg(anyhow_no_clippy_format_args) --check-cfg cfg(anyhow_no_core_error) --check-cfg cfg(anyhow_no_core_unwind_safe) --check-cfg cfg(anyhow_no_fmt_arguments_as_str) --check-cfg cfg(anyhow_no_ptr_addr_of) --check-cfg cfg(anyhow_no_unsafe_op_in_unsafe_fn_lint) --check-cfg cfg(error_generic_member_access) --check-cfg cfg(std_backtrace)",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "anyhow",
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
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"backtrace\", \"default\", \"std\"))",
    "-C",
    "metadata=c5367ae446b17772",
    "-C",
    "extra-filename=-71377cde20d2ee82",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
    "--cfg",
    "std_backtrace",
    "--check-cfg",
    "cfg(anyhow_build_probe)",
    "--check-cfg",
    "cfg(anyhow_nightly_testing)",
    "--check-cfg",
    "cfg(anyhow_no_clippy_format_args)",
    "--check-cfg",
    "cfg(anyhow_no_core_error)",
    "--check-cfg",
    "cfg(anyhow_no_core_unwind_safe)",
    "--check-cfg",
    "cfg(anyhow_no_fmt_arguments_as_str)",
    "--check-cfg",
    "cfg(anyhow_no_ptr_addr_of)",
    "--check-cfg",
    "cfg(anyhow_no_unsafe_op_in_unsafe_fn_lint)",
    "--check-cfg",
    "cfg(error_generic_member_access)",
    "--check-cfg",
    "cfg(std_backtrace)"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:10.966194+00:00",
  "end_time": "2026-07-13T14:50:11.628790+00:00",
  "start_unix_nanos": 1783954210966194200,
  "end_unix_nanos": 1783954211628789700,
  "crate_name": "anyhow",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:50:13.297292+00:00",
  "crate": "anyhow",
  "version": "1.0.100",
  "duration_seconds": 25.652495600050315,
  "trace_record_count": 10,
  "trace_owner_summary": {
    "owner_package_count": 41,
    "owner_packages": [
      {
        "crate": "pin-project-lite",
        "version": "0.2.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.16",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.16",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.16/Cargo.toml"
      },
      {
        "crate": "futures-channel",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-channel@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-channel-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-channel-0.3.31/Cargo.toml"
      },
      {
        "crate": "thiserror-impl",
        "version": "2.0.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror-impl@2.0.16",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.16",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.16/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.225",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.225",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.225",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.225/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.19",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.19",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.19/Cargo.toml"
      },
      {
        "crate": "futures-core",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.31/Cargo.toml"
      },
      {
        "crate": "futures-sink",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-sink@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.31/Cargo.toml"
      },
      {
        "crate": "futures-task",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.31/Cargo.toml"
      },
      {
        "crate": "futures-util",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.31/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.101",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.101",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.101",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.101/Cargo.toml"
      },
      {
        "crate": "serde_spanned",
        "version": "1.0.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_spanned@1.0.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-1.0.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-1.0.2/Cargo.toml"
      },
      {
        "crate": "target-triple",
        "version": "0.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-triple@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-0.1.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-0.1.4/Cargo.toml"
      },
      {
        "crate": "toml_datetime",
        "version": "0.7.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@0.7.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.7.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.7.2/Cargo.toml"
      },
      {
        "crate": "rustversion",
        "version": "1.0.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.22",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.22",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.22/Cargo.toml"
      },
      {
        "crate": "serde_core",
        "version": "1.0.225",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.225",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.225",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.225/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.145",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.145",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.145",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.145/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml"
      },
      {
        "crate": "windows-link",
        "version": "0.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.0/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.61.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.0/Cargo.toml"
      },
      {
        "crate": "dissimilar",
        "version": "1.0.10",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#dissimilar@1.0.10",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.10",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.10/Cargo.toml"
      },
      {
        "crate": "futures-io",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.31/Cargo.toml"
      },
      {
        "crate": "toml_parser",
        "version": "1.0.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_parser@1.0.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.0.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.0.3/Cargo.toml"
      },
      {
        "crate": "toml_writer",
        "version": "1.0.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_writer@1.0.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.0.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.0.3/Cargo.toml"
      },
      {
        "crate": "equivalent",
        "version": "1.0.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2/Cargo.toml"
      },
      {
        "crate": "hashbrown",
        "version": "0.16.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.16.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.16.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.16.0/Cargo.toml"
      },
      {
        "crate": "thiserror",
        "version": "2.0.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror@2.0.16",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.16",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.16/Cargo.toml"
      },
      {
        "crate": "trybuild",
        "version": "1.0.111",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.111",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.111",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.111/Cargo.toml"
      },
      {
        "crate": "indexmap",
        "version": "2.11.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.11.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.11.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.11.4/Cargo.toml"
      },
      {
        "crate": "pin-utils",
        "version": "0.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-utils@0.1.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-utils-0.1.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-utils-0.1.0/Cargo.toml"
      },
      {
        "crate": "termcolor",
        "version": "1.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml"
      },
      {
        "crate": "futures",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.31/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.225",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.225",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.225",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.225/Cargo.toml"
      },
      {
        "crate": "winnow",
        "version": "0.7.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@0.7.13",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.13",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.13/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.7.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.5/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.40",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.40",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.15",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.15",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.15/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.106",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.106",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.106/Cargo.toml"
      },
      {
        "crate": "glob",
        "version": "0.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.20",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.20",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.20/Cargo.toml"
      },
      {
        "crate": "toml",
        "version": "0.9.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml@0.9.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.9.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.9.7/Cargo.toml"
      },
      {
        "crate": "anyhow",
        "version": "1.0.100",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 6,
    "owners": [
      {
        "crate": "anyhow",
        "version": "1.0.100",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
          "name": "anyhow",
          "version": "1.0.100",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#dissimilar@1.0.10",
          "name": "dissimilar",
          "version": "1.0.10",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dissimilar-1.0.10\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dissimilar-1.0.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
          "name": "equivalent",
          "version": "1.0.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures@0.3.31",
          "name": "futures",
          "version": "0.3.31",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-0.3.31\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-0.3.31"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-channel@0.3.31",
          "name": "futures-channel",
          "version": "0.3.31",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-channel-0.3.31\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-channel-0.3.31"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.31",
          "name": "futures-core",
          "version": "0.3.31",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.31\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.31"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.31",
          "name": "futures-io",
          "version": "0.3.31",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-io-0.3.31\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-io-0.3.31"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-sink@0.3.31",
          "name": "futures-sink",
          "version": "0.3.31",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-sink-0.3.31\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-sink-0.3.31"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.31",
          "name": "futures-task",
          "version": "0.3.31",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.31\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.31"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.31",
          "name": "futures-util",
          "version": "0.3.31",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.31\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.31"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.3",
          "name": "glob",
          "version": "0.3.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\glob-0.3.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\glob-0.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.16.0",
          "name": "hashbrown",
          "version": "0.16.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.16.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.16.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.11.4",
          "name": "indexmap",
          "version": "2.11.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.11.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.11.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.15",
          "name": "itoa",
          "version": "1.0.15",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.15\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.5",
          "name": "memchr",
          "version": "2.7.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.16",
          "name": "pin-project-lite",
          "version": "0.2.16",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.16\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-utils@0.1.0",
          "name": "pin-utils",
          "version": "0.1.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-utils-0.1.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-utils-0.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.101",
          "name": "proc-macro2",
          "version": "1.0.101",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.101\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.101"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.40",
          "name": "quote",
          "version": "1.0.40",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.40\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.40"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.22",
          "name": "rustversion",
          "version": "1.0.22",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.22\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.22"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.20",
          "name": "ryu",
          "version": "1.0.20",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.20\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.225",
          "name": "serde",
          "version": "1.0.225",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.225\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.225"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.225",
          "name": "serde_core",
          "version": "1.0.225",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_core-1.0.225\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_core-1.0.225"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.225",
          "name": "serde_derive",
          "version": "1.0.225",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.225\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.225"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.145",
          "name": "serde_json",
          "version": "1.0.145",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.145\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.145"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_spanned@1.0.2",
          "name": "serde_spanned",
          "version": "1.0.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_spanned-1.0.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_spanned-1.0.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.106",
          "name": "syn",
          "version": "2.0.106",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.106\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.106"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-triple@0.1.4",
          "name": "target-triple",
          "version": "0.1.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\target-triple-0.1.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\target-triple-0.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
          "name": "termcolor",
          "version": "1.4.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\termcolor-1.4.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\termcolor-1.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror@2.0.16",
          "name": "thiserror",
          "version": "2.0.16",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-2.0.16\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-2.0.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror-impl@2.0.16",
          "name": "thiserror-impl",
          "version": "2.0.16",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-2.0.16\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-2.0.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml@0.9.7",
          "name": "toml",
          "version": "0.9.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml-0.9.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml-0.9.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@0.7.2",
          "name": "toml_datetime",
          "version": "0.7.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_datetime-0.7.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_datetime-0.7.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_parser@1.0.3",
          "name": "toml_parser",
          "version": "1.0.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_parser-1.0.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_parser-1.0.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_writer@1.0.3",
          "name": "toml_writer",
          "version": "1.0.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_writer-1.0.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_writer-1.0.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.111",
          "name": "trybuild",
          "version": "1.0.111",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\trybuild-1.0.111\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\trybuild-1.0.111"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.19",
          "name": "unicode-ident",
          "version": "1.0.19",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.19\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
          "name": "winapi-util",
          "version": "0.1.11",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.11\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.0",
          "name": "windows-link",
          "version": "0.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-link-0.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-link-0.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.0",
          "name": "windows-sys",
          "version": "0.61.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.61.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.61.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@0.7.13",
          "name": "winnow",
          "version": "0.7.13",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winnow-0.7.13\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winnow-0.7.13"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "exit_code": 0,
      "kind": "exec",
      "pid": 10364,
      "ppid": 4188,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "anyhow",
        "version": "1.0.100",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "anyhow",
        "version": "1.0.100",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "cargo_pkg_name": "anyhow",
      "cargo_pkg_version": "1.0.100",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 10364,
      "ppid": 4188,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "_owner": {
        "crate": "anyhow",
        "version": "1.0.100",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-10584-1783954209953\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\rustcn3SnVZ\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000238       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002c0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002d0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000378       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000390       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000003c0       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000238       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000238       \\177KERNEL32_NULL_THUNK_DATA 0000000140037238     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000288       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140037288     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002a8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400372a8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002c0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002c0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400372c0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002d0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400372d0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000002e0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400372e0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000378       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000378       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140037378     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000390       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:00000390       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140037390     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000003c0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\0002:000003c0       \\177ntdll_NULL_THUNK_DATA  00000001400373c0     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-link-link-10364-1783954210552287800.map",
      "pid": 10364,
      "ppid": 4188,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\.tmp\\native-trace-link-link-10364-1783954210552287800.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "anyhow",
        "version": "1.0.100",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100#anyhow@1.0.100",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-8pm31ll0/src/anyhow-1.0.100",
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
      "raw_event_count": 4444,
      "parsed_event_count": 4444,
      "parse_error_count": 0,
      "command_line_event_count": 4444,
      "build_script_root_event_count": 84,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 360,
      "dropped_event_count": 2331
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15720,
      "ppid": 788,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:50:10.886340+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b\\build-script-build.exe",
      "root_cargo_pid": 15400,
      "build_script_root_pid": 15720,
      "build_script_related": true,
      "build_script_target_dir": "anyhow-d65ddc231fdac38b"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 10244,
      "ppid": 15720,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
      ],
      "comm": "rustc-trace-wrapper.exe",
      "time": "2026-07-13T14:50:10.894256+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "root_cargo_pid": 15400,
      "build_script_root_pid": 15720,
      "build_script_related": true,
      "build_script_target_dir": "anyhow-d65ddc231fdac38b"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7440,
      "ppid": 10244,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:50:10.902019+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 15400,
      "build_script_root_pid": 15720,
      "build_script_related": true,
      "build_script_target_dir": "anyhow-d65ddc231fdac38b"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12896,
      "ppid": 15720,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:50:10.943178+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 15400,
      "build_script_root_pid": 15720,
      "build_script_related": true,
      "build_script_target_dir": "anyhow-d65ddc231fdac38b"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "anyhow:1.0.100:11856",
      "root_process_pid": 15400,
      "pid": 10256,
      "ppid": 15712,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
      "time": "2026-07-13T14:50:10.142553+00:00",
      "end_time": "2026-07-13T14:50:10.158258+00:00",
      "start_unix_nanos": 1783954210142553000,
      "end_unix_nanos": 1783954210158257900,
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
      "run_id": "anyhow:1.0.100:11856",
      "root_process_pid": 15400,
      "pid": 16984,
      "ppid": 15712,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
      "time": "2026-07-13T14:50:10.164627+00:00",
      "end_time": "2026-07-13T14:50:10.181706+00:00",
      "start_unix_nanos": 1783954210164626900,
      "end_unix_nanos": 1783954210181706500,
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
      "run_id": "anyhow:1.0.100:11856",
      "root_process_pid": 15400,
      "pid": 556,
      "ppid": 788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
      "time": "2026-07-13T14:50:10.262834+00:00",
      "end_time": "2026-07-13T14:50:10.279981+00:00",
      "start_unix_nanos": 1783954210262834300,
      "end_unix_nanos": 1783954210279980700,
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
      "run_id": "anyhow:1.0.100:11856",
      "root_process_pid": 15400,
      "pid": 15832,
      "ppid": 788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
      "time": "2026-07-13T14:50:10.286267+00:00",
      "end_time": "2026-07-13T14:50:10.305378+00:00",
      "start_unix_nanos": 1783954210286267000,
      "end_unix_nanos": 1783954210305378100,
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
      "run_id": "anyhow:1.0.100:11856",
      "root_process_pid": 15400,
      "pid": 16920,
      "ppid": 788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
      "time": "2026-07-13T14:50:10.320337+00:00",
      "end_time": "2026-07-13T14:50:10.335009+00:00",
      "start_unix_nanos": 1783954210320336900,
      "end_unix_nanos": 1783954210335008800,
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
      "run_id": "anyhow:1.0.100:11856",
      "root_process_pid": 15400,
      "pid": 4436,
      "ppid": 788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"backtrace\", \"default\", \"std\"))",
        "-C",
        "metadata=d1f383fe84be0ef8",
        "-C",
        "extra-filename=-d65ddc231fdac38b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"backtrace\\\", \\\"default\\\", \\\"std\\\"))\" -C metadata=d1f383fe84be0ef8 -C extra-filename=-d65ddc231fdac38b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"backtrace\", \"default\", \"std\"))",
        "-C",
        "metadata=d1f383fe84be0ef8",
        "-C",
        "extra-filename=-d65ddc231fdac38b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:10.350640+00:00",
      "end_time": "2026-07-13T14:50:10.812969+00:00",
      "start_unix_nanos": 1783954210350640100,
      "end_unix_nanos": 1783954210812968700,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-d65ddc231fdac38b"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "anyhow:1.0.100:11856",
      "root_process_pid": 15400,
      "pid": 10244,
      "ppid": 15720,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--cfg=anyhow_build_probe",
        "--edition=2018",
        "--crate-name=anyhow",
        "--crate-type=lib",
        "--cap-lints=allow",
        "--emit=dep-info,metadata",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-7e0b65d942635ec5\\out\\probe",
        "src\\nightly.rs",
        "--target",
        "x86_64-pc-windows-msvc"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --cfg=anyhow_build_probe --edition=2018 --crate-name=anyhow --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-7e0b65d942635ec5\\out\\probe src\\nightly.rs --target x86_64-pc-windows-msvc",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--cfg=anyhow_build_probe",
        "--edition=2018",
        "--crate-name=anyhow",
        "--crate-type=lib",
        "--cap-lints=allow",
        "--emit=dep-info,metadata",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-7e0b65d942635ec5\\out\\probe",
        "src\\nightly.rs",
        "--target",
        "x86_64-pc-windows-msvc"
      ],
      "exit_code": 1,
      "success": false,
      "time": "2026-07-13T14:50:10.898442+00:00",
      "end_time": "2026-07-13T14:50:10.940492+00:00",
      "start_unix_nanos": 1783954210898441700,
      "end_unix_nanos": 1783954210940492200,
      "crate_name": "anyhow",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\build\\anyhow-7e0b65d942635ec5\\out\\probe"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "anyhow:1.0.100:11856",
      "root_process_pid": 15400,
      "pid": 16300,
      "ppid": 788,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "anyhow",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"backtrace\", \"default\", \"std\"))",
        "-C",
        "metadata=c5367ae446b17772",
        "-C",
        "extra-filename=-71377cde20d2ee82",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
        "--cfg",
        "std_backtrace",
        "--check-cfg",
        "cfg(anyhow_build_probe)",
        "--check-cfg",
        "cfg(anyhow_nightly_testing)",
        "--check-cfg",
        "cfg(anyhow_no_clippy_format_args)",
        "--check-cfg",
        "cfg(anyhow_no_core_error)",
        "--check-cfg",
        "cfg(anyhow_no_core_unwind_safe)",
        "--check-cfg",
        "cfg(anyhow_no_fmt_arguments_as_str)",
        "--check-cfg",
        "cfg(anyhow_no_ptr_addr_of)",
        "--check-cfg",
        "cfg(anyhow_no_unsafe_op_in_unsafe_fn_lint)",
        "--check-cfg",
        "cfg(error_generic_member_access)",
        "--check-cfg",
        "cfg(std_backtrace)"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name anyhow --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"backtrace\\\", \\\"default\\\", \\\"std\\\"))\" -C metadata=c5367ae446b17772 -C extra-filename=-71377cde20d2ee82 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps --cfg std_backtrace --check-cfg cfg(anyhow_build_probe) --check-cfg cfg(anyhow_nightly_testing) --check-cfg cfg(anyhow_no_clippy_format_args) --check-cfg cfg(anyhow_no_core_error) --check-cfg cfg(anyhow_no_core_unwind_safe) --check-cfg cfg(anyhow_no_fmt_arguments_as_str) --check-cfg cfg(anyhow_no_ptr_addr_of) --check-cfg cfg(anyhow_no_unsafe_op_in_unsafe_fn_lint) --check-cfg cfg(error_generic_member_access) --check-cfg cfg(std_backtrace)",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "anyhow",
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
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"backtrace\", \"default\", \"std\"))",
        "-C",
        "metadata=c5367ae446b17772",
        "-C",
        "extra-filename=-71377cde20d2ee82",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps",
        "--cfg",
        "std_backtrace",
        "--check-cfg",
        "cfg(anyhow_build_probe)",
        "--check-cfg",
        "cfg(anyhow_nightly_testing)",
        "--check-cfg",
        "cfg(anyhow_no_clippy_format_args)",
        "--check-cfg",
        "cfg(anyhow_no_core_error)",
        "--check-cfg",
        "cfg(anyhow_no_core_unwind_safe)",
        "--check-cfg",
        "cfg(anyhow_no_fmt_arguments_as_str)",
        "--check-cfg",
        "cfg(anyhow_no_ptr_addr_of)",
        "--check-cfg",
        "cfg(anyhow_no_unsafe_op_in_unsafe_fn_lint)",
        "--check-cfg",
        "cfg(error_generic_member_access)",
        "--check-cfg",
        "cfg(std_backtrace)"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:10.966194+00:00",
      "end_time": "2026-07-13T14:50:11.628790+00:00",
      "start_unix_nanos": 1783954210966194200,
      "end_unix_nanos": 1783954211628789700,
      "crate_name": "anyhow",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-8pm31ll0\\src\\anyhow-1.0.100\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 416,
    "crate": "anyhow",
    "version": "1.0.100",
    "crate_id": "170198",
    "version_id": "1737227",
    "downloads": 76716059,
    "cumulative_downloads": 65209000413,
    "cumulative_share_of_global": 0.2438013986672602,
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
