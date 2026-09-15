# `eyre` `0.6.12`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "eyre",
    "version": "0.6.12",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000250       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000340       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140030200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140030250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140030270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140030288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140030298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400302a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140030340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140030358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140030388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-link-link-1528-1783954262118861400.map",
  "pid": 1528,
  "ppid": 12296,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-link-link-1528-1783954262118861400.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "eyre",
    "version": "0.6.12",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#addr2line@0.21.0",
      "name": "addr2line",
      "version": "0.21.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\addr2line-0.21.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\addr2line-0.21.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#adler@1.0.2",
      "name": "adler",
      "version": "1.0.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler-1.0.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler-1.0.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#anyhow@1.0.75",
      "name": "anyhow",
      "version": "1.0.75",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\anyhow-1.0.75\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\anyhow-1.0.75"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
      "name": "autocfg",
      "version": "1.1.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.1.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#backtrace@0.3.69",
      "name": "backtrace",
      "version": "0.3.69",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\backtrace-0.3.69\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\backtrace-0.3.69"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#basic-toml@0.1.7",
      "name": "basic-toml",
      "version": "0.1.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\basic-toml-0.1.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\basic-toml-0.1.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
      "name": "bitflags",
      "version": "1.3.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
      "name": "cc",
      "version": "1.0.83",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.83\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.83"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#dissimilar@1.0.7",
      "name": "dissimilar",
      "version": "1.0.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dissimilar-1.0.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dissimilar-1.0.7"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
      "name": "eyre",
      "version": "0.6.12",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures@0.3.29",
      "name": "futures",
      "version": "0.3.29",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-0.3.29\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-0.3.29"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-channel@0.3.29",
      "name": "futures-channel",
      "version": "0.3.29",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-channel-0.3.29\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-channel-0.3.29"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.29",
      "name": "futures-core",
      "version": "0.3.29",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.29\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.29"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.29",
      "name": "futures-io",
      "version": "0.3.29",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-io-0.3.29\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-io-0.3.29"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-sink@0.3.29",
      "name": "futures-sink",
      "version": "0.3.29",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-sink-0.3.29\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-sink-0.3.29"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.29",
      "name": "futures-task",
      "version": "0.3.29",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.29\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.29"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.29",
      "name": "futures-util",
      "version": "0.3.29",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.29\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.29"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#gimli@0.28.1",
      "name": "gimli",
      "version": "0.28.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gimli-0.28.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gimli-0.28.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.1",
      "name": "glob",
      "version": "0.3.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\glob-0.3.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\glob-0.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#indenter@0.3.3",
      "name": "indenter",
      "version": "0.3.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#instant@0.1.12",
      "name": "instant",
      "version": "0.1.12",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\instant-0.1.12\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\instant-0.1.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.9",
      "name": "itoa",
      "version": "1.0.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.150",
      "name": "libc",
      "version": "0.2.150",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.150\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.150"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lock_api@0.4.11",
      "name": "lock_api",
      "version": "0.4.11",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lock_api-0.4.11\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lock_api-0.4.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.6.4",
      "name": "memchr",
      "version": "2.6.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.6.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.6.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.0",
      "name": "memoffset",
      "version": "0.9.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.9.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#miniz_oxide@0.7.1",
      "name": "miniz_oxide",
      "version": "0.7.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.7.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#object@0.32.1",
      "name": "object",
      "version": "0.32.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\object-0.32.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\object-0.32.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.18.0",
      "name": "once_cell",
      "version": "1.18.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot@0.11.2",
      "name": "parking_lot",
      "version": "0.11.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot-0.11.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot-0.11.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot_core@0.8.6",
      "name": "parking_lot_core",
      "version": "0.8.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot_core-0.8.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot_core-0.8.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.13",
      "name": "pin-project-lite",
      "version": "0.2.13",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.13\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.13"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-utils@0.1.0",
      "name": "pin-utils",
      "version": "0.1.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-utils-0.1.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-utils-0.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.70",
      "name": "proc-macro2",
      "version": "1.0.70",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.70\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.70"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pyo3@0.20.0",
      "name": "pyo3",
      "version": "0.20.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-0.20.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-0.20.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pyo3-build-config@0.20.0",
      "name": "pyo3-build-config",
      "version": "0.20.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-build-config-0.20.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-build-config-0.20.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pyo3-ffi@0.20.0",
      "name": "pyo3-ffi",
      "version": "0.20.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-ffi-0.20.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-ffi-0.20.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.33",
      "name": "quote",
      "version": "1.0.33",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.33\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.33"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.2.16",
      "name": "redox_syscall",
      "version": "0.2.16",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.2.16\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.2.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc-demangle@0.1.23",
      "name": "rustc-demangle",
      "version": "0.1.23",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc-demangle-0.1.23\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc-demangle-0.1.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.14",
      "name": "rustversion",
      "version": "1.0.14",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.14\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.15",
      "name": "ryu",
      "version": "1.0.15",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.15\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
      "name": "scopeguard",
      "version": "1.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scopeguard-1.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scopeguard-1.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.193",
      "name": "serde",
      "version": "1.0.193",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.193\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.193"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.193",
      "name": "serde_derive",
      "version": "1.0.193",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.193\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.193"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.108",
      "name": "serde_json",
      "version": "1.0.108",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.108\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.108"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#smallvec@1.11.2",
      "name": "smallvec",
      "version": "1.11.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.11.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.11.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.39",
      "name": "syn",
      "version": "2.0.39",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.39\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.39"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-lexicon@0.12.12",
      "name": "target-lexicon",
      "version": "0.12.12",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\target-lexicon-0.12.12\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\target-lexicon-0.12.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.0",
      "name": "termcolor",
      "version": "1.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\termcolor-1.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\termcolor-1.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror@1.0.50",
      "name": "thiserror",
      "version": "1.0.50",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-1.0.50\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-1.0.50"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror-impl@1.0.50",
      "name": "thiserror-impl",
      "version": "1.0.50",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-1.0.50\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-1.0.50"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.85",
      "name": "trybuild",
      "version": "1.0.85",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\trybuild-1.0.85\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\trybuild-1.0.85"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
      "name": "unicode-ident",
      "version": "1.0.12",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.12\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.12"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
      "name": "winapi-util",
      "version": "0.1.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.6"
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1528,
  "ppid": 12296,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "eyre",
    "version": "0.6.12",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "eyre",
    "version": "0.6.12",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "cargo_pkg_name": "eyre",
  "cargo_pkg_version": "0.6.12",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1528,
  "ppid": 12296,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "_owner": {
    "crate": "eyre",
    "version": "0.6.12",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000200       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000250       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000270       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000340       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140030200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140030250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140030270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140030288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140030298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400302a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140030340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140030358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140030388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-link-link-1528-1783954262118861400.map",
  "pid": 1528,
  "ppid": 12296,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-link-link-1528-1783954262118861400.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "eyre",
    "version": "0.6.12",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
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
  "pid": 12152,
  "ppid": 13448,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:51:02.508953+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\build-script-build.exe",
  "root_cargo_pid": 12572,
  "build_script_root_pid": 12152,
  "build_script_related": true,
  "build_script_target_dir": "eyre-26c0449f5f93e3bc"
}
```

#### Record 8

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 8280,
  "ppid": 12152,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:51:02.517276+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 12572,
  "build_script_root_pid": 12152,
  "build_script_related": true,
  "build_script_target_dir": "eyre-26c0449f5f93e3bc"
}
```

#### Record 9

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 9872,
  "ppid": 12152,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:51:02.554815+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 12572,
  "build_script_root_pid": 12152,
  "build_script_related": true,
  "build_script_target_dir": "eyre-26c0449f5f93e3bc"
}
```

#### Record 10

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7760,
  "ppid": 12152,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:51:02.592582+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 12572,
  "build_script_root_pid": 12152,
  "build_script_related": true,
  "build_script_target_dir": "eyre-26c0449f5f93e3bc"
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
  "run_id": "eyre:0.6.12:14896",
  "root_process_pid": 12572,
  "pid": 10076,
  "ppid": 13760,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
  "time": "2026-07-13T14:51:00.243240+00:00",
  "end_time": "2026-07-13T14:51:00.260897+00:00",
  "start_unix_nanos": 1783954260243240400,
  "end_unix_nanos": 1783954260260897400,
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
  "run_id": "eyre:0.6.12:14896",
  "root_process_pid": 12572,
  "pid": 15020,
  "ppid": 13760,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
  "time": "2026-07-13T14:51:00.267418+00:00",
  "end_time": "2026-07-13T14:51:00.287971+00:00",
  "start_unix_nanos": 1783954260267418200,
  "end_unix_nanos": 1783954260287970800,
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
  "run_id": "eyre:0.6.12:14896",
  "root_process_pid": 12572,
  "pid": 16436,
  "ppid": 13448,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
  "time": "2026-07-13T14:51:01.789679+00:00",
  "end_time": "2026-07-13T14:51:01.805796+00:00",
  "start_unix_nanos": 1783954261789679300,
  "end_unix_nanos": 1783954261805795900,
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
  "run_id": "eyre:0.6.12:14896",
  "root_process_pid": 12572,
  "pid": 680,
  "ppid": 13448,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
  "time": "2026-07-13T14:51:01.811866+00:00",
  "end_time": "2026-07-13T14:51:01.831295+00:00",
  "start_unix_nanos": 1783954261811866300,
  "end_unix_nanos": 1783954261831295300,
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
  "run_id": "eyre:0.6.12:14896",
  "root_process_pid": 12572,
  "pid": 12500,
  "ppid": 13448,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
  "time": "2026-07-13T14:51:01.850565+00:00",
  "end_time": "2026-07-13T14:51:01.871570+00:00",
  "start_unix_nanos": 1783954261850565300,
  "end_unix_nanos": 1783954261871570300,
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
  "run_id": "eyre:0.6.12:14896",
  "root_process_pid": 12572,
  "pid": 10432,
  "ppid": 13448,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "indenter",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3\\src\\lib.rs",
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
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=9752679c3d9c3044",
    "-C",
    "extra-filename=-f5f7c836ec0819a6",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name indenter --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=9752679c3d9c3044 -C extra-filename=-f5f7c836ec0819a6 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "indenter",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3\\src\\lib.rs",
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
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=9752679c3d9c3044",
    "-C",
    "extra-filename=-f5f7c836ec0819a6",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:51:01.892114+00:00",
  "end_time": "2026-07-13T14:51:01.973838+00:00",
  "start_unix_nanos": 1783954261892114300,
  "end_unix_nanos": 1783954261973838200,
  "crate_name": "indenter",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
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
  "run_id": "eyre:0.6.12:14896",
  "root_process_pid": 12572,
  "pid": 16204,
  "ppid": 13448,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "once_cell",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0\\src\\lib.rs",
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
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"race\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"atomic-polyfill\", \"critical-section\", \"default\", \"parking_lot\", \"race\", \"std\", \"unstable\"))",
    "-C",
    "metadata=b4f99540f5db8bab",
    "-C",
    "extra-filename=-667c8bd556635e4f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name once_cell --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"race\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"atomic-polyfill\\\", \\\"critical-section\\\", \\\"default\\\", \\\"parking_lot\\\", \\\"race\\\", \\\"std\\\", \\\"unstable\\\"))\" -C metadata=b4f99540f5db8bab -C extra-filename=-667c8bd556635e4f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "once_cell",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0\\src\\lib.rs",
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
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"race\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"atomic-polyfill\", \"critical-section\", \"default\", \"parking_lot\", \"race\", \"std\", \"unstable\"))",
    "-C",
    "metadata=b4f99540f5db8bab",
    "-C",
    "extra-filename=-667c8bd556635e4f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:51:01.897316+00:00",
  "end_time": "2026-07-13T14:51:02.049332+00:00",
  "start_unix_nanos": 1783954261897315600,
  "end_unix_nanos": 1783954262049332400,
  "crate_name": "once_cell",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
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
  "run_id": "eyre:0.6.12:14896",
  "root_process_pid": 12572,
  "pid": 1448,
  "ppid": 13448,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
    "feature=\"auto-install\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"track-caller\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"auto-install\", \"default\", \"pyo3\", \"track-caller\"))",
    "-C",
    "metadata=a46bd5b474986dc2",
    "-C",
    "extra-filename=-26c0449f5f93e3bc",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"auto-install\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"track-caller\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"auto-install\\\", \\\"default\\\", \\\"pyo3\\\", \\\"track-caller\\\"))\" -C metadata=a46bd5b474986dc2 -C extra-filename=-26c0449f5f93e3bc --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
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
    "feature=\"auto-install\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"track-caller\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"auto-install\", \"default\", \"pyo3\", \"track-caller\"))",
    "-C",
    "metadata=a46bd5b474986dc2",
    "-C",
    "extra-filename=-26c0449f5f93e3bc",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:51:01.899660+00:00",
  "end_time": "2026-07-13T14:51:02.423827+00:00",
  "start_unix_nanos": 1783954261899659700,
  "end_unix_nanos": 1783954262423827100,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc"
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
  "run_id": "eyre:0.6.12:14896",
  "root_process_pid": 12572,
  "pid": 16064,
  "ppid": 13448,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "eyre",
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
    "feature=\"auto-install\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"track-caller\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"auto-install\", \"default\", \"pyo3\", \"track-caller\"))",
    "-C",
    "metadata=ed5df61ddb99bc1c",
    "-C",
    "extra-filename=-91ac3ce4aed9b61d",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "--extern",
    "indenter=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libindenter-f5f7c836ec0819a6.rmeta",
    "--extern",
    "once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libonce_cell-667c8bd556635e4f.rmeta",
    "--cfg",
    "track_caller",
    "--cfg",
    "stable"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name eyre --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"auto-install\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"track-caller\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"auto-install\\\", \\\"default\\\", \\\"pyo3\\\", \\\"track-caller\\\"))\" -C metadata=ed5df61ddb99bc1c -C extra-filename=-91ac3ce4aed9b61d --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps --extern indenter=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libindenter-f5f7c836ec0819a6.rmeta --extern once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libonce_cell-667c8bd556635e4f.rmeta --cfg track_caller --cfg stable",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "eyre",
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
    "feature=\"auto-install\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"track-caller\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"auto-install\", \"default\", \"pyo3\", \"track-caller\"))",
    "-C",
    "metadata=ed5df61ddb99bc1c",
    "-C",
    "extra-filename=-91ac3ce4aed9b61d",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
    "--extern",
    "indenter=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libindenter-f5f7c836ec0819a6.rmeta",
    "--extern",
    "once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libonce_cell-667c8bd556635e4f.rmeta",
    "--cfg",
    "track_caller",
    "--cfg",
    "stable"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:51:02.616690+00:00",
  "end_time": "2026-07-13T14:51:03.200672+00:00",
  "start_unix_nanos": 1783954262616689600,
  "end_unix_nanos": 1783954263200672200,
  "crate_name": "eyre",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:51:05.735237+00:00",
  "crate": "eyre",
  "version": "0.6.12",
  "duration_seconds": 27.78761310002301,
  "trace_record_count": 10,
  "trace_owner_summary": {
    "owner_package_count": 59,
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
        "crate": "pyo3-build-config",
        "version": "0.20.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pyo3-build-config@0.20.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pyo3-build-config-0.20.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pyo3-build-config-0.20.0/Cargo.toml"
      },
      {
        "crate": "pin-project-lite",
        "version": "0.2.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.13",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.13",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.13/Cargo.toml"
      },
      {
        "crate": "futures-channel",
        "version": "0.3.29",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-channel@0.3.29",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-channel-0.3.29",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-channel-0.3.29/Cargo.toml"
      },
      {
        "crate": "parking_lot_core",
        "version": "0.8.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot_core@0.8.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.8.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.8.6/Cargo.toml"
      },
      {
        "crate": "target-lexicon",
        "version": "0.12.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-lexicon@0.12.12",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.12",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.12/Cargo.toml"
      },
      {
        "crate": "rustc-demangle",
        "version": "0.1.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc-demangle@0.1.23",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-demangle-0.1.23",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-demangle-0.1.23/Cargo.toml"
      },
      {
        "crate": "thiserror-impl",
        "version": "1.0.50",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror-impl@1.0.50",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.50",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.50/Cargo.toml"
      },
      {
        "crate": "redox_syscall",
        "version": "0.2.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.2.16",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/redox_syscall-0.2.16",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/redox_syscall-0.2.16/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.193",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.193",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.193",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.193/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml"
      },
      {
        "crate": "futures-core",
        "version": "0.3.29",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.29",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.29",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.29/Cargo.toml"
      },
      {
        "crate": "futures-sink",
        "version": "0.3.29",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-sink@0.3.29",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.29",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-sink-0.3.29/Cargo.toml"
      },
      {
        "crate": "futures-task",
        "version": "0.3.29",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.29",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.29",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.29/Cargo.toml"
      },
      {
        "crate": "futures-util",
        "version": "0.3.29",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.29",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.29",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.29/Cargo.toml"
      },
      {
        "crate": "parking_lot",
        "version": "0.11.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot@0.11.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.11.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.11.2/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.70",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.70",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.70",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.70/Cargo.toml"
      },
      {
        "crate": "rustversion",
        "version": "1.0.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.14",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.14",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.14/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.108",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.108",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.108",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.108/Cargo.toml"
      },
      {
        "crate": "futures-io",
        "version": "0.3.29",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.29",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.29",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.29/Cargo.toml"
      },
      {
        "crate": "miniz_oxide",
        "version": "0.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#miniz_oxide@0.7.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/miniz_oxide-0.7.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/miniz_oxide-0.7.1/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6/Cargo.toml"
      },
      {
        "crate": "addr2line",
        "version": "0.21.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#addr2line@0.21.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/addr2line-0.21.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/addr2line-0.21.0/Cargo.toml"
      },
      {
        "crate": "backtrace",
        "version": "0.3.69",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#backtrace@0.3.69",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/backtrace-0.3.69",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/backtrace-0.3.69/Cargo.toml"
      },
      {
        "crate": "basic-toml",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#basic-toml@0.1.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/basic-toml-0.1.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/basic-toml-0.1.7/Cargo.toml"
      },
      {
        "crate": "dissimilar",
        "version": "1.0.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#dissimilar@1.0.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.7/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.18.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.18.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0/Cargo.toml"
      },
      {
        "crate": "scopeguard",
        "version": "1.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml"
      },
      {
        "crate": "thiserror",
        "version": "1.0.50",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror@1.0.50",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.50",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.50/Cargo.toml"
      },
      {
        "crate": "lock_api",
        "version": "0.4.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lock_api@0.4.11",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.11",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.11/Cargo.toml"
      },
      {
        "crate": "memoffset",
        "version": "0.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0/Cargo.toml"
      },
      {
        "crate": "pin-utils",
        "version": "0.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-utils@0.1.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-utils-0.1.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-utils-0.1.0/Cargo.toml"
      },
      {
        "crate": "pyo3-ffi",
        "version": "0.20.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pyo3-ffi@0.20.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pyo3-ffi-0.20.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pyo3-ffi-0.20.0/Cargo.toml"
      },
      {
        "crate": "smallvec",
        "version": "1.11.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#smallvec@1.11.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smallvec-1.11.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smallvec-1.11.2/Cargo.toml"
      },
      {
        "crate": "termcolor",
        "version": "1.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.0/Cargo.toml"
      },
      {
        "crate": "trybuild",
        "version": "1.0.85",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.85",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.85",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.85/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "1.3.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/Cargo.toml"
      },
      {
        "crate": "futures",
        "version": "0.3.29",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures@0.3.29",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.29",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.29/Cargo.toml"
      },
      {
        "crate": "indenter",
        "version": "0.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#indenter@0.3.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indenter-0.3.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indenter-0.3.3/Cargo.toml"
      },
      {
        "crate": "instant",
        "version": "0.1.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#instant@0.1.12",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/instant-0.1.12",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/instant-0.1.12/Cargo.toml"
      },
      {
        "crate": "anyhow",
        "version": "1.0.75",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#anyhow@1.0.75",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.75",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anyhow-1.0.75/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml"
      },
      {
        "crate": "object",
        "version": "0.32.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#object@0.32.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/object-0.32.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/object-0.32.1/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.193",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.193",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.193",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.193/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml"
      },
      {
        "crate": "gimli",
        "version": "0.28.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#gimli@0.28.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gimli-0.28.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gimli-0.28.1/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.150",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.150",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.150",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.150/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.6.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.6.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.33",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.33",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "adler",
        "version": "1.0.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#adler@1.0.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/adler-1.0.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/adler-1.0.2/Cargo.toml"
      },
      {
        "crate": "pyo3",
        "version": "0.20.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pyo3@0.20.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pyo3-0.20.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pyo3-0.20.0/Cargo.toml"
      },
      {
        "crate": "glob",
        "version": "0.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.1/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.15",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.39",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.39",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.39",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.39/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.0.83",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/Cargo.toml"
      },
      {
        "crate": "eyre",
        "version": "0.6.12",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 6,
    "owners": [
      {
        "crate": "eyre",
        "version": "0.6.12",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#addr2line@0.21.0",
          "name": "addr2line",
          "version": "0.21.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\addr2line-0.21.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\addr2line-0.21.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#adler@1.0.2",
          "name": "adler",
          "version": "1.0.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler-1.0.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler-1.0.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#anyhow@1.0.75",
          "name": "anyhow",
          "version": "1.0.75",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\anyhow-1.0.75\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\anyhow-1.0.75"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
          "name": "autocfg",
          "version": "1.1.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.1.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#backtrace@0.3.69",
          "name": "backtrace",
          "version": "0.3.69",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\backtrace-0.3.69\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\backtrace-0.3.69"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#basic-toml@0.1.7",
          "name": "basic-toml",
          "version": "0.1.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\basic-toml-0.1.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\basic-toml-0.1.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
          "name": "bitflags",
          "version": "1.3.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
          "name": "cc",
          "version": "1.0.83",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.83\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.83"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#dissimilar@1.0.7",
          "name": "dissimilar",
          "version": "1.0.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dissimilar-1.0.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dissimilar-1.0.7"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
          "name": "eyre",
          "version": "0.6.12",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures@0.3.29",
          "name": "futures",
          "version": "0.3.29",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-0.3.29\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-0.3.29"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-channel@0.3.29",
          "name": "futures-channel",
          "version": "0.3.29",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-channel-0.3.29\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-channel-0.3.29"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.29",
          "name": "futures-core",
          "version": "0.3.29",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.29\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.29"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.29",
          "name": "futures-io",
          "version": "0.3.29",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-io-0.3.29\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-io-0.3.29"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-sink@0.3.29",
          "name": "futures-sink",
          "version": "0.3.29",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-sink-0.3.29\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-sink-0.3.29"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.29",
          "name": "futures-task",
          "version": "0.3.29",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.29\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.29"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.29",
          "name": "futures-util",
          "version": "0.3.29",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.29\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.29"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#gimli@0.28.1",
          "name": "gimli",
          "version": "0.28.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gimli-0.28.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gimli-0.28.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.1",
          "name": "glob",
          "version": "0.3.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\glob-0.3.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\glob-0.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#indenter@0.3.3",
          "name": "indenter",
          "version": "0.3.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#instant@0.1.12",
          "name": "instant",
          "version": "0.1.12",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\instant-0.1.12\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\instant-0.1.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.9",
          "name": "itoa",
          "version": "1.0.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.150",
          "name": "libc",
          "version": "0.2.150",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.150\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.150"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lock_api@0.4.11",
          "name": "lock_api",
          "version": "0.4.11",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lock_api-0.4.11\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lock_api-0.4.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.6.4",
          "name": "memchr",
          "version": "2.6.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.6.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.6.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.0",
          "name": "memoffset",
          "version": "0.9.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.9.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#miniz_oxide@0.7.1",
          "name": "miniz_oxide",
          "version": "0.7.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.7.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#object@0.32.1",
          "name": "object",
          "version": "0.32.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\object-0.32.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\object-0.32.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.18.0",
          "name": "once_cell",
          "version": "1.18.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot@0.11.2",
          "name": "parking_lot",
          "version": "0.11.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot-0.11.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot-0.11.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot_core@0.8.6",
          "name": "parking_lot_core",
          "version": "0.8.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot_core-0.8.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot_core-0.8.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.13",
          "name": "pin-project-lite",
          "version": "0.2.13",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.13\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.13"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-utils@0.1.0",
          "name": "pin-utils",
          "version": "0.1.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-utils-0.1.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-utils-0.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.70",
          "name": "proc-macro2",
          "version": "1.0.70",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.70\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.70"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pyo3@0.20.0",
          "name": "pyo3",
          "version": "0.20.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-0.20.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-0.20.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pyo3-build-config@0.20.0",
          "name": "pyo3-build-config",
          "version": "0.20.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-build-config-0.20.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-build-config-0.20.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pyo3-ffi@0.20.0",
          "name": "pyo3-ffi",
          "version": "0.20.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-ffi-0.20.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pyo3-ffi-0.20.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.33",
          "name": "quote",
          "version": "1.0.33",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.33\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.33"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.2.16",
          "name": "redox_syscall",
          "version": "0.2.16",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.2.16\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.2.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc-demangle@0.1.23",
          "name": "rustc-demangle",
          "version": "0.1.23",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc-demangle-0.1.23\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustc-demangle-0.1.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.14",
          "name": "rustversion",
          "version": "1.0.14",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.14\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.15",
          "name": "ryu",
          "version": "1.0.15",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.15\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
          "name": "scopeguard",
          "version": "1.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scopeguard-1.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scopeguard-1.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.193",
          "name": "serde",
          "version": "1.0.193",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.193\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.193"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.193",
          "name": "serde_derive",
          "version": "1.0.193",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.193\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.193"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.108",
          "name": "serde_json",
          "version": "1.0.108",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.108\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.108"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#smallvec@1.11.2",
          "name": "smallvec",
          "version": "1.11.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.11.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.11.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.39",
          "name": "syn",
          "version": "2.0.39",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.39\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.39"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-lexicon@0.12.12",
          "name": "target-lexicon",
          "version": "0.12.12",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\target-lexicon-0.12.12\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\target-lexicon-0.12.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.0",
          "name": "termcolor",
          "version": "1.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\termcolor-1.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\termcolor-1.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror@1.0.50",
          "name": "thiserror",
          "version": "1.0.50",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-1.0.50\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-1.0.50"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror-impl@1.0.50",
          "name": "thiserror-impl",
          "version": "1.0.50",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-1.0.50\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-1.0.50"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.85",
          "name": "trybuild",
          "version": "1.0.85",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\trybuild-1.0.85\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\trybuild-1.0.85"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
          "name": "unicode-ident",
          "version": "1.0.12",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.12\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.12"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
          "name": "winapi-util",
          "version": "0.1.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.6"
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1528,
      "ppid": 12296,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "eyre",
        "version": "0.6.12",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "eyre",
        "version": "0.6.12",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "cargo_pkg_name": "eyre",
      "cargo_pkg_version": "0.6.12",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1528,
      "ppid": 12296,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "_owner": {
        "crate": "eyre",
        "version": "0.6.12",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-15552-1783954260067\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\rustcClt7TH\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000200       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000250       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000270       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000340       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140030200     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000250       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140030250     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140030270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140030288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140030298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400302a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000340       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140030340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140030358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140030388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-link-link-1528-1783954262118861400.map",
      "pid": 1528,
      "ppid": 12296,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\.tmp\\native-trace-link-link-1528-1783954262118861400.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "eyre",
        "version": "0.6.12",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12#eyre@0.6.12",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-y1ey5g1z/src/eyre-0.6.12",
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
      "pid": 12152,
      "ppid": 13448,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:51:02.508953+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc\\build-script-build.exe",
      "root_cargo_pid": 12572,
      "build_script_root_pid": 12152,
      "build_script_related": true,
      "build_script_target_dir": "eyre-26c0449f5f93e3bc"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 8280,
      "ppid": 12152,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:51:02.517276+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 12572,
      "build_script_root_pid": 12152,
      "build_script_related": true,
      "build_script_target_dir": "eyre-26c0449f5f93e3bc"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 9872,
      "ppid": 12152,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:51:02.554815+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 12572,
      "build_script_root_pid": 12152,
      "build_script_related": true,
      "build_script_target_dir": "eyre-26c0449f5f93e3bc"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7760,
      "ppid": 12152,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:51:02.592582+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 12572,
      "build_script_root_pid": 12152,
      "build_script_related": true,
      "build_script_target_dir": "eyre-26c0449f5f93e3bc"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "eyre:0.6.12:14896",
      "root_process_pid": 12572,
      "pid": 10076,
      "ppid": 13760,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
      "time": "2026-07-13T14:51:00.243240+00:00",
      "end_time": "2026-07-13T14:51:00.260897+00:00",
      "start_unix_nanos": 1783954260243240400,
      "end_unix_nanos": 1783954260260897400,
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
      "run_id": "eyre:0.6.12:14896",
      "root_process_pid": 12572,
      "pid": 15020,
      "ppid": 13760,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
      "time": "2026-07-13T14:51:00.267418+00:00",
      "end_time": "2026-07-13T14:51:00.287971+00:00",
      "start_unix_nanos": 1783954260267418200,
      "end_unix_nanos": 1783954260287970800,
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
      "run_id": "eyre:0.6.12:14896",
      "root_process_pid": 12572,
      "pid": 16436,
      "ppid": 13448,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
      "time": "2026-07-13T14:51:01.789679+00:00",
      "end_time": "2026-07-13T14:51:01.805796+00:00",
      "start_unix_nanos": 1783954261789679300,
      "end_unix_nanos": 1783954261805795900,
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
      "run_id": "eyre:0.6.12:14896",
      "root_process_pid": 12572,
      "pid": 680,
      "ppid": 13448,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
      "time": "2026-07-13T14:51:01.811866+00:00",
      "end_time": "2026-07-13T14:51:01.831295+00:00",
      "start_unix_nanos": 1783954261811866300,
      "end_unix_nanos": 1783954261831295300,
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
      "run_id": "eyre:0.6.12:14896",
      "root_process_pid": 12572,
      "pid": 12500,
      "ppid": 13448,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
      "time": "2026-07-13T14:51:01.850565+00:00",
      "end_time": "2026-07-13T14:51:01.871570+00:00",
      "start_unix_nanos": 1783954261850565300,
      "end_unix_nanos": 1783954261871570300,
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
      "run_id": "eyre:0.6.12:14896",
      "root_process_pid": 12572,
      "pid": 10432,
      "ppid": 13448,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "indenter",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3\\src\\lib.rs",
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
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=9752679c3d9c3044",
        "-C",
        "extra-filename=-f5f7c836ec0819a6",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name indenter --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=9752679c3d9c3044 -C extra-filename=-f5f7c836ec0819a6 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "indenter",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indenter-0.3.3\\src\\lib.rs",
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
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=9752679c3d9c3044",
        "-C",
        "extra-filename=-f5f7c836ec0819a6",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:51:01.892114+00:00",
      "end_time": "2026-07-13T14:51:01.973838+00:00",
      "start_unix_nanos": 1783954261892114300,
      "end_unix_nanos": 1783954261973838200,
      "crate_name": "indenter",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "eyre:0.6.12:14896",
      "root_process_pid": 12572,
      "pid": 16204,
      "ppid": 13448,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "once_cell",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0\\src\\lib.rs",
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
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"race\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"atomic-polyfill\", \"critical-section\", \"default\", \"parking_lot\", \"race\", \"std\", \"unstable\"))",
        "-C",
        "metadata=b4f99540f5db8bab",
        "-C",
        "extra-filename=-667c8bd556635e4f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name once_cell --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"race\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"atomic-polyfill\\\", \\\"critical-section\\\", \\\"default\\\", \\\"parking_lot\\\", \\\"race\\\", \\\"std\\\", \\\"unstable\\\"))\" -C metadata=b4f99540f5db8bab -C extra-filename=-667c8bd556635e4f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "once_cell",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.18.0\\src\\lib.rs",
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
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"race\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"atomic-polyfill\", \"critical-section\", \"default\", \"parking_lot\", \"race\", \"std\", \"unstable\"))",
        "-C",
        "metadata=b4f99540f5db8bab",
        "-C",
        "extra-filename=-667c8bd556635e4f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:51:01.897316+00:00",
      "end_time": "2026-07-13T14:51:02.049332+00:00",
      "start_unix_nanos": 1783954261897315600,
      "end_unix_nanos": 1783954262049332400,
      "crate_name": "once_cell",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "eyre:0.6.12:14896",
      "root_process_pid": 12572,
      "pid": 1448,
      "ppid": 13448,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
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
        "feature=\"auto-install\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"track-caller\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"auto-install\", \"default\", \"pyo3\", \"track-caller\"))",
        "-C",
        "metadata=a46bd5b474986dc2",
        "-C",
        "extra-filename=-26c0449f5f93e3bc",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"auto-install\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"track-caller\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"auto-install\\\", \\\"default\\\", \\\"pyo3\\\", \\\"track-caller\\\"))\" -C metadata=a46bd5b474986dc2 -C extra-filename=-26c0449f5f93e3bc --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
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
        "feature=\"auto-install\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"track-caller\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"auto-install\", \"default\", \"pyo3\", \"track-caller\"))",
        "-C",
        "metadata=a46bd5b474986dc2",
        "-C",
        "extra-filename=-26c0449f5f93e3bc",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:51:01.899660+00:00",
      "end_time": "2026-07-13T14:51:02.423827+00:00",
      "start_unix_nanos": 1783954261899659700,
      "end_unix_nanos": 1783954262423827100,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\build\\eyre-26c0449f5f93e3bc"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "eyre:0.6.12:14896",
      "root_process_pid": 12572,
      "pid": 16064,
      "ppid": 13448,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "eyre",
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
        "feature=\"auto-install\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"track-caller\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"auto-install\", \"default\", \"pyo3\", \"track-caller\"))",
        "-C",
        "metadata=ed5df61ddb99bc1c",
        "-C",
        "extra-filename=-91ac3ce4aed9b61d",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "--extern",
        "indenter=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libindenter-f5f7c836ec0819a6.rmeta",
        "--extern",
        "once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libonce_cell-667c8bd556635e4f.rmeta",
        "--cfg",
        "track_caller",
        "--cfg",
        "stable"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name eyre --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"auto-install\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"track-caller\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"auto-install\\\", \\\"default\\\", \\\"pyo3\\\", \\\"track-caller\\\"))\" -C metadata=ed5df61ddb99bc1c -C extra-filename=-91ac3ce4aed9b61d --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps --extern indenter=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libindenter-f5f7c836ec0819a6.rmeta --extern once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libonce_cell-667c8bd556635e4f.rmeta --cfg track_caller --cfg stable",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "eyre",
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
        "feature=\"auto-install\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"track-caller\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"auto-install\", \"default\", \"pyo3\", \"track-caller\"))",
        "-C",
        "metadata=ed5df61ddb99bc1c",
        "-C",
        "extra-filename=-91ac3ce4aed9b61d",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps",
        "--extern",
        "indenter=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libindenter-f5f7c836ec0819a6.rmeta",
        "--extern",
        "once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps\\libonce_cell-667c8bd556635e4f.rmeta",
        "--cfg",
        "track_caller",
        "--cfg",
        "stable"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:51:02.616690+00:00",
      "end_time": "2026-07-13T14:51:03.200672+00:00",
      "start_unix_nanos": 1783954262616689600,
      "end_unix_nanos": 1783954263200672200,
      "crate_name": "eyre",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-y1ey5g1z\\src\\eyre-0.6.12\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 551,
    "crate": "eyre",
    "version": "0.6.12",
    "crate_id": "205184",
    "version_id": "1034815",
    "downloads": 53072039,
    "cumulative_downloads": 73904902382,
    "cumulative_share_of_global": 0.2763133686298135,
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
