# `winit` `0.29.15`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "winit",
    "version": "0.29.15",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140027148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140027198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400271b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400271d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400271e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400271f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140027288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400272a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400272b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-15912-1783961319455906700.map",
  "pid": 15912,
  "ppid": 3632,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-15912-1783961319455906700.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "winit",
    "version": "0.29.15",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ab_glyph@0.2.23",
      "name": "ab_glyph",
      "version": "0.2.23",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ab_glyph-0.2.23\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ab_glyph-0.2.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ab_glyph_rasterizer@0.1.8",
      "name": "ab_glyph_rasterizer",
      "version": "0.1.8",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ab_glyph_rasterizer-0.1.8\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ab_glyph_rasterizer-0.1.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#adler@1.0.2",
      "name": "adler",
      "version": "1.0.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler-1.0.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler-1.0.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ahash@0.8.7",
      "name": "ahash",
      "version": "0.8.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ahash-0.8.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ahash-0.8.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#android-activity@0.5.2",
      "name": "android-activity",
      "version": "0.5.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\android-activity-0.5.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\android-activity-0.5.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#android-properties@0.2.2",
      "name": "android-properties",
      "version": "0.2.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\android-properties-0.2.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\android-properties-0.2.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayref@0.3.7",
      "name": "arrayref",
      "version": "0.3.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayvec@0.7.4",
      "name": "arrayvec",
      "version": "0.7.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#as-raw-xcb-connection@1.0.1",
      "name": "as-raw-xcb-connection",
      "version": "1.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\as-raw-xcb-connection-1.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\as-raw-xcb-connection-1.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#atomic-waker@1.1.2",
      "name": "atomic-waker",
      "version": "1.1.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atomic-waker-1.1.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atomic-waker-1.1.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
      "name": "autocfg",
      "version": "1.1.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.1.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
      "name": "bitflags",
      "version": "1.3.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.4.2",
      "name": "bitflags",
      "version": "2.4.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#block@0.1.6",
      "name": "block",
      "version": "0.1.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-0.1.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-0.1.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#block-sys@0.2.1",
      "name": "block-sys",
      "version": "0.2.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-sys-0.2.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-sys-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#block2@0.3.0",
      "name": "block2",
      "version": "0.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block2-0.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block2-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
      "name": "bumpalo",
      "version": "3.14.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.14.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.14.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bytemuck@1.14.2",
      "name": "bytemuck",
      "version": "1.14.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytemuck-1.14.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytemuck-1.14.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bytemuck_derive@1.6.0",
      "name": "bytemuck_derive",
      "version": "1.6.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytemuck_derive-1.6.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytemuck_derive-1.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#byteorder@1.5.0",
      "name": "byteorder",
      "version": "1.5.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\byteorder-1.5.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\byteorder-1.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bytes@1.5.0",
      "name": "bytes",
      "version": "1.5.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytes-1.5.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytes-1.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#calloop@0.12.4",
      "name": "calloop",
      "version": "0.12.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\calloop-0.12.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\calloop-0.12.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#calloop-wayland-source@0.2.0",
      "name": "calloop-wayland-source",
      "version": "0.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\calloop-wayland-source-0.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\calloop-wayland-source-0.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
      "name": "cc",
      "version": "1.0.83",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.83\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.83"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cesu8@1.1.0",
      "name": "cesu8",
      "version": "1.1.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cesu8-1.1.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cesu8-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg_aliases@0.1.1",
      "name": "cfg_aliases",
      "version": "0.1.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cocoa@0.25.0",
      "name": "cocoa",
      "version": "0.25.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cocoa-0.25.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cocoa-0.25.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cocoa-foundation@0.1.2",
      "name": "cocoa-foundation",
      "version": "0.1.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cocoa-foundation-0.1.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cocoa-foundation-0.1.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#color_quant@1.1.0",
      "name": "color_quant",
      "version": "1.1.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\color_quant-1.1.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\color_quant-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#combine@4.6.6",
      "name": "combine",
      "version": "4.6.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\combine-4.6.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\combine-4.6.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#concurrent-queue@2.4.0",
      "name": "concurrent-queue",
      "version": "2.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\concurrent-queue-2.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\concurrent-queue-2.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#console_log@1.0.0",
      "name": "console_log",
      "version": "1.0.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\console_log-1.0.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\console_log-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-foundation@0.9.4",
      "name": "core-foundation",
      "version": "0.9.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-foundation-0.9.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-foundation-0.9.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-foundation-sys@0.8.6",
      "name": "core-foundation-sys",
      "version": "0.8.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-foundation-sys-0.8.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-foundation-sys-0.8.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-graphics@0.23.1",
      "name": "core-graphics",
      "version": "0.23.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-graphics-0.23.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-graphics-0.23.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-graphics-types@0.1.3",
      "name": "core-graphics-types",
      "version": "0.1.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-graphics-types-0.1.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-graphics-types-0.1.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crc32fast@1.3.2",
      "name": "crc32fast",
      "version": "1.3.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crc32fast-1.3.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crc32fast-1.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.19",
      "name": "crossbeam-utils",
      "version": "0.8.19",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.19\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ctor@0.2.6",
      "name": "ctor",
      "version": "0.2.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ctor-0.2.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ctor-0.2.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cursor-icon@1.1.0",
      "name": "cursor-icon",
      "version": "1.1.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#dispatch@0.2.0",
      "name": "dispatch",
      "version": "0.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dispatch-0.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dispatch-0.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#dlib@0.5.2",
      "name": "dlib",
      "version": "0.5.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dlib-0.5.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dlib-0.5.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#downcast-rs@1.2.0",
      "name": "downcast-rs",
      "version": "1.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\downcast-rs-1.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\downcast-rs-1.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm@0.11.1",
      "name": "drm",
      "version": "0.11.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-0.11.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-0.11.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm-ffi@0.7.1",
      "name": "drm-ffi",
      "version": "0.7.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-ffi-0.7.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-ffi-0.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm-fourcc@2.2.0",
      "name": "drm-fourcc",
      "version": "2.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-fourcc-2.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-fourcc-2.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm-sys@0.6.1",
      "name": "drm-sys",
      "version": "0.6.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-sys-0.6.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-sys-0.6.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.1",
      "name": "equivalent",
      "version": "1.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.8",
      "name": "errno",
      "version": "0.3.8",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.8\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.0.1",
      "name": "fastrand",
      "version": "2.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fdeflate@0.3.4",
      "name": "fdeflate",
      "version": "0.3.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fdeflate-0.3.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fdeflate-0.3.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#flate2@1.0.28",
      "name": "flate2",
      "version": "1.0.28",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\flate2-1.0.28\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\flate2-1.0.28"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#foreign-types@0.5.0",
      "name": "foreign-types",
      "version": "0.5.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-0.5.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-0.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#foreign-types-macros@0.2.3",
      "name": "foreign-types-macros",
      "version": "0.2.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-macros-0.2.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-macros-0.2.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#foreign-types-shared@0.3.1",
      "name": "foreign-types-shared",
      "version": "0.3.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-shared-0.3.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-shared-0.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#gethostname@0.3.0",
      "name": "gethostname",
      "version": "0.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gethostname-0.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gethostname-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#gethostname@0.4.3",
      "name": "gethostname",
      "version": "0.4.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gethostname-0.4.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gethostname-0.4.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.12",
      "name": "getrandom",
      "version": "0.2.12",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.2.12\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.2.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.14.3",
      "name": "hashbrown",
      "version": "0.14.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.14.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.14.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#icrate@0.0.4",
      "name": "icrate",
      "version": "0.0.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\icrate-0.0.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\icrate-0.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#image@0.24.8",
      "name": "image",
      "version": "0.24.8",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\image-0.24.8\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\image-0.24.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.2.2",
      "name": "indexmap",
      "version": "2.2.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.2.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.2.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#jni@0.21.1",
      "name": "jni",
      "version": "0.21.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jni-0.21.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jni-0.21.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#jni-sys@0.3.0",
      "name": "jni-sys",
      "version": "0.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jni-sys-0.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jni-sys-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#jobserver@0.1.27",
      "name": "jobserver",
      "version": "0.1.27",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jobserver-0.1.27\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jobserver-0.1.27"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.68",
      "name": "js-sys",
      "version": "0.3.68",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.68\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.68"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
      "name": "libc",
      "version": "0.2.153",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.153\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.153"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.7.4",
      "name": "libloading",
      "version": "0.7.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libloading-0.7.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libloading-0.7.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.8.1",
      "name": "libloading",
      "version": "0.8.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libloading-0.8.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libloading-0.8.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libredox@0.0.2",
      "name": "libredox",
      "version": "0.0.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libredox-0.0.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libredox-0.0.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.13",
      "name": "linux-raw-sys",
      "version": "0.4.13",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.4.13\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.4.13"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.6.4",
      "name": "linux-raw-sys",
      "version": "0.6.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.6.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.6.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
      "name": "log",
      "version": "0.4.20",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#malloc_buf@0.0.6",
      "name": "malloc_buf",
      "version": "0.0.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\malloc_buf-0.0.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\malloc_buf-0.0.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.1",
      "name": "memchr",
      "version": "2.7.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memmap2@0.9.4",
      "name": "memmap2",
      "version": "0.9.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memmap2-0.9.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memmap2-0.9.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.7.1",
      "name": "memoffset",
      "version": "0.7.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.7.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#miniz_oxide@0.7.2",
      "name": "miniz_oxide",
      "version": "0.7.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.7.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.7.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ndk@0.8.0",
      "name": "ndk",
      "version": "0.8.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-0.8.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-0.8.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ndk-context@0.1.1",
      "name": "ndk-context",
      "version": "0.1.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-context-0.1.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-context-0.1.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ndk-sys@0.5.0+25.2.9519653",
      "name": "ndk-sys",
      "version": "0.5.0+25.2.9519653",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-sys-0.5.0+25.2.9519653\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-sys-0.5.0+25.2.9519653"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#nix@0.26.4",
      "name": "nix",
      "version": "0.26.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\nix-0.26.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\nix-0.26.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
      "name": "num-traits",
      "version": "0.2.18",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.18\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num_enum@0.7.2",
      "name": "num_enum",
      "version": "0.7.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num_enum-0.7.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num_enum-0.7.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num_enum_derive@0.7.2",
      "name": "num_enum_derive",
      "version": "0.7.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num_enum_derive-0.7.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num_enum_derive-0.7.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc@0.2.7",
      "name": "objc",
      "version": "0.2.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc-0.2.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc-0.2.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc-sys@0.3.2",
      "name": "objc-sys",
      "version": "0.3.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc-sys-0.3.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc-sys-0.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc2@0.4.1",
      "name": "objc2",
      "version": "0.4.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc2-0.4.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc2-0.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc2-encode@3.0.0",
      "name": "objc2-encode",
      "version": "3.0.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc2-encode-3.0.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc2-encode-3.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.19.0",
      "name": "once_cell",
      "version": "1.19.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#orbclient@0.3.47",
      "name": "orbclient",
      "version": "0.3.47",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\orbclient-0.3.47\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\orbclient-0.3.47"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#owned_ttf_parser@0.20.0",
      "name": "owned_ttf_parser",
      "version": "0.20.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\owned_ttf_parser-0.20.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\owned_ttf_parser-0.20.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#percent-encoding@2.3.1",
      "name": "percent-encoding",
      "version": "2.3.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\percent-encoding-2.3.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\percent-encoding-2.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.13",
      "name": "pin-project-lite",
      "version": "0.2.13",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.13\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.13"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.29",
      "name": "pkg-config",
      "version": "0.3.29",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.29\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.29"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#png@0.17.11",
      "name": "png",
      "version": "0.17.11",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\png-0.17.11\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\png-0.17.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#polling@3.4.0",
      "name": "polling",
      "version": "3.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\polling-3.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\polling-3.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro-crate@1.3.1",
      "name": "proc-macro-crate",
      "version": "1.3.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro-crate-1.3.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro-crate-1.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.78",
      "name": "proc-macro2",
      "version": "1.0.78",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.78\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.78"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quick-xml@0.31.0",
      "name": "quick-xml",
      "version": "0.31.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quick-xml-0.31.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quick-xml-0.31.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.35",
      "name": "quote",
      "version": "1.0.35",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.35\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.35"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#raw-window-handle@0.5.2",
      "name": "raw-window-handle",
      "version": "0.5.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.5.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.5.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#raw-window-handle@0.6.0",
      "name": "raw-window-handle",
      "version": "0.6.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.3.5",
      "name": "redox_syscall",
      "version": "0.3.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.3.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.4.1",
      "name": "redox_syscall",
      "version": "0.4.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.4.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.31",
      "name": "rustix",
      "version": "0.38.31",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-0.38.31\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-0.38.31"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
      "name": "same-file",
      "version": "1.0.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#scoped-tls@1.0.1",
      "name": "scoped-tls",
      "version": "1.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scoped-tls-1.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scoped-tls-1.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#sctk-adwaita@0.8.1",
      "name": "sctk-adwaita",
      "version": "0.8.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\sctk-adwaita-0.8.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\sctk-adwaita-0.8.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.196",
      "name": "serde",
      "version": "1.0.196",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.196\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.196"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.196",
      "name": "serde_derive",
      "version": "1.0.196",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.196\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.196"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#simd-adler32@0.3.7",
      "name": "simd-adler32",
      "version": "0.3.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\simd-adler32-0.3.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\simd-adler32-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#simple_logger@4.3.3",
      "name": "simple_logger",
      "version": "4.3.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\simple_logger-4.3.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\simple_logger-4.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.9",
      "name": "slab",
      "version": "0.4.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#smallvec@1.13.1",
      "name": "smallvec",
      "version": "1.13.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.13.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.13.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#smithay-client-toolkit@0.18.0",
      "name": "smithay-client-toolkit",
      "version": "0.18.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smithay-client-toolkit-0.18.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smithay-client-toolkit-0.18.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#smol_str@0.2.1",
      "name": "smol_str",
      "version": "0.2.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#softbuffer@0.3.4",
      "name": "softbuffer",
      "version": "0.3.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\softbuffer-0.3.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\softbuffer-0.3.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#strict-num@0.1.1",
      "name": "strict-num",
      "version": "0.1.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\strict-num-0.1.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\strict-num-0.1.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.48",
      "name": "syn",
      "version": "2.0.48",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.48\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.48"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror@1.0.56",
      "name": "thiserror",
      "version": "1.0.56",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-1.0.56\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-1.0.56"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror-impl@1.0.56",
      "name": "thiserror-impl",
      "version": "1.0.56",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-1.0.56\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-1.0.56"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tiny-skia@0.11.4",
      "name": "tiny-skia",
      "version": "0.11.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-skia-0.11.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-skia-0.11.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tiny-skia-path@0.11.4",
      "name": "tiny-skia-path",
      "version": "0.11.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-skia-path-0.11.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-skia-path-0.11.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tiny-xlib@0.2.2",
      "name": "tiny-xlib",
      "version": "0.2.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-xlib-0.2.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-xlib-0.2.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@0.6.5",
      "name": "toml_datetime",
      "version": "0.6.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_datetime-0.6.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_datetime-0.6.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_edit@0.19.15",
      "name": "toml_edit",
      "version": "0.19.15",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_edit-0.19.15\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_edit-0.19.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tracing@0.1.40",
      "name": "tracing",
      "version": "0.1.40",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tracing-0.1.40\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tracing-0.1.40"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tracing-core@0.1.32",
      "name": "tracing-core",
      "version": "0.1.32",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tracing-core-0.1.32\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tracing-core-0.1.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ttf-parser@0.20.0",
      "name": "ttf-parser",
      "version": "0.20.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ttf-parser-0.20.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ttf-parser-0.20.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
      "name": "unicode-ident",
      "version": "1.0.12",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.12\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-segmentation@1.11.0",
      "name": "unicode-segmentation",
      "version": "1.11.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.4",
      "name": "version_check",
      "version": "0.9.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\version_check-0.9.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\version_check-0.9.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.4.0",
      "name": "walkdir",
      "version": "2.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
      "name": "wasi",
      "version": "0.11.0+wasi-snapshot-preview1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.11.0+wasi-snapshot-preview1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.11.0+wasi-snapshot-preview1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.91",
      "name": "wasm-bindgen",
      "version": "0.2.91",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.91\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.91"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.91",
      "name": "wasm-bindgen-backend",
      "version": "0.2.91",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-backend-0.2.91\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-backend-0.2.91"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-futures@0.4.41",
      "name": "wasm-bindgen-futures",
      "version": "0.4.41",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-futures-0.4.41\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-futures-0.4.41"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.91",
      "name": "wasm-bindgen-macro",
      "version": "0.2.91",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.91\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.91"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.91",
      "name": "wasm-bindgen-macro-support",
      "version": "0.2.91",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.91\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.91"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.91",
      "name": "wasm-bindgen-shared",
      "version": "0.2.91",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.91\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.91"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-backend@0.3.3",
      "name": "wayland-backend",
      "version": "0.3.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-backend-0.3.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-backend-0.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-client@0.31.2",
      "name": "wayland-client",
      "version": "0.31.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-client-0.31.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-client-0.31.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-csd-frame@0.3.0",
      "name": "wayland-csd-frame",
      "version": "0.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-csd-frame-0.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-csd-frame-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-cursor@0.31.1",
      "name": "wayland-cursor",
      "version": "0.31.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-cursor-0.31.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-cursor-0.31.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-protocols@0.31.2",
      "name": "wayland-protocols",
      "version": "0.31.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-0.31.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-0.31.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-protocols-plasma@0.2.0",
      "name": "wayland-protocols-plasma",
      "version": "0.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-plasma-0.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-plasma-0.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-protocols-wlr@0.2.0",
      "name": "wayland-protocols-wlr",
      "version": "0.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-wlr-0.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-wlr-0.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-scanner@0.31.1",
      "name": "wayland-scanner",
      "version": "0.31.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-scanner-0.31.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-scanner-0.31.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-sys@0.31.1",
      "name": "wayland-sys",
      "version": "0.31.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-sys-0.31.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-sys-0.31.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.68",
      "name": "web-sys",
      "version": "0.3.68",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.68\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.68"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-time@0.2.4",
      "name": "web-time",
      "version": "0.2.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-time-0.2.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-time-0.2.4"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-wsapoll@0.1.1",
      "name": "winapi-wsapoll",
      "version": "0.1.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-wsapoll-0.1.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-wsapoll-0.1.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
      "name": "winapi-x86_64-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.45.0",
      "name": "windows-sys",
      "version": "0.45.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.45.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.45.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.48.0",
      "name": "windows-sys",
      "version": "0.48.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.52.0",
      "name": "windows-sys",
      "version": "0.52.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.52.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.52.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.42.2",
      "name": "windows-targets",
      "version": "0.42.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.42.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.42.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.48.5",
      "name": "windows-targets",
      "version": "0.48.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.0",
      "name": "windows-targets",
      "version": "0.52.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.42.2",
      "name": "windows_aarch64_gnullvm",
      "version": "0.42.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.42.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.42.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.48.5",
      "name": "windows_aarch64_gnullvm",
      "version": "0.48.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.48.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.0",
      "name": "windows_aarch64_gnullvm",
      "version": "0.52.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.52.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.52.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.42.2",
      "name": "windows_aarch64_msvc",
      "version": "0.42.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.42.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.42.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.48.5",
      "name": "windows_aarch64_msvc",
      "version": "0.48.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.48.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.0",
      "name": "windows_aarch64_msvc",
      "version": "0.52.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.52.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.52.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.42.2",
      "name": "windows_i686_gnu",
      "version": "0.42.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.42.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.42.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.48.5",
      "name": "windows_i686_gnu",
      "version": "0.48.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.48.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.0",
      "name": "windows_i686_gnu",
      "version": "0.52.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.52.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.52.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.42.2",
      "name": "windows_i686_msvc",
      "version": "0.42.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.42.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.42.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.48.5",
      "name": "windows_i686_msvc",
      "version": "0.48.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.48.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.0",
      "name": "windows_i686_msvc",
      "version": "0.52.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.52.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.52.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.42.2",
      "name": "windows_x86_64_gnu",
      "version": "0.42.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.42.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.42.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.48.5",
      "name": "windows_x86_64_gnu",
      "version": "0.48.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.48.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.0",
      "name": "windows_x86_64_gnu",
      "version": "0.52.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.52.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.52.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.42.2",
      "name": "windows_x86_64_gnullvm",
      "version": "0.42.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.42.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.42.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.48.5",
      "name": "windows_x86_64_gnullvm",
      "version": "0.48.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.48.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.0",
      "name": "windows_x86_64_gnullvm",
      "version": "0.52.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.52.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.52.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.42.2",
      "name": "windows_x86_64_msvc",
      "version": "0.42.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.42.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.42.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
      "name": "windows_x86_64_msvc",
      "version": "0.48.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.0",
      "name": "windows_x86_64_msvc",
      "version": "0.52.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.0"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
      "name": "winit",
      "version": "0.29.15",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@0.5.39",
      "name": "winnow",
      "version": "0.5.39",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winnow-0.5.39\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winnow-0.5.39"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11-dl@2.21.0",
      "name": "x11-dl",
      "version": "2.21.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11-dl-2.21.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11-dl-2.21.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb@0.12.0",
      "name": "x11rb",
      "version": "0.12.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-0.12.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-0.12.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb@0.13.0",
      "name": "x11rb",
      "version": "0.13.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-0.13.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-0.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb-protocol@0.12.0",
      "name": "x11rb-protocol",
      "version": "0.12.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-protocol-0.12.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-protocol-0.12.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb-protocol@0.13.0",
      "name": "x11rb-protocol",
      "version": "0.13.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-protocol-0.13.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-protocol-0.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#xcursor@0.3.5",
      "name": "xcursor",
      "version": "0.3.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xcursor-0.3.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xcursor-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#xkbcommon-dl@0.4.2",
      "name": "xkbcommon-dl",
      "version": "0.4.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xkbcommon-dl-0.4.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xkbcommon-dl-0.4.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#xkeysym@0.2.0",
      "name": "xkeysym",
      "version": "0.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xkeysym-0.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xkeysym-0.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy@0.7.32",
      "name": "zerocopy",
      "version": "0.7.32",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-0.7.32\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-0.7.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy-derive@0.7.32",
      "name": "zerocopy-derive",
      "version": "0.7.32",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-derive-0.7.32\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-derive-0.7.32"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17348,
  "ppid": 6468,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:afba339e1afeea72:386a9de7aa2301cd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
  "pid": 17348,
  "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:72442d78d66b2f5c:386a9de7aa2301cd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
  "pid": 17348,
  "sha256": "59f62eb15f6d83ac62ef451179ce318623825939c8ba5b446fc2b514836f4d08",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:c0b293330aa97d47:386a9de7aa2301cd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
  "pid": 17348,
  "sha256": "f8422d6d05925df913081382846c65efd458d0db01b1770342457c42cbabede0",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:1ceda9c220daf075:386a9de7aa2301cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "kernel32.lib",
  "pid": 17348,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:1ceda9c220daf075:386a9de7aa2301cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "kernel32.lib",
  "pid": 17348,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:1ceda9c220daf075:386a9de7aa2301cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "kernel32.lib",
  "pid": 17348,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:1db9512c4d5c31e6:386a9de7aa2301cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "ntdll.lib",
  "pid": 17348,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:861f0814f9c52599:386a9de7aa2301cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "userenv.lib",
  "pid": 17348,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:50848825683fdca9:386a9de7aa2301cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "ws2_32.lib",
  "pid": 17348,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "used:link:6b43f26fd17962e1:df7d4e53c08047f7:386a9de7aa2301cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "path": "dbghelp.lib",
  "pid": 17348,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib"
  ],
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.48.5",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 17348,
  "ppid": 6468,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "directories": [
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000148       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000198       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000288       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-17348-1783961319258456300.map",
  "pid": 17348,
  "ppid": 6468,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-17348-1783961319258456300.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15912,
  "ppid": 3632,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "winit",
    "version": "0.29.15",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "winit",
    "version": "0.29.15",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "cargo_pkg_name": "winit",
  "cargo_pkg_version": "0.29.15",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 15912,
  "ppid": 3632,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "_owner": {
    "crate": "winit",
    "version": "0.29.15",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140027148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140027198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400271b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400271d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400271e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400271f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140027288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400272a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400272b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-15912-1783961319455906700.map",
  "pid": 15912,
  "ppid": 3632,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-15912-1783961319455906700.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "winit",
    "version": "0.29.15",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "crate": "windows_x86_64_msvc",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "event_id": "bsrun:c40213baefe8fbb9:8f05b09d80a10b7e:f8fa522367f92fec",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15/target/debug/build/windows_x86_64_msvc-17383b75150b7180\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15/target/debug/build/windows_x86_64_msvc-17383b75150b7180/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
  "success": true,
  "target": null,
  "version": "0.48.5",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 21

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
  "raw_event_count": 15175,
  "parsed_event_count": 15175,
  "parse_error_count": 0,
  "command_line_event_count": 15175,
  "build_script_root_event_count": 346,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 1350,
  "dropped_event_count": 7854
}
```

#### Record 22

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16064,
  "ppid": 9664,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T16:48:39.460671+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build-script-build.exe",
  "root_cargo_pid": 8280,
  "build_script_root_pid": 16064,
  "build_script_related": true,
  "build_script_target_dir": "windows_x86_64_msvc-17383b75150b7180",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.48.5",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15/target/debug/build/windows_x86_64_msvc-17383b75150b7180/out"
}
```

#### Record 23

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 10856,
  "ppid": 9664,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T16:48:39.886119+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\build-script-build.exe",
  "root_cargo_pid": 8280,
  "build_script_root_pid": 10856,
  "build_script_related": true,
  "build_script_target_dir": "winit-717c5d300b98a4e3"
}
```

#### Record 24

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 20580,
  "ppid": 13052,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
  "time": "2026-07-13T16:48:32.881089+00:00",
  "end_time": "2026-07-13T16:48:32.900764+00:00",
  "start_unix_nanos": 1783961312881089500,
  "end_unix_nanos": 1783961312900763600,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 25

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 3280,
  "ppid": 13052,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
  "time": "2026-07-13T16:48:32.907386+00:00",
  "end_time": "2026-07-13T16:48:32.927854+00:00",
  "start_unix_nanos": 1783961312907385600,
  "end_unix_nanos": 1783961312927854300,
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

#### Record 26

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 17556,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
  "time": "2026-07-13T16:48:38.956205+00:00",
  "end_time": "2026-07-13T16:48:38.975552+00:00",
  "start_unix_nanos": 1783961318956205100,
  "end_unix_nanos": 1783961318975552000,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 27

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 21252,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
  "time": "2026-07-13T16:48:38.983271+00:00",
  "end_time": "2026-07-13T16:48:39.007308+00:00",
  "start_unix_nanos": 1783961318983270700,
  "end_unix_nanos": 1783961319007308000,
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

#### Record 28

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 7300,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
  "time": "2026-07-13T16:48:39.057383+00:00",
  "end_time": "2026-07-13T16:48:39.076129+00:00",
  "start_unix_nanos": 1783961319057382500,
  "end_unix_nanos": 1783961319076128700,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 29

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 15704,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\build.rs",
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
    "metadata=6db132d4d00a965f",
    "-C",
    "extra-filename=-17383b75150b7180",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=6db132d4d00a965f -C extra-filename=-17383b75150b7180 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\build.rs",
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
    "metadata=6db132d4d00a965f",
    "-C",
    "extra-filename=-17383b75150b7180",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.105130+00:00",
  "end_time": "2026-07-13T16:48:39.367442+00:00",
  "start_unix_nanos": 1783961319105129900,
  "end_unix_nanos": 1783961319367442100,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180"
}
```

#### Record 30

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 9192,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cfg_aliases",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1\\src\\lib.rs",
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
    "metadata=71aaad46bdefbb7a",
    "-C",
    "extra-filename=-58fc099ce75d46bd",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cfg_aliases --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=71aaad46bdefbb7a -C extra-filename=-58fc099ce75d46bd --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cfg_aliases",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1\\src\\lib.rs",
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
    "metadata=71aaad46bdefbb7a",
    "-C",
    "extra-filename=-58fc099ce75d46bd",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.108201+00:00",
  "end_time": "2026-07-13T16:48:39.173235+00:00",
  "start_unix_nanos": 1783961319108200500,
  "end_unix_nanos": 1783961319173235200,
  "crate_name": "cfg_aliases",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 31

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 836,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cursor_icon",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0\\src\\lib.rs",
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
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"serde\", \"std\"))",
    "-C",
    "metadata=d31e111c2d3a29f0",
    "-C",
    "extra-filename=-7064bb38659984d2",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cursor_icon --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=d31e111c2d3a29f0 -C extra-filename=-7064bb38659984d2 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cursor_icon",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0\\src\\lib.rs",
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
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"serde\", \"std\"))",
    "-C",
    "metadata=d31e111c2d3a29f0",
    "-C",
    "extra-filename=-7064bb38659984d2",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.110804+00:00",
  "end_time": "2026-07-13T16:48:39.210739+00:00",
  "start_unix_nanos": 1783961319110803600,
  "end_unix_nanos": 1783961319210739200,
  "crate_name": "cursor_icon",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 32

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 18996,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "unicode_segmentation",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0\\src\\lib.rs",
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
    "cfg(feature, values(\"no_std\"))",
    "-C",
    "metadata=7a34b5f1be54d454",
    "-C",
    "extra-filename=-82c365516f112666",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name unicode_segmentation --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"no_std\\\"))\" -C metadata=7a34b5f1be54d454 -C extra-filename=-82c365516f112666 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "unicode_segmentation",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0\\src\\lib.rs",
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
    "cfg(feature, values(\"no_std\"))",
    "-C",
    "metadata=7a34b5f1be54d454",
    "-C",
    "extra-filename=-82c365516f112666",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.113660+00:00",
  "end_time": "2026-07-13T16:48:39.453711+00:00",
  "start_unix_nanos": 1783961319113659900,
  "end_unix_nanos": 1783961319453710700,
  "crate_name": "unicode_segmentation",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 33

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 5428,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "bitflags",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2\\src\\lib.rs",
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
    "cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std\"))",
    "-C",
    "metadata=9c7ce8c554b06bba",
    "-C",
    "extra-filename=-0667b619dfc545b1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name bitflags --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"bytemuck\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"example_generated\\\", \\\"rustc-dep-of-std\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=9c7ce8c554b06bba -C extra-filename=-0667b619dfc545b1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "bitflags",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2\\src\\lib.rs",
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
    "cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std\"))",
    "-C",
    "metadata=9c7ce8c554b06bba",
    "-C",
    "extra-filename=-0667b619dfc545b1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.116404+00:00",
  "end_time": "2026-07-13T16:48:39.284625+00:00",
  "start_unix_nanos": 1783961319116404300,
  "end_unix_nanos": 1783961319284624500,
  "crate_name": "bitflags",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 34

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 16244,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "once_cell",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0\\src\\lib.rs",
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
    "cfg(feature, values(\"alloc\", \"atomic-polyfill\", \"critical-section\", \"default\", \"parking_lot\", \"portable-atomic\", \"race\", \"std\", \"unstable\"))",
    "-C",
    "metadata=b67124b64dad4f71",
    "-C",
    "extra-filename=-d076018eae555cad",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name once_cell --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"race\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"atomic-polyfill\\\", \\\"critical-section\\\", \\\"default\\\", \\\"parking_lot\\\", \\\"portable-atomic\\\", \\\"race\\\", \\\"std\\\", \\\"unstable\\\"))\" -C metadata=b67124b64dad4f71 -C extra-filename=-d076018eae555cad --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "once_cell",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0\\src\\lib.rs",
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
    "cfg(feature, values(\"alloc\", \"atomic-polyfill\", \"critical-section\", \"default\", \"parking_lot\", \"portable-atomic\", \"race\", \"std\", \"unstable\"))",
    "-C",
    "metadata=b67124b64dad4f71",
    "-C",
    "extra-filename=-d076018eae555cad",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.119662+00:00",
  "end_time": "2026-07-13T16:48:39.275128+00:00",
  "start_unix_nanos": 1783961319119662400,
  "end_unix_nanos": 1783961319275127700,
  "crate_name": "once_cell",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 35

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 16100,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "log",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20\\src\\lib.rs",
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
    "cfg(feature, values(\"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_error\", \"max_level_info\", \"max_level_off\", \"max_level_trace\", \"max_level_warn\", \"release_max_level_debug\", \"release_max_level_error\", \"release_max_level_info\", \"release_max_level_off\", \"release_max_level_trace\", \"release_max_level_warn\", \"serde\", \"std\", \"sval\", \"sval_ref\", \"value-bag\"))",
    "-C",
    "metadata=b7e189e74a236304",
    "-C",
    "extra-filename=-c49eeec8812cf892",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name log --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"kv_unstable\\\", \\\"kv_unstable_serde\\\", \\\"kv_unstable_std\\\", \\\"kv_unstable_sval\\\", \\\"max_level_debug\\\", \\\"max_level_error\\\", \\\"max_level_info\\\", \\\"max_level_off\\\", \\\"max_level_trace\\\", \\\"max_level_warn\\\", \\\"release_max_level_debug\\\", \\\"release_max_level_error\\\", \\\"release_max_level_info\\\", \\\"release_max_level_off\\\", \\\"release_max_level_trace\\\", \\\"release_max_level_warn\\\", \\\"serde\\\", \\\"std\\\", \\\"sval\\\", \\\"sval_ref\\\", \\\"value-bag\\\"))\" -C metadata=b7e189e74a236304 -C extra-filename=-c49eeec8812cf892 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "log",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20\\src\\lib.rs",
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
    "cfg(feature, values(\"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_error\", \"max_level_info\", \"max_level_off\", \"max_level_trace\", \"max_level_warn\", \"release_max_level_debug\", \"release_max_level_error\", \"release_max_level_info\", \"release_max_level_off\", \"release_max_level_trace\", \"release_max_level_warn\", \"serde\", \"std\", \"sval\", \"sval_ref\", \"value-bag\"))",
    "-C",
    "metadata=b7e189e74a236304",
    "-C",
    "extra-filename=-c49eeec8812cf892",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.122745+00:00",
  "end_time": "2026-07-13T16:48:39.278522+00:00",
  "start_unix_nanos": 1783961319122744500,
  "end_unix_nanos": 1783961319278522400,
  "crate_name": "log",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 36

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 20548,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "raw_window_handle",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0\\src\\lib.rs",
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
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"std\", \"wasm-bindgen\", \"wasm-bindgen-0-2\"))",
    "-C",
    "metadata=fb00f7ee4ae98682",
    "-C",
    "extra-filename=-8084b02d24173edc",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name raw_window_handle --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"std\\\", \\\"wasm-bindgen\\\", \\\"wasm-bindgen-0-2\\\"))\" -C metadata=fb00f7ee4ae98682 -C extra-filename=-8084b02d24173edc --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "raw_window_handle",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0\\src\\lib.rs",
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
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"std\", \"wasm-bindgen\", \"wasm-bindgen-0-2\"))",
    "-C",
    "metadata=fb00f7ee4ae98682",
    "-C",
    "extra-filename=-8084b02d24173edc",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.125971+00:00",
  "end_time": "2026-07-13T16:48:39.303971+00:00",
  "start_unix_nanos": 1783961319125971300,
  "end_unix_nanos": 1783961319303971100,
  "crate_name": "raw_window_handle",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 37

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 18908,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "smol_str",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1\\src\\lib.rs",
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
    "cfg(feature, values(\"arbitrary\", \"default\", \"serde\", \"std\"))",
    "-C",
    "metadata=643fc940d43059b7",
    "-C",
    "extra-filename=-a58cc8446871329b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name smol_str --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"default\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=643fc940d43059b7 -C extra-filename=-a58cc8446871329b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "smol_str",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1\\src\\lib.rs",
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
    "cfg(feature, values(\"arbitrary\", \"default\", \"serde\", \"std\"))",
    "-C",
    "metadata=643fc940d43059b7",
    "-C",
    "extra-filename=-a58cc8446871329b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.129431+00:00",
  "end_time": "2026-07-13T16:48:39.310435+00:00",
  "start_unix_nanos": 1783961319129430500,
  "end_unix_nanos": 1783961319310435200,
  "crate_name": "smol_str",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 38

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 12620,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
    "feature=\"ahash\"",
    "--cfg",
    "feature=\"bytemuck\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"memmap2\"",
    "--cfg",
    "feature=\"percent-encoding\"",
    "--cfg",
    "feature=\"rwh_06\"",
    "--cfg",
    "feature=\"sctk\"",
    "--cfg",
    "feature=\"sctk-adwaita\"",
    "--cfg",
    "feature=\"wayland\"",
    "--cfg",
    "feature=\"wayland-backend\"",
    "--cfg",
    "feature=\"wayland-client\"",
    "--cfg",
    "feature=\"wayland-csd-adwaita\"",
    "--cfg",
    "feature=\"wayland-dlopen\"",
    "--cfg",
    "feature=\"wayland-protocols\"",
    "--cfg",
    "feature=\"wayland-protocols-plasma\"",
    "--cfg",
    "feature=\"x11\"",
    "--cfg",
    "feature=\"x11-dl\"",
    "--cfg",
    "feature=\"x11rb\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"ahash\", \"android-game-activity\", \"android-native-activity\", \"bytemuck\", \"default\", \"memmap2\", \"mint\", \"percent-encoding\", \"rwh_04\", \"rwh_05\", \"rwh_06\", \"sctk\", \"sctk-adwaita\", \"serde\", \"wayland\", \"wayland-backend\", \"wayland-client\", \"wayland-csd-adwaita\", \"wayland-csd-adwaita-crossfont\", \"wayland-csd-adwaita-notitle\", \"wayland-dlopen\", \"wayland-protocols\", \"wayland-protocols-plasma\", \"x11\", \"x11-dl\", \"x11rb\"))",
    "-C",
    "metadata=c8a5096ab5ff811a",
    "-C",
    "extra-filename=-717c5d300b98a4e3",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--extern",
    "cfg_aliases=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcfg_aliases-58fc099ce75d46bd.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"ahash\\\"\" --cfg \"feature=\\\"bytemuck\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"memmap2\\\"\" --cfg \"feature=\\\"percent-encoding\\\"\" --cfg \"feature=\\\"rwh_06\\\"\" --cfg \"feature=\\\"sctk\\\"\" --cfg \"feature=\\\"sctk-adwaita\\\"\" --cfg \"feature=\\\"wayland\\\"\" --cfg \"feature=\\\"wayland-backend\\\"\" --cfg \"feature=\\\"wayland-client\\\"\" --cfg \"feature=\\\"wayland-csd-adwaita\\\"\" --cfg \"feature=\\\"wayland-dlopen\\\"\" --cfg \"feature=\\\"wayland-protocols\\\"\" --cfg \"feature=\\\"wayland-protocols-plasma\\\"\" --cfg \"feature=\\\"x11\\\"\" --cfg \"feature=\\\"x11-dl\\\"\" --cfg \"feature=\\\"x11rb\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"ahash\\\", \\\"android-game-activity\\\", \\\"android-native-activity\\\", \\\"bytemuck\\\", \\\"default\\\", \\\"memmap2\\\", \\\"mint\\\", \\\"percent-encoding\\\", \\\"rwh_04\\\", \\\"rwh_05\\\", \\\"rwh_06\\\", \\\"sctk\\\", \\\"sctk-adwaita\\\", \\\"serde\\\", \\\"wayland\\\", \\\"wayland-backend\\\", \\\"wayland-client\\\", \\\"wayland-csd-adwaita\\\", \\\"wayland-csd-adwaita-crossfont\\\", \\\"wayland-csd-adwaita-notitle\\\", \\\"wayland-dlopen\\\", \\\"wayland-protocols\\\", \\\"wayland-protocols-plasma\\\", \\\"x11\\\", \\\"x11-dl\\\", \\\"x11rb\\\"))\" -C metadata=c8a5096ab5ff811a -C extra-filename=-717c5d300b98a4e3 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --extern cfg_aliases=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcfg_aliases-58fc099ce75d46bd.rlib",
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
    "feature=\"ahash\"",
    "--cfg",
    "feature=\"bytemuck\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"memmap2\"",
    "--cfg",
    "feature=\"percent-encoding\"",
    "--cfg",
    "feature=\"rwh_06\"",
    "--cfg",
    "feature=\"sctk\"",
    "--cfg",
    "feature=\"sctk-adwaita\"",
    "--cfg",
    "feature=\"wayland\"",
    "--cfg",
    "feature=\"wayland-backend\"",
    "--cfg",
    "feature=\"wayland-client\"",
    "--cfg",
    "feature=\"wayland-csd-adwaita\"",
    "--cfg",
    "feature=\"wayland-dlopen\"",
    "--cfg",
    "feature=\"wayland-protocols\"",
    "--cfg",
    "feature=\"wayland-protocols-plasma\"",
    "--cfg",
    "feature=\"x11\"",
    "--cfg",
    "feature=\"x11-dl\"",
    "--cfg",
    "feature=\"x11rb\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"ahash\", \"android-game-activity\", \"android-native-activity\", \"bytemuck\", \"default\", \"memmap2\", \"mint\", \"percent-encoding\", \"rwh_04\", \"rwh_05\", \"rwh_06\", \"sctk\", \"sctk-adwaita\", \"serde\", \"wayland\", \"wayland-backend\", \"wayland-client\", \"wayland-csd-adwaita\", \"wayland-csd-adwaita-crossfont\", \"wayland-csd-adwaita-notitle\", \"wayland-dlopen\", \"wayland-protocols\", \"wayland-protocols-plasma\", \"x11\", \"x11-dl\", \"x11rb\"))",
    "-C",
    "metadata=c8a5096ab5ff811a",
    "-C",
    "extra-filename=-717c5d300b98a4e3",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--extern",
    "cfg_aliases=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcfg_aliases-58fc099ce75d46bd.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.218183+00:00",
  "end_time": "2026-07-13T16:48:39.802593+00:00",
  "start_unix_nanos": 1783961319218183300,
  "end_unix_nanos": 1783961319802593200,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3"
}
```

#### Record 39

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 15924,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_x86_64_msvc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\src\\lib.rs",
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
    "metadata=ec5e69bf4147ead9",
    "-C",
    "extra-filename=-90661bad6bd70640",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_x86_64_msvc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=ec5e69bf4147ead9 -C extra-filename=-90661bad6bd70640 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_x86_64_msvc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\src\\lib.rs",
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
    "metadata=ec5e69bf4147ead9",
    "-C",
    "extra-filename=-90661bad6bd70640",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.478541+00:00",
  "end_time": "2026-07-13T16:48:39.528642+00:00",
  "start_unix_nanos": 1783961319478540600,
  "end_unix_nanos": 1783961319528642500,
  "crate_name": "windows_x86_64_msvc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 40

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 14980,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_targets",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5\\src\\lib.rs",
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
    "metadata=3179a779a073e2bf",
    "-C",
    "extra-filename=-cf26163e4cd2c220",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--extern",
    "windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_x86_64_msvc-90661bad6bd70640.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_targets --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=3179a779a073e2bf -C extra-filename=-cf26163e4cd2c220 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --extern windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_x86_64_msvc-90661bad6bd70640.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_targets",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5\\src\\lib.rs",
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
    "metadata=3179a779a073e2bf",
    "-C",
    "extra-filename=-cf26163e4cd2c220",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--extern",
    "windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_x86_64_msvc-90661bad6bd70640.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.510060+00:00",
  "end_time": "2026-07-13T16:48:39.559257+00:00",
  "start_unix_nanos": 1783961319510060300,
  "end_unix_nanos": 1783961319559256900,
  "crate_name": "windows_targets",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 41

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 19008,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_sys",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0\\src\\lib.rs",
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
    "feature=\"Win32\"",
    "--cfg",
    "feature=\"Win32_Devices\"",
    "--cfg",
    "feature=\"Win32_Devices_HumanInterfaceDevice\"",
    "--cfg",
    "feature=\"Win32_Foundation\"",
    "--cfg",
    "feature=\"Win32_Globalization\"",
    "--cfg",
    "feature=\"Win32_Graphics\"",
    "--cfg",
    "feature=\"Win32_Graphics_Dwm\"",
    "--cfg",
    "feature=\"Win32_Graphics_Gdi\"",
    "--cfg",
    "feature=\"Win32_Media\"",
    "--cfg",
    "feature=\"Win32_System\"",
    "--cfg",
    "feature=\"Win32_System_Com\"",
    "--cfg",
    "feature=\"Win32_System_Com_StructuredStorage\"",
    "--cfg",
    "feature=\"Win32_System_LibraryLoader\"",
    "--cfg",
    "feature=\"Win32_System_Ole\"",
    "--cfg",
    "feature=\"Win32_System_SystemInformation\"",
    "--cfg",
    "feature=\"Win32_System_SystemServices\"",
    "--cfg",
    "feature=\"Win32_System_Threading\"",
    "--cfg",
    "feature=\"Win32_System_WindowsProgramming\"",
    "--cfg",
    "feature=\"Win32_UI\"",
    "--cfg",
    "feature=\"Win32_UI_Accessibility\"",
    "--cfg",
    "feature=\"Win32_UI_Controls\"",
    "--cfg",
    "feature=\"Win32_UI_HiDpi\"",
    "--cfg",
    "feature=\"Win32_UI_Input\"",
    "--cfg",
    "feature=\"Win32_UI_Input_Ime\"",
    "--cfg",
    "feature=\"Win32_UI_Input_KeyboardAndMouse\"",
    "--cfg",
    "feature=\"Win32_UI_Input_Pointer\"",
    "--cfg",
    "feature=\"Win32_UI_Input_Touch\"",
    "--cfg",
    "feature=\"Win32_UI_Shell\"",
    "--cfg",
    "feature=\"Win32_UI_TextServices\"",
    "--cfg",
    "feature=\"Win32_UI_WindowsAndMessaging\"",
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"Wdk\", \"Wdk_System\", \"Wdk_System_OfflineRegistry\", \"Win32\", \"Win32_Data\", \"Win32_Data_HtmlHelp\", \"Win32_Data_RightsManagement\", \"Win32_Data_Xml\", \"Win32_Data_Xml_MsXml\", \"Win32_Data_Xml_XmlLite\", \"Win32_Devices\", \"Win32_Devices_AllJoyn\", \"Win32_Devices_BiometricFramework\", \"Win32_Devices_Bluetooth\", \"Win32_Devices_Communication\", \"Win32_Devices_DeviceAccess\", \"Win32_Devices_DeviceAndDriverInstallation\", \"Win32_Devices_DeviceQuery\", \"Win32_Devices_Display\", \"Win32_Devices_Enumeration\", \"Win32_Devices_Enumeration_Pnp\", \"Win32_Devices_Fax\", \"Win32_Devices_FunctionDiscovery\", \"Win32_Devices_Geolocation\", \"Win32_Devices_HumanInterfaceDevice\", \"Win32_Devices_ImageAcquisition\", \"Win32_Devices_PortableDevices\", \"Win32_Devices_Properties\", \"Win32_Devices_Pwm\", \"Win32_Devices_Sensors\", \"Win32_Devices_SerialCommunication\", \"Win32_Devices_Tapi\", \"Win32_Devices_Usb\", \"Win32_Devices_WebServicesOnDevices\", \"Win32_Foundation\", \"Win32_Gaming\", \"Win32_Globalization\", \"Win32_Graphics\", \"Win32_Graphics_Dwm\", \"Win32_Graphics_Gdi\", \"Win32_Graphics_Hlsl\", \"Win32_Graphics_OpenGL\", \"Win32_Graphics_Printing\", \"Win32_Graphics_Printing_PrintTicket\", \"Win32_Management\", \"Win32_Management_MobileDeviceManagementRegistration\", \"Win32_Media\", \"Win32_Media_Audio\", \"Win32_Media_Audio_Apo\", \"Win32_Media_Audio_DirectMusic\", \"Win32_Media_Audio_Endpoints\", \"Win32_Media_Audio_XAudio2\", \"Win32_Media_DeviceManager\", \"Win32_Media_DxMediaObjects\", \"Win32_Media_KernelStreaming\", \"Win32_Media_LibrarySharingServices\", \"Win32_Media_MediaPlayer\", \"Win32_Media_Multimedia\", \"Win32_Media_Speech\", \"Win32_Media_Streaming\", \"Win32_Media_WindowsMediaFormat\", \"Win32_NetworkManagement\", \"Win32_NetworkManagement_Dhcp\", \"Win32_NetworkManagement_Dns\", \"Win32_NetworkManagement_InternetConnectionWizard\", \"Win32_NetworkManagement_IpHelper\", \"Win32_NetworkManagement_MobileBroadband\", \"Win32_NetworkManagement_Multicast\", \"Win32_NetworkManagement_Ndis\", \"Win32_NetworkManagement_NetBios\", \"Win32_NetworkManagement_NetManagement\", \"Win32_NetworkManagement_NetShell\", \"Win32_NetworkManagement_NetworkDiagnosticsFramework\", \"Win32_NetworkManagement_NetworkPolicyServer\", \"Win32_NetworkManagement_P2P\", \"Win32_NetworkManagement_QoS\", \"Win32_NetworkManagement_Rras\", \"Win32_NetworkManagement_Snmp\", \"Win32_NetworkManagement_WNet\", \"Win32_NetworkManagement_WebDav\", \"Win32_NetworkManagement_WiFi\", \"Win32_NetworkManagement_WindowsConnectNow\", \"Win32_NetworkManagement_WindowsConnectionManager\", \"Win32_NetworkManagement_WindowsFilteringPlatform\", \"Win32_NetworkManagement_WindowsFirewall\", \"Win32_NetworkManagement_WindowsNetworkVirtualization\", \"Win32_Networking\", \"Win32_Networking_ActiveDirectory\", \"Win32_Networking_BackgroundIntelligentTransferService\", \"Win32_Networking_Clustering\", \"Win32_Networking_HttpServer\", \"Win32_Networking_Ldap\", \"Win32_Networking_NetworkListManager\", \"Win32_Networking_RemoteDifferentialCompression\", \"Win32_Networking_WebSocket\", \"Win32_Networking_WinHttp\", \"Win32_Networking_WinInet\", \"Win32_Networking_WinSock\", \"Win32_Networking_WindowsWebServices\", \"Win32_Security\", \"Win32_Security_AppLocker\", \"Win32_Security_Authentication\", \"Win32_Security_Authentication_Identity\", \"Win32_Security_Authentication_Identity_Provider\", \"Win32_Security_Authorization\", \"Win32_Security_Authorization_UI\", \"Win32_Security_ConfigurationSnapin\", \"Win32_Security_Credentials\", \"Win32_Security_Cryptography\", \"Win32_Security_Cryptography_Catalog\", \"Win32_Security_Cryptography_Certificates\", \"Win32_Security_Cryptography_Sip\", \"Win32_Security_Cryptography_UI\", \"Win32_Security_DiagnosticDataQuery\", \"Win32_Security_DirectoryServices\", \"Win32_Security_EnterpriseData\", \"Win32_Security_ExtensibleAuthenticationProtocol\", \"Win32_Security_Isolation\", \"Win32_Security_LicenseProtection\", \"Win32_Security_NetworkAccessProtection\", \"Win32_Security_Tpm\", \"Win32_Security_WinTrust\", \"Win32_Security_WinWlx\", \"Win32_Storage\", \"Win32_Storage_Cabinets\", \"Win32_Storage_CloudFilters\", \"Win32_Storage_Compression\", \"Win32_Storage_DataDeduplication\", \"Win32_Storage_DistributedFileSystem\", \"Win32_Storage_EnhancedStorage\", \"Win32_Storage_FileHistory\", \"Win32_Storage_FileServerResourceManager\", \"Win32_Storage_FileSystem\", \"Win32_Storage_Imapi\", \"Win32_Storage_IndexServer\", \"Win32_Storage_InstallableFileSystems\", \"Win32_Storage_IscsiDisc\", \"Win32_Storage_Jet\", \"Win32_Storage_OfflineFiles\", \"Win32_Storage_OperationRecorder\", \"Win32_Storage_Packaging\", \"Win32_Storage_Packaging_Appx\", \"Win32_Storage_Packaging_Opc\", \"Win32_Storage_ProjectedFileSystem\", \"Win32_Storage_StructuredStorage\", \"Win32_Storage_Vhd\", \"Win32_Storage_VirtualDiskService\", \"Win32_Storage_Vss\", \"Win32_Storage_Xps\", \"Win32_Storage_Xps_Printing\", \"Win32_System\", \"Win32_System_AddressBook\", \"Win32_System_Antimalware\", \"Win32_System_ApplicationInstallationAndServicing\", \"Win32_System_ApplicationVerifier\", \"Win32_System_AssessmentTool\", \"Win32_System_ClrHosting\", \"Win32_System_Com\", \"Win32_System_Com_CallObj\", \"Win32_System_Com_ChannelCredentials\", \"Win32_System_Com_Events\", \"Win32_System_Com_Marshal\", \"Win32_System_Com_StructuredStorage\", \"Win32_System_Com_UI\", \"Win32_System_Com_Urlmon\", \"Win32_System_ComponentServices\", \"Win32_System_Console\", \"Win32_System_Contacts\", \"Win32_System_CorrelationVector\", \"Win32_System_DataExchange\", \"Win32_System_DeploymentServices\", \"Win32_System_DesktopSharing\", \"Win32_System_DeveloperLicensing\", \"Win32_System_Diagnostics\", \"Win32_System_Diagnostics_Ceip\", \"Win32_System_Diagnostics_ClrProfiling\", \"Win32_System_Diagnostics_Debug\", \"Win32_System_Diagnostics_Debug_ActiveScript\", \"Win32_System_Diagnostics_Debug_Extensions\", \"Win32_System_Diagnostics_Etw\", \"Win32_System_Diagnostics_ProcessSnapshotting\", \"Win32_System_Diagnostics_ToolHelp\", \"Win32_System_DistributedTransactionCoordinator\", \"Win32_System_Environment\", \"Win32_System_ErrorReporting\", \"Win32_System_EventCollector\", \"Win32_System_EventLog\", \"Win32_System_EventNotificationService\", \"Win32_System_GroupPolicy\", \"Win32_System_HostCompute\", \"Win32_System_HostComputeNetwork\", \"Win32_System_HostComputeSystem\", \"Win32_System_Hypervisor\", \"Win32_System_IO\", \"Win32_System_Iis\", \"Win32_System_Ioctl\", \"Win32_System_JobObjects\", \"Win32_System_Js\", \"Win32_System_Kernel\", \"Win32_System_LibraryLoader\", \"Win32_System_Mailslots\", \"Win32_System_Mapi\", \"Win32_System_Memory\", \"Win32_System_Memory_NonVolatile\", \"Win32_System_MessageQueuing\", \"Win32_System_MixedReality\", \"Win32_System_Mmc\", \"Win32_System_Ole\", \"Win32_System_ParentalControls\", \"Win32_System_PasswordManagement\", \"Win32_System_Performance\", \"Win32_System_Performance_HardwareCounterProfiling\", \"Win32_System_Pipes\", \"Win32_System_Power\", \"Win32_System_ProcessStatus\", \"Win32_System_RealTimeCommunications\", \"Win32_System_Recovery\", \"Win32_System_Registry\", \"Win32_System_RemoteAssistance\", \"Win32_System_RemoteDesktop\", \"Win32_System_RemoteManagement\", \"Win32_System_RestartManager\", \"Win32_System_Restore\", \"Win32_System_Rpc\", \"Win32_System_Search\", \"Win32_System_Search_Common\", \"Win32_System_SecurityCenter\", \"Win32_System_ServerBackup\", \"Win32_System_Services\", \"Win32_System_SettingsManagementInfrastructure\", \"Win32_System_SetupAndMigration\", \"Win32_System_Shutdown\", \"Win32_System_StationsAndDesktops\", \"Win32_System_SubsystemForLinux\", \"Win32_System_SystemInformation\", \"Win32_System_SystemServices\", \"Win32_System_TaskScheduler\", \"Win32_System_Threading\", \"Win32_System_Time\", \"Win32_System_TpmBaseServices\", \"Win32_System_UpdateAgent\", \"Win32_System_UpdateAssessment\", \"Win32_System_UserAccessLogging\", \"Win32_System_VirtualDosMachines\", \"Win32_System_WindowsProgramming\", \"Win32_System_WindowsSync\", \"Win32_System_Wmi\", \"Win32_UI\", \"Win32_UI_Accessibility\", \"Win32_UI_Animation\", \"Win32_UI_ColorSystem\", \"Win32_UI_Controls\", \"Win32_UI_Controls_Dialogs\", \"Win32_UI_Controls_RichEdit\", \"Win32_UI_HiDpi\", \"Win32_UI_Input\", \"Win32_UI_Input_Ime\", \"Win32_UI_Input_Ink\", \"Win32_UI_Input_KeyboardAndMouse\", \"Win32_UI_Input_Pointer\", \"Win32_UI_Input_Radial\", \"Win32_UI_Input_Touch\", \"Win32_UI_Input_XboxController\", \"Win32_UI_InteractionContext\", \"Win32_UI_LegacyWindowsEnvironmentFeatures\", \"Win32_UI_Magnification\", \"Win32_UI_Notifications\", \"Win32_UI_Ribbon\", \"Win32_UI_Shell\", \"Win32_UI_Shell_Common\", \"Win32_UI_Shell_PropertiesSystem\", \"Win32_UI_TabletPC\", \"Win32_UI_TextServices\", \"Win32_UI_WindowsAndMessaging\", \"Win32_UI_Wpf\", \"Win32_Web\", \"Win32_Web_InternetExplorer\", \"default\"))",
    "-C",
    "metadata=b5b51020364d6d0c",
    "-C",
    "extra-filename=-80bdfb6f4e0c903e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--extern",
    "windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_targets-cf26163e4cd2c220.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_sys --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"Win32\\\"\" --cfg \"feature=\\\"Win32_Devices\\\"\" --cfg \"feature=\\\"Win32_Devices_HumanInterfaceDevice\\\"\" --cfg \"feature=\\\"Win32_Foundation\\\"\" --cfg \"feature=\\\"Win32_Globalization\\\"\" --cfg \"feature=\\\"Win32_Graphics\\\"\" --cfg \"feature=\\\"Win32_Graphics_Dwm\\\"\" --cfg \"feature=\\\"Win32_Graphics_Gdi\\\"\" --cfg \"feature=\\\"Win32_Media\\\"\" --cfg \"feature=\\\"Win32_System\\\"\" --cfg \"feature=\\\"Win32_System_Com\\\"\" --cfg \"feature=\\\"Win32_System_Com_StructuredStorage\\\"\" --cfg \"feature=\\\"Win32_System_LibraryLoader\\\"\" --cfg \"feature=\\\"Win32_System_Ole\\\"\" --cfg \"feature=\\\"Win32_System_SystemInformation\\\"\" --cfg \"feature=\\\"Win32_System_SystemServices\\\"\" --cfg \"feature=\\\"Win32_System_Threading\\\"\" --cfg \"feature=\\\"Win32_System_WindowsProgramming\\\"\" --cfg \"feature=\\\"Win32_UI\\\"\" --cfg \"feature=\\\"Win32_UI_Accessibility\\\"\" --cfg \"feature=\\\"Win32_UI_Controls\\\"\" --cfg \"feature=\\\"Win32_UI_HiDpi\\\"\" --cfg \"feature=\\\"Win32_UI_Input\\\"\" --cfg \"feature=\\\"Win32_UI_Input_Ime\\\"\" --cfg \"feature=\\\"Win32_UI_Input_KeyboardAndMouse\\\"\" --cfg \"feature=\\\"Win32_UI_Input_Pointer\\\"\" --cfg \"feature=\\\"Win32_UI_Input_Touch\\\"\" --cfg \"feature=\\\"Win32_UI_Shell\\\"\" --cfg \"feature=\\\"Win32_UI_TextServices\\\"\" --cfg \"feature=\\\"Win32_UI_WindowsAndMessaging\\\"\" --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"Wdk\\\", \\\"Wdk_System\\\", \\\"Wdk_System_OfflineRegistry\\\", \\\"Win32\\\", \\\"Win32_Data\\\", \\\"Win32_Data_HtmlHelp\\\", \\\"Win32_Data_RightsManagement\\\", \\\"Win32_Data_Xml\\\", \\\"Win32_Data_Xml_MsXml\\\", \\\"Win32_Data_Xml_XmlLite\\\", \\\"Win32_Devices\\\", \\\"Win32_Devices_AllJoyn\\\", \\\"Win32_Devices_BiometricFramework\\\", \\\"Win32_Devices_Bluetooth\\\", \\\"Win32_Devices_Communication\\\", \\\"Win32_Devices_DeviceAccess\\\", \\\"Win32_Devices_DeviceAndDriverInstallation\\\", \\\"Win32_Devices_DeviceQuery\\\", \\\"Win32_Devices_Display\\\", \\\"Win32_Devices_Enumeration\\\", \\\"Win32_Devices_Enumeration_Pnp\\\", \\\"Win32_Devices_Fax\\\", \\\"Win32_Devices_FunctionDiscovery\\\", \\\"Win32_Devices_Geolocation\\\", \\\"Win32_Devices_HumanInterfaceDevice\\\", \\\"Win32_Devices_ImageAcquisition\\\", \\\"Win32_Devices_PortableDevices\\\", \\\"Win32_Devices_Properties\\\", \\\"Win32_Devices_Pwm\\\", \\\"Win32_Devices_Sensors\\\", \\\"Win32_Devices_SerialCommunication\\\", \\\"Win32_Devices_Tapi\\\", \\\"Win32_Devices_Usb\\\", \\\"Win32_Devices_WebServicesOnDevices\\\", \\\"Win32_Foundation\\\", \\\"Win32_Gaming\\\", \\\"Win32_Globalization\\\", \\\"Win32_Graphics\\\", \\\"Win32_Graphics_Dwm\\\", \\\"Win32_Graphics_Gdi\\\", \\\"Win32_Graphics_Hlsl\\\", \\\"Win32_Graphics_OpenGL\\\", \\\"Win32_Graphics_Printing\\\", \\\"Win32_Graphics_Printing_PrintTicket\\\", \\\"Win32_Management\\\", \\\"Win32_Management_MobileDeviceManagementRegistration\\\", \\\"Win32_Media\\\", \\\"Win32_Media_Audio\\\", \\\"Win32_Media_Audio_Apo\\\", \\\"Win32_Media_Audio_DirectMusic\\\", \\\"Win32_Media_Audio_Endpoints\\\", \\\"Win32_Media_Audio_XAudio2\\\", \\\"Win32_Media_DeviceManager\\\", \\\"Win32_Media_DxMediaObjects\\\", \\\"Win32_Media_KernelStreaming\\\", \\\"Win32_Media_LibrarySharingServices\\\", \\\"Win32_Media_MediaPlayer\\\", \\\"Win32_Media_Multimedia\\\", \\\"Win32_Media_Speech\\\", \\\"Win32_Media_Streaming\\\", \\\"Win32_Media_WindowsMediaFormat\\\", \\\"Win32_NetworkManagement\\\", \\\"Win32_NetworkManagement_Dhcp\\\", \\\"Win32_NetworkManagement_Dns\\\", \\\"Win32_NetworkManagement_InternetConnectionWizard\\\", \\\"Win32_NetworkManagement_IpHelper\\\", \\\"Win32_NetworkManagement_MobileBroadband\\\", \\\"Win32_NetworkManagement_Multicast\\\", \\\"Win32_NetworkManagement_Ndis\\\", \\\"Win32_NetworkManagement_NetBios\\\", \\\"Win32_NetworkManagement_NetManagement\\\", \\\"Win32_NetworkManagement_NetShell\\\", \\\"Win32_NetworkManagement_NetworkDiagnosticsFramework\\\", \\\"Win32_NetworkManagement_NetworkPolicyServer\\\", \\\"Win32_NetworkManagement_P2P\\\", \\\"Win32_NetworkManagement_QoS\\\", \\\"Win32_NetworkManagement_Rras\\\", \\\"Win32_NetworkManagement_Snmp\\\", \\\"Win32_NetworkManagement_WNet\\\", \\\"Win32_NetworkManagement_WebDav\\\", \\\"Win32_NetworkManagement_WiFi\\\", \\\"Win32_NetworkManagement_WindowsConnectNow\\\", \\\"Win32_NetworkManagement_WindowsConnectionManager\\\", \\\"Win32_NetworkManagement_WindowsFilteringPlatform\\\", \\\"Win32_NetworkManagement_WindowsFirewall\\\", \\\"Win32_NetworkManagement_WindowsNetworkVirtualization\\\", \\\"Win32_Networking\\\", \\\"Win32_Networking_ActiveDirectory\\\", \\\"Win32_Networking_BackgroundIntelligentTransferService\\\", \\\"Win32_Networking_Clustering\\\", \\\"Win32_Networking_HttpServer\\\", \\\"Win32_Networking_Ldap\\\", \\\"Win32_Networking_NetworkListManager\\\", \\\"Win32_Networking_RemoteDifferentialCompression\\\", \\\"Win32_Networking_WebSocket\\\", \\\"Win32_Networking_WinHttp\\\", \\\"Win32_Networking_WinInet\\\", \\\"Win32_Networking_WinSock\\\", \\\"Win32_Networking_WindowsWebServices\\\", \\\"Win32_Security\\\", \\\"Win32_Security_AppLocker\\\", \\\"Win32_Security_Authentication\\\", \\\"Win32_Security_Authentication_Identity\\\", \\\"Win32_Security_Authentication_Identity_Provider\\\", \\\"Win32_Security_Authorization\\\", \\\"Win32_Security_Authorization_UI\\\", \\\"Win32_Security_ConfigurationSnapin\\\", \\\"Win32_Security_Credentials\\\", \\\"Win32_Security_Cryptography\\\", \\\"Win32_Security_Cryptography_Catalog\\\", \\\"Win32_Security_Cryptography_Certificates\\\", \\\"Win32_Security_Cryptography_Sip\\\", \\\"Win32_Security_Cryptography_UI\\\", \\\"Win32_Security_DiagnosticDataQuery\\\", \\\"Win32_Security_DirectoryServices\\\", \\\"Win32_Security_EnterpriseData\\\", \\\"Win32_Security_ExtensibleAuthenticationProtocol\\\", \\\"Win32_Security_Isolation\\\", \\\"Win32_Security_LicenseProtection\\\", \\\"Win32_Security_NetworkAccessProtection\\\", \\\"Win32_Security_Tpm\\\", \\\"Win32_Security_WinTrust\\\", \\\"Win32_Security_WinWlx\\\", \\\"Win32_Storage\\\", \\\"Win32_Storage_Cabinets\\\", \\\"Win32_Storage_CloudFilters\\\", \\\"Win32_Storage_Compression\\\", \\\"Win32_Storage_DataDeduplication\\\", \\\"Win32_Storage_DistributedFileSystem\\\", \\\"Win32_Storage_EnhancedStorage\\\", \\\"Win32_Storage_FileHistory\\\", \\\"Win32_Storage_FileServerResourceManager\\\", \\\"Win32_Storage_FileSystem\\\", \\\"Win32_Storage_Imapi\\\", \\\"Win32_Storage_IndexServer\\\", \\\"Win32_Storage_InstallableFileSystems\\\", \\\"Win32_Storage_IscsiDisc\\\", \\\"Win32_Storage_Jet\\\", \\\"Win32_Storage_OfflineFiles\\\", \\\"Win32_Storage_OperationRecorder\\\", \\\"Win32_Storage_Packaging\\\", \\\"Win32_Storage_Packaging_Appx\\\", \\\"Win32_Storage_Packaging_Opc\\\", \\\"Win32_Storage_ProjectedFileSystem\\\", \\\"Win32_Storage_StructuredStorage\\\", \\\"Win32_Storage_Vhd\\\", \\\"Win32_Storage_VirtualDiskService\\\", \\\"Win32_Storage_Vss\\\", \\\"Win32_Storage_Xps\\\", \\\"Win32_Storage_Xps_Printing\\\", \\\"Win32_System\\\", \\\"Win32_System_AddressBook\\\", \\\"Win32_System_Antimalware\\\", \\\"Win32_System_ApplicationInstallationAndServicing\\\", \\\"Win32_System_ApplicationVerifier\\\", \\\"Win32_System_AssessmentTool\\\", \\\"Win32_System_ClrHosting\\\", \\\"Win32_System_Com\\\", \\\"Win32_System_Com_CallObj\\\", \\\"Win32_System_Com_ChannelCredentials\\\", \\\"Win32_System_Com_Events\\\", \\\"Win32_System_Com_Marshal\\\", \\\"Win32_System_Com_StructuredStorage\\\", \\\"Win32_System_Com_UI\\\", \\\"Win32_System_Com_Urlmon\\\", \\\"Win32_System_ComponentServices\\\", \\\"Win32_System_Console\\\", \\\"Win32_System_Contacts\\\", \\\"Win32_System_CorrelationVector\\\", \\\"Win32_System_DataExchange\\\", \\\"Win32_System_DeploymentServices\\\", \\\"Win32_System_DesktopSharing\\\", \\\"Win32_System_DeveloperLicensing\\\", \\\"Win32_System_Diagnostics\\\", \\\"Win32_System_Diagnostics_Ceip\\\", \\\"Win32_System_Diagnostics_ClrProfiling\\\", \\\"Win32_System_Diagnostics_Debug\\\", \\\"Win32_System_Diagnostics_Debug_ActiveScript\\\", \\\"Win32_System_Diagnostics_Debug_Extensions\\\", \\\"Win32_System_Diagnostics_Etw\\\", \\\"Win32_System_Diagnostics_ProcessSnapshotting\\\", \\\"Win32_System_Diagnostics_ToolHelp\\\", \\\"Win32_System_DistributedTransactionCoordinator\\\", \\\"Win32_System_Environment\\\", \\\"Win32_System_ErrorReporting\\\", \\\"Win32_System_EventCollector\\\", \\\"Win32_System_EventLog\\\", \\\"Win32_System_EventNotificationService\\\", \\\"Win32_System_GroupPolicy\\\", \\\"Win32_System_HostCompute\\\", \\\"Win32_System_HostComputeNetwork\\\", \\\"Win32_System_HostComputeSystem\\\", \\\"Win32_System_Hypervisor\\\", \\\"Win32_System_IO\\\", \\\"Win32_System_Iis\\\", \\\"Win32_System_Ioctl\\\", \\\"Win32_System_JobObjects\\\", \\\"Win32_System_Js\\\", \\\"Win32_System_Kernel\\\", \\\"Win32_System_LibraryLoader\\\", \\\"Win32_System_Mailslots\\\", \\\"Win32_System_Mapi\\\", \\\"Win32_System_Memory\\\", \\\"Win32_System_Memory_NonVolatile\\\", \\\"Win32_System_MessageQueuing\\\", \\\"Win32_System_MixedReality\\\", \\\"Win32_System_Mmc\\\", \\\"Win32_System_Ole\\\", \\\"Win32_System_ParentalControls\\\", \\\"Win32_System_PasswordManagement\\\", \\\"Win32_System_Performance\\\", \\\"Win32_System_Performance_HardwareCounterProfiling\\\", \\\"Win32_System_Pipes\\\", \\\"Win32_System_Power\\\", \\\"Win32_System_ProcessStatus\\\", \\\"Win32_System_RealTimeCommunications\\\", \\\"Win32_System_Recovery\\\", \\\"Win32_System_Registry\\\", \\\"Win32_System_RemoteAssistance\\\", \\\"Win32_System_RemoteDesktop\\\", \\\"Win32_System_RemoteManagement\\\", \\\"Win32_System_RestartManager\\\", \\\"Win32_System_Restore\\\", \\\"Win32_System_Rpc\\\", \\\"Win32_System_Search\\\", \\\"Win32_System_Search_Common\\\", \\\"Win32_System_SecurityCenter\\\", \\\"Win32_System_ServerBackup\\\", \\\"Win32_System_Services\\\", \\\"Win32_System_SettingsManagementInfrastructure\\\", \\\"Win32_System_SetupAndMigration\\\", \\\"Win32_System_Shutdown\\\", \\\"Win32_System_StationsAndDesktops\\\", \\\"Win32_System_SubsystemForLinux\\\", \\\"Win32_System_SystemInformation\\\", \\\"Win32_System_SystemServices\\\", \\\"Win32_System_TaskScheduler\\\", \\\"Win32_System_Threading\\\", \\\"Win32_System_Time\\\", \\\"Win32_System_TpmBaseServices\\\", \\\"Win32_System_UpdateAgent\\\", \\\"Win32_System_UpdateAssessment\\\", \\\"Win32_System_UserAccessLogging\\\", \\\"Win32_System_VirtualDosMachines\\\", \\\"Win32_System_WindowsProgramming\\\", \\\"Win32_System_WindowsSync\\\", \\\"Win32_System_Wmi\\\", \\\"Win32_UI\\\", \\\"Win32_UI_Accessibility\\\", \\\"Win32_UI_Animation\\\", \\\"Win32_UI_ColorSystem\\\", \\\"Win32_UI_Controls\\\", \\\"Win32_UI_Controls_Dialogs\\\", \\\"Win32_UI_Controls_RichEdit\\\", \\\"Win32_UI_HiDpi\\\", \\\"Win32_UI_Input\\\", \\\"Win32_UI_Input_Ime\\\", \\\"Win32_UI_Input_Ink\\\", \\\"Win32_UI_Input_KeyboardAndMouse\\\", \\\"Win32_UI_Input_Pointer\\\", \\\"Win32_UI_Input_Radial\\\", \\\"Win32_UI_Input_Touch\\\", \\\"Win32_UI_Input_XboxController\\\", \\\"Win32_UI_InteractionContext\\\", \\\"Win32_UI_LegacyWindowsEnvironmentFeatures\\\", \\\"Win32_UI_Magnification\\\", \\\"Win32_UI_Notifications\\\", \\\"Win32_UI_Ribbon\\\", \\\"Win32_UI_Shell\\\", \\\"Win32_UI_Shell_Common\\\", \\\"Win32_UI_Shell_PropertiesSystem\\\", \\\"Win32_UI_TabletPC\\\", \\\"Win32_UI_TextServices\\\", \\\"Win32_UI_WindowsAndMessaging\\\", \\\"Win32_UI_Wpf\\\", \\\"Win32_Web\\\", \\\"Win32_Web_InternetExplorer\\\", \\\"default\\\"))\" -C metadata=b5b51020364d6d0c -C extra-filename=-80bdfb6f4e0c903e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --extern windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_targets-cf26163e4cd2c220.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_sys",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0\\src\\lib.rs",
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
    "feature=\"Win32\"",
    "--cfg",
    "feature=\"Win32_Devices\"",
    "--cfg",
    "feature=\"Win32_Devices_HumanInterfaceDevice\"",
    "--cfg",
    "feature=\"Win32_Foundation\"",
    "--cfg",
    "feature=\"Win32_Globalization\"",
    "--cfg",
    "feature=\"Win32_Graphics\"",
    "--cfg",
    "feature=\"Win32_Graphics_Dwm\"",
    "--cfg",
    "feature=\"Win32_Graphics_Gdi\"",
    "--cfg",
    "feature=\"Win32_Media\"",
    "--cfg",
    "feature=\"Win32_System\"",
    "--cfg",
    "feature=\"Win32_System_Com\"",
    "--cfg",
    "feature=\"Win32_System_Com_StructuredStorage\"",
    "--cfg",
    "feature=\"Win32_System_LibraryLoader\"",
    "--cfg",
    "feature=\"Win32_System_Ole\"",
    "--cfg",
    "feature=\"Win32_System_SystemInformation\"",
    "--cfg",
    "feature=\"Win32_System_SystemServices\"",
    "--cfg",
    "feature=\"Win32_System_Threading\"",
    "--cfg",
    "feature=\"Win32_System_WindowsProgramming\"",
    "--cfg",
    "feature=\"Win32_UI\"",
    "--cfg",
    "feature=\"Win32_UI_Accessibility\"",
    "--cfg",
    "feature=\"Win32_UI_Controls\"",
    "--cfg",
    "feature=\"Win32_UI_HiDpi\"",
    "--cfg",
    "feature=\"Win32_UI_Input\"",
    "--cfg",
    "feature=\"Win32_UI_Input_Ime\"",
    "--cfg",
    "feature=\"Win32_UI_Input_KeyboardAndMouse\"",
    "--cfg",
    "feature=\"Win32_UI_Input_Pointer\"",
    "--cfg",
    "feature=\"Win32_UI_Input_Touch\"",
    "--cfg",
    "feature=\"Win32_UI_Shell\"",
    "--cfg",
    "feature=\"Win32_UI_TextServices\"",
    "--cfg",
    "feature=\"Win32_UI_WindowsAndMessaging\"",
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"Wdk\", \"Wdk_System\", \"Wdk_System_OfflineRegistry\", \"Win32\", \"Win32_Data\", \"Win32_Data_HtmlHelp\", \"Win32_Data_RightsManagement\", \"Win32_Data_Xml\", \"Win32_Data_Xml_MsXml\", \"Win32_Data_Xml_XmlLite\", \"Win32_Devices\", \"Win32_Devices_AllJoyn\", \"Win32_Devices_BiometricFramework\", \"Win32_Devices_Bluetooth\", \"Win32_Devices_Communication\", \"Win32_Devices_DeviceAccess\", \"Win32_Devices_DeviceAndDriverInstallation\", \"Win32_Devices_DeviceQuery\", \"Win32_Devices_Display\", \"Win32_Devices_Enumeration\", \"Win32_Devices_Enumeration_Pnp\", \"Win32_Devices_Fax\", \"Win32_Devices_FunctionDiscovery\", \"Win32_Devices_Geolocation\", \"Win32_Devices_HumanInterfaceDevice\", \"Win32_Devices_ImageAcquisition\", \"Win32_Devices_PortableDevices\", \"Win32_Devices_Properties\", \"Win32_Devices_Pwm\", \"Win32_Devices_Sensors\", \"Win32_Devices_SerialCommunication\", \"Win32_Devices_Tapi\", \"Win32_Devices_Usb\", \"Win32_Devices_WebServicesOnDevices\", \"Win32_Foundation\", \"Win32_Gaming\", \"Win32_Globalization\", \"Win32_Graphics\", \"Win32_Graphics_Dwm\", \"Win32_Graphics_Gdi\", \"Win32_Graphics_Hlsl\", \"Win32_Graphics_OpenGL\", \"Win32_Graphics_Printing\", \"Win32_Graphics_Printing_PrintTicket\", \"Win32_Management\", \"Win32_Management_MobileDeviceManagementRegistration\", \"Win32_Media\", \"Win32_Media_Audio\", \"Win32_Media_Audio_Apo\", \"Win32_Media_Audio_DirectMusic\", \"Win32_Media_Audio_Endpoints\", \"Win32_Media_Audio_XAudio2\", \"Win32_Media_DeviceManager\", \"Win32_Media_DxMediaObjects\", \"Win32_Media_KernelStreaming\", \"Win32_Media_LibrarySharingServices\", \"Win32_Media_MediaPlayer\", \"Win32_Media_Multimedia\", \"Win32_Media_Speech\", \"Win32_Media_Streaming\", \"Win32_Media_WindowsMediaFormat\", \"Win32_NetworkManagement\", \"Win32_NetworkManagement_Dhcp\", \"Win32_NetworkManagement_Dns\", \"Win32_NetworkManagement_InternetConnectionWizard\", \"Win32_NetworkManagement_IpHelper\", \"Win32_NetworkManagement_MobileBroadband\", \"Win32_NetworkManagement_Multicast\", \"Win32_NetworkManagement_Ndis\", \"Win32_NetworkManagement_NetBios\", \"Win32_NetworkManagement_NetManagement\", \"Win32_NetworkManagement_NetShell\", \"Win32_NetworkManagement_NetworkDiagnosticsFramework\", \"Win32_NetworkManagement_NetworkPolicyServer\", \"Win32_NetworkManagement_P2P\", \"Win32_NetworkManagement_QoS\", \"Win32_NetworkManagement_Rras\", \"Win32_NetworkManagement_Snmp\", \"Win32_NetworkManagement_WNet\", \"Win32_NetworkManagement_WebDav\", \"Win32_NetworkManagement_WiFi\", \"Win32_NetworkManagement_WindowsConnectNow\", \"Win32_NetworkManagement_WindowsConnectionManager\", \"Win32_NetworkManagement_WindowsFilteringPlatform\", \"Win32_NetworkManagement_WindowsFirewall\", \"Win32_NetworkManagement_WindowsNetworkVirtualization\", \"Win32_Networking\", \"Win32_Networking_ActiveDirectory\", \"Win32_Networking_BackgroundIntelligentTransferService\", \"Win32_Networking_Clustering\", \"Win32_Networking_HttpServer\", \"Win32_Networking_Ldap\", \"Win32_Networking_NetworkListManager\", \"Win32_Networking_RemoteDifferentialCompression\", \"Win32_Networking_WebSocket\", \"Win32_Networking_WinHttp\", \"Win32_Networking_WinInet\", \"Win32_Networking_WinSock\", \"Win32_Networking_WindowsWebServices\", \"Win32_Security\", \"Win32_Security_AppLocker\", \"Win32_Security_Authentication\", \"Win32_Security_Authentication_Identity\", \"Win32_Security_Authentication_Identity_Provider\", \"Win32_Security_Authorization\", \"Win32_Security_Authorization_UI\", \"Win32_Security_ConfigurationSnapin\", \"Win32_Security_Credentials\", \"Win32_Security_Cryptography\", \"Win32_Security_Cryptography_Catalog\", \"Win32_Security_Cryptography_Certificates\", \"Win32_Security_Cryptography_Sip\", \"Win32_Security_Cryptography_UI\", \"Win32_Security_DiagnosticDataQuery\", \"Win32_Security_DirectoryServices\", \"Win32_Security_EnterpriseData\", \"Win32_Security_ExtensibleAuthenticationProtocol\", \"Win32_Security_Isolation\", \"Win32_Security_LicenseProtection\", \"Win32_Security_NetworkAccessProtection\", \"Win32_Security_Tpm\", \"Win32_Security_WinTrust\", \"Win32_Security_WinWlx\", \"Win32_Storage\", \"Win32_Storage_Cabinets\", \"Win32_Storage_CloudFilters\", \"Win32_Storage_Compression\", \"Win32_Storage_DataDeduplication\", \"Win32_Storage_DistributedFileSystem\", \"Win32_Storage_EnhancedStorage\", \"Win32_Storage_FileHistory\", \"Win32_Storage_FileServerResourceManager\", \"Win32_Storage_FileSystem\", \"Win32_Storage_Imapi\", \"Win32_Storage_IndexServer\", \"Win32_Storage_InstallableFileSystems\", \"Win32_Storage_IscsiDisc\", \"Win32_Storage_Jet\", \"Win32_Storage_OfflineFiles\", \"Win32_Storage_OperationRecorder\", \"Win32_Storage_Packaging\", \"Win32_Storage_Packaging_Appx\", \"Win32_Storage_Packaging_Opc\", \"Win32_Storage_ProjectedFileSystem\", \"Win32_Storage_StructuredStorage\", \"Win32_Storage_Vhd\", \"Win32_Storage_VirtualDiskService\", \"Win32_Storage_Vss\", \"Win32_Storage_Xps\", \"Win32_Storage_Xps_Printing\", \"Win32_System\", \"Win32_System_AddressBook\", \"Win32_System_Antimalware\", \"Win32_System_ApplicationInstallationAndServicing\", \"Win32_System_ApplicationVerifier\", \"Win32_System_AssessmentTool\", \"Win32_System_ClrHosting\", \"Win32_System_Com\", \"Win32_System_Com_CallObj\", \"Win32_System_Com_ChannelCredentials\", \"Win32_System_Com_Events\", \"Win32_System_Com_Marshal\", \"Win32_System_Com_StructuredStorage\", \"Win32_System_Com_UI\", \"Win32_System_Com_Urlmon\", \"Win32_System_ComponentServices\", \"Win32_System_Console\", \"Win32_System_Contacts\", \"Win32_System_CorrelationVector\", \"Win32_System_DataExchange\", \"Win32_System_DeploymentServices\", \"Win32_System_DesktopSharing\", \"Win32_System_DeveloperLicensing\", \"Win32_System_Diagnostics\", \"Win32_System_Diagnostics_Ceip\", \"Win32_System_Diagnostics_ClrProfiling\", \"Win32_System_Diagnostics_Debug\", \"Win32_System_Diagnostics_Debug_ActiveScript\", \"Win32_System_Diagnostics_Debug_Extensions\", \"Win32_System_Diagnostics_Etw\", \"Win32_System_Diagnostics_ProcessSnapshotting\", \"Win32_System_Diagnostics_ToolHelp\", \"Win32_System_DistributedTransactionCoordinator\", \"Win32_System_Environment\", \"Win32_System_ErrorReporting\", \"Win32_System_EventCollector\", \"Win32_System_EventLog\", \"Win32_System_EventNotificationService\", \"Win32_System_GroupPolicy\", \"Win32_System_HostCompute\", \"Win32_System_HostComputeNetwork\", \"Win32_System_HostComputeSystem\", \"Win32_System_Hypervisor\", \"Win32_System_IO\", \"Win32_System_Iis\", \"Win32_System_Ioctl\", \"Win32_System_JobObjects\", \"Win32_System_Js\", \"Win32_System_Kernel\", \"Win32_System_LibraryLoader\", \"Win32_System_Mailslots\", \"Win32_System_Mapi\", \"Win32_System_Memory\", \"Win32_System_Memory_NonVolatile\", \"Win32_System_MessageQueuing\", \"Win32_System_MixedReality\", \"Win32_System_Mmc\", \"Win32_System_Ole\", \"Win32_System_ParentalControls\", \"Win32_System_PasswordManagement\", \"Win32_System_Performance\", \"Win32_System_Performance_HardwareCounterProfiling\", \"Win32_System_Pipes\", \"Win32_System_Power\", \"Win32_System_ProcessStatus\", \"Win32_System_RealTimeCommunications\", \"Win32_System_Recovery\", \"Win32_System_Registry\", \"Win32_System_RemoteAssistance\", \"Win32_System_RemoteDesktop\", \"Win32_System_RemoteManagement\", \"Win32_System_RestartManager\", \"Win32_System_Restore\", \"Win32_System_Rpc\", \"Win32_System_Search\", \"Win32_System_Search_Common\", \"Win32_System_SecurityCenter\", \"Win32_System_ServerBackup\", \"Win32_System_Services\", \"Win32_System_SettingsManagementInfrastructure\", \"Win32_System_SetupAndMigration\", \"Win32_System_Shutdown\", \"Win32_System_StationsAndDesktops\", \"Win32_System_SubsystemForLinux\", \"Win32_System_SystemInformation\", \"Win32_System_SystemServices\", \"Win32_System_TaskScheduler\", \"Win32_System_Threading\", \"Win32_System_Time\", \"Win32_System_TpmBaseServices\", \"Win32_System_UpdateAgent\", \"Win32_System_UpdateAssessment\", \"Win32_System_UserAccessLogging\", \"Win32_System_VirtualDosMachines\", \"Win32_System_WindowsProgramming\", \"Win32_System_WindowsSync\", \"Win32_System_Wmi\", \"Win32_UI\", \"Win32_UI_Accessibility\", \"Win32_UI_Animation\", \"Win32_UI_ColorSystem\", \"Win32_UI_Controls\", \"Win32_UI_Controls_Dialogs\", \"Win32_UI_Controls_RichEdit\", \"Win32_UI_HiDpi\", \"Win32_UI_Input\", \"Win32_UI_Input_Ime\", \"Win32_UI_Input_Ink\", \"Win32_UI_Input_KeyboardAndMouse\", \"Win32_UI_Input_Pointer\", \"Win32_UI_Input_Radial\", \"Win32_UI_Input_Touch\", \"Win32_UI_Input_XboxController\", \"Win32_UI_InteractionContext\", \"Win32_UI_LegacyWindowsEnvironmentFeatures\", \"Win32_UI_Magnification\", \"Win32_UI_Notifications\", \"Win32_UI_Ribbon\", \"Win32_UI_Shell\", \"Win32_UI_Shell_Common\", \"Win32_UI_Shell_PropertiesSystem\", \"Win32_UI_TabletPC\", \"Win32_UI_TextServices\", \"Win32_UI_WindowsAndMessaging\", \"Win32_UI_Wpf\", \"Win32_Web\", \"Win32_Web_InternetExplorer\", \"default\"))",
    "-C",
    "metadata=b5b51020364d6d0c",
    "-C",
    "extra-filename=-80bdfb6f4e0c903e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--extern",
    "windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_targets-cf26163e4cd2c220.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:39.543694+00:00",
  "end_time": "2026-07-13T16:48:42.158612+00:00",
  "start_unix_nanos": 1783961319543694000,
  "end_unix_nanos": 1783961322158612500,
  "crate_name": "windows_sys",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

#### Record 42

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "winit:0.29.15:17260",
  "root_process_pid": 8280,
  "pid": 7700,
  "ppid": 9664,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "winit",
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
    "feature=\"ahash\"",
    "--cfg",
    "feature=\"bytemuck\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"memmap2\"",
    "--cfg",
    "feature=\"percent-encoding\"",
    "--cfg",
    "feature=\"rwh_06\"",
    "--cfg",
    "feature=\"sctk\"",
    "--cfg",
    "feature=\"sctk-adwaita\"",
    "--cfg",
    "feature=\"wayland\"",
    "--cfg",
    "feature=\"wayland-backend\"",
    "--cfg",
    "feature=\"wayland-client\"",
    "--cfg",
    "feature=\"wayland-csd-adwaita\"",
    "--cfg",
    "feature=\"wayland-dlopen\"",
    "--cfg",
    "feature=\"wayland-protocols\"",
    "--cfg",
    "feature=\"wayland-protocols-plasma\"",
    "--cfg",
    "feature=\"x11\"",
    "--cfg",
    "feature=\"x11-dl\"",
    "--cfg",
    "feature=\"x11rb\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"ahash\", \"android-game-activity\", \"android-native-activity\", \"bytemuck\", \"default\", \"memmap2\", \"mint\", \"percent-encoding\", \"rwh_04\", \"rwh_05\", \"rwh_06\", \"sctk\", \"sctk-adwaita\", \"serde\", \"wayland\", \"wayland-backend\", \"wayland-client\", \"wayland-csd-adwaita\", \"wayland-csd-adwaita-crossfont\", \"wayland-csd-adwaita-notitle\", \"wayland-dlopen\", \"wayland-protocols\", \"wayland-protocols-plasma\", \"x11\", \"x11-dl\", \"x11rb\"))",
    "-C",
    "metadata=735ce2361f38dada",
    "-C",
    "extra-filename=-651ac98e096969a1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--extern",
    "bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libbitflags-0667b619dfc545b1.rmeta",
    "--extern",
    "cursor_icon=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcursor_icon-7064bb38659984d2.rmeta",
    "--extern",
    "log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\liblog-c49eeec8812cf892.rmeta",
    "--extern",
    "once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libonce_cell-d076018eae555cad.rmeta",
    "--extern",
    "rwh_06=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libraw_window_handle-8084b02d24173edc.rmeta",
    "--extern",
    "smol_str=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libsmol_str-a58cc8446871329b.rmeta",
    "--extern",
    "unicode_segmentation=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libunicode_segmentation-82c365516f112666.rmeta",
    "--extern",
    "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_sys-80bdfb6f4e0c903e.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
    "--cfg",
    "windows_platform"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name winit --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"ahash\\\"\" --cfg \"feature=\\\"bytemuck\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"memmap2\\\"\" --cfg \"feature=\\\"percent-encoding\\\"\" --cfg \"feature=\\\"rwh_06\\\"\" --cfg \"feature=\\\"sctk\\\"\" --cfg \"feature=\\\"sctk-adwaita\\\"\" --cfg \"feature=\\\"wayland\\\"\" --cfg \"feature=\\\"wayland-backend\\\"\" --cfg \"feature=\\\"wayland-client\\\"\" --cfg \"feature=\\\"wayland-csd-adwaita\\\"\" --cfg \"feature=\\\"wayland-dlopen\\\"\" --cfg \"feature=\\\"wayland-protocols\\\"\" --cfg \"feature=\\\"wayland-protocols-plasma\\\"\" --cfg \"feature=\\\"x11\\\"\" --cfg \"feature=\\\"x11-dl\\\"\" --cfg \"feature=\\\"x11rb\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"ahash\\\", \\\"android-game-activity\\\", \\\"android-native-activity\\\", \\\"bytemuck\\\", \\\"default\\\", \\\"memmap2\\\", \\\"mint\\\", \\\"percent-encoding\\\", \\\"rwh_04\\\", \\\"rwh_05\\\", \\\"rwh_06\\\", \\\"sctk\\\", \\\"sctk-adwaita\\\", \\\"serde\\\", \\\"wayland\\\", \\\"wayland-backend\\\", \\\"wayland-client\\\", \\\"wayland-csd-adwaita\\\", \\\"wayland-csd-adwaita-crossfont\\\", \\\"wayland-csd-adwaita-notitle\\\", \\\"wayland-dlopen\\\", \\\"wayland-protocols\\\", \\\"wayland-protocols-plasma\\\", \\\"x11\\\", \\\"x11-dl\\\", \\\"x11rb\\\"))\" -C metadata=735ce2361f38dada -C extra-filename=-651ac98e096969a1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --extern bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libbitflags-0667b619dfc545b1.rmeta --extern cursor_icon=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcursor_icon-7064bb38659984d2.rmeta --extern log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\liblog-c49eeec8812cf892.rmeta --extern once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libonce_cell-d076018eae555cad.rmeta --extern rwh_06=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libraw_window_handle-8084b02d24173edc.rmeta --extern smol_str=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libsmol_str-a58cc8446871329b.rmeta --extern unicode_segmentation=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libunicode_segmentation-82c365516f112666.rmeta --extern windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_sys-80bdfb6f4e0c903e.rmeta -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib --cfg windows_platform",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "winit",
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
    "feature=\"ahash\"",
    "--cfg",
    "feature=\"bytemuck\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"memmap2\"",
    "--cfg",
    "feature=\"percent-encoding\"",
    "--cfg",
    "feature=\"rwh_06\"",
    "--cfg",
    "feature=\"sctk\"",
    "--cfg",
    "feature=\"sctk-adwaita\"",
    "--cfg",
    "feature=\"wayland\"",
    "--cfg",
    "feature=\"wayland-backend\"",
    "--cfg",
    "feature=\"wayland-client\"",
    "--cfg",
    "feature=\"wayland-csd-adwaita\"",
    "--cfg",
    "feature=\"wayland-dlopen\"",
    "--cfg",
    "feature=\"wayland-protocols\"",
    "--cfg",
    "feature=\"wayland-protocols-plasma\"",
    "--cfg",
    "feature=\"x11\"",
    "--cfg",
    "feature=\"x11-dl\"",
    "--cfg",
    "feature=\"x11rb\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"ahash\", \"android-game-activity\", \"android-native-activity\", \"bytemuck\", \"default\", \"memmap2\", \"mint\", \"percent-encoding\", \"rwh_04\", \"rwh_05\", \"rwh_06\", \"sctk\", \"sctk-adwaita\", \"serde\", \"wayland\", \"wayland-backend\", \"wayland-client\", \"wayland-csd-adwaita\", \"wayland-csd-adwaita-crossfont\", \"wayland-csd-adwaita-notitle\", \"wayland-dlopen\", \"wayland-protocols\", \"wayland-protocols-plasma\", \"x11\", \"x11-dl\", \"x11rb\"))",
    "-C",
    "metadata=735ce2361f38dada",
    "-C",
    "extra-filename=-651ac98e096969a1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
    "--extern",
    "bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libbitflags-0667b619dfc545b1.rmeta",
    "--extern",
    "cursor_icon=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcursor_icon-7064bb38659984d2.rmeta",
    "--extern",
    "log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\liblog-c49eeec8812cf892.rmeta",
    "--extern",
    "once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libonce_cell-d076018eae555cad.rmeta",
    "--extern",
    "rwh_06=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libraw_window_handle-8084b02d24173edc.rmeta",
    "--extern",
    "smol_str=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libsmol_str-a58cc8446871329b.rmeta",
    "--extern",
    "unicode_segmentation=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libunicode_segmentation-82c365516f112666.rmeta",
    "--extern",
    "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_sys-80bdfb6f4e0c903e.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
    "--cfg",
    "windows_platform"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T16:48:41.826319+00:00",
  "end_time": "2026-07-13T16:48:45.039551+00:00",
  "start_unix_nanos": 1783961321826318900,
  "end_unix_nanos": 1783961325039550800,
  "crate_name": "winit",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T16:48:46.137401+00:00",
  "crate": "winit",
  "version": "0.29.15",
  "duration_seconds": 36.11415839998517,
  "trace_record_count": 23,
  "trace_owner_summary": {
    "owner_package_count": 197,
    "owner_packages": [
      {
        "crate": "wasi",
        "version": "0.11.0+wasi-snapshot-preview1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml"
      },
      {
        "crate": "winapi-x86_64-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro-support",
        "version": "0.2.91",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.91",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.91",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.91/Cargo.toml"
      },
      {
        "crate": "winapi-i686-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "wayland-protocols-plasma",
        "version": "0.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-protocols-plasma@0.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-plasma-0.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-plasma-0.2.0/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_gnullvm",
        "version": "0.42.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.42.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.42.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.42.2/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_gnullvm",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_gnullvm",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.0/Cargo.toml"
      },
      {
        "crate": "smithay-client-toolkit",
        "version": "0.18.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#smithay-client-toolkit@0.18.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smithay-client-toolkit-0.18.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smithay-client-toolkit-0.18.0/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnullvm",
        "version": "0.42.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.42.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.42.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.42.2/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnullvm",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnullvm",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.0/Cargo.toml"
      },
      {
        "crate": "calloop-wayland-source",
        "version": "0.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#calloop-wayland-source@0.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-wayland-source-0.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-wayland-source-0.2.0/Cargo.toml"
      },
      {
        "crate": "as-raw-xcb-connection",
        "version": "1.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#as-raw-xcb-connection@1.0.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/as-raw-xcb-connection-1.0.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/as-raw-xcb-connection-1.0.1/Cargo.toml"
      },
      {
        "crate": "unicode-segmentation",
        "version": "1.11.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-segmentation@1.11.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-segmentation-1.11.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-segmentation-1.11.0/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-backend",
        "version": "0.2.91",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.91",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.91",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.91/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-futures",
        "version": "0.4.41",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-futures@0.4.41",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-futures-0.4.41",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-futures-0.4.41/Cargo.toml"
      },
      {
        "crate": "wayland-protocols-wlr",
        "version": "0.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-protocols-wlr@0.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-wlr-0.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-wlr-0.2.0/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.42.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.42.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.42.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.42.2/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.0/Cargo.toml"
      },
      {
        "crate": "foreign-types-macros",
        "version": "0.2.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#foreign-types-macros@0.2.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foreign-types-macros-0.2.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foreign-types-macros-0.2.3/Cargo.toml"
      },
      {
        "crate": "foreign-types-shared",
        "version": "0.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#foreign-types-shared@0.3.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foreign-types-shared-0.3.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foreign-types-shared-0.3.1/Cargo.toml"
      },
      {
        "crate": "ndk-sys",
        "version": "0.5.0+25.2.9519653",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ndk-sys@0.5.0+25.2.9519653",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ndk-sys-0.5.0+25.2.9519653",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ndk-sys-0.5.0+25.2.9519653/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-shared",
        "version": "0.2.91",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.91",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.91",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.91/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.42.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.42.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.42.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.42.2/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.0/Cargo.toml"
      },
      {
        "crate": "ab_glyph_rasterizer",
        "version": "0.1.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ab_glyph_rasterizer@0.1.8",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ab_glyph_rasterizer-0.1.8",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ab_glyph_rasterizer-0.1.8/Cargo.toml"
      },
      {
        "crate": "core-foundation-sys",
        "version": "0.8.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-foundation-sys@0.8.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-foundation-sys-0.8.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-foundation-sys-0.8.6/Cargo.toml"
      },
      {
        "crate": "core-graphics-types",
        "version": "0.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-graphics-types@0.1.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-graphics-types-0.1.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-graphics-types-0.1.3/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro",
        "version": "0.2.91",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.91",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.91",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.91/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.42.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.42.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.42.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.42.2/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.0/Cargo.toml"
      },
      {
        "crate": "android-properties",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#android-properties@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/android-properties-0.2.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/android-properties-0.2.2/Cargo.toml"
      },
      {
        "crate": "wayland-protocols",
        "version": "0.31.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-protocols@0.31.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-0.31.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-protocols-0.31.2/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.42.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.42.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.42.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.42.2/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.0/Cargo.toml"
      },
      {
        "crate": "owned_ttf_parser",
        "version": "0.20.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#owned_ttf_parser@0.20.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/owned_ttf_parser-0.20.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/owned_ttf_parser-0.20.0/Cargo.toml"
      },
      {
        "crate": "pin-project-lite",
        "version": "0.2.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.13",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.13",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.13/Cargo.toml"
      },
      {
        "crate": "raw-window-handle",
        "version": "0.5.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#raw-window-handle@0.5.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/raw-window-handle-0.5.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/raw-window-handle-0.5.2/Cargo.toml"
      },
      {
        "crate": "raw-window-handle",
        "version": "0.6.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#raw-window-handle@0.6.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/raw-window-handle-0.6.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/raw-window-handle-0.6.0/Cargo.toml"
      },
      {
        "crate": "wayland-csd-frame",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-csd-frame@0.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-csd-frame-0.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-csd-frame-0.3.0/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.42.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.42.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.42.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.42.2/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.0/Cargo.toml"
      },
      {
        "crate": "android-activity",
        "version": "0.5.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#android-activity@0.5.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/android-activity-0.5.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/android-activity-0.5.2/Cargo.toml"
      },
      {
        "crate": "cocoa-foundation",
        "version": "0.1.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cocoa-foundation@0.1.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cocoa-foundation-0.1.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cocoa-foundation-0.1.2/Cargo.toml"
      },
      {
        "crate": "concurrent-queue",
        "version": "2.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#concurrent-queue@2.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.4.0/Cargo.toml"
      },
      {
        "crate": "crossbeam-utils",
        "version": "0.8.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.19",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.19",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.19/Cargo.toml"
      },
      {
        "crate": "percent-encoding",
        "version": "2.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#percent-encoding@2.3.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/percent-encoding-2.3.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/percent-encoding-2.3.1/Cargo.toml"
      },
      {
        "crate": "proc-macro-crate",
        "version": "1.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro-crate@1.3.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-crate-1.3.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-crate-1.3.1/Cargo.toml"
      },
      {
        "crate": "wayland-scanner",
        "version": "0.31.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-scanner@0.31.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-scanner-0.31.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-scanner-0.31.1/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.42.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.42.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.42.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.42.2/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.0/Cargo.toml"
      },
      {
        "crate": "zerocopy-derive",
        "version": "0.7.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy-derive@0.7.32",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.7.32",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.7.32/Cargo.toml"
      },
      {
        "crate": "bytemuck_derive",
        "version": "1.6.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bytemuck_derive@1.6.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck_derive-1.6.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck_derive-1.6.0/Cargo.toml"
      },
      {
        "crate": "core-foundation",
        "version": "0.9.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-foundation@0.9.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-foundation-0.9.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-foundation-0.9.4/Cargo.toml"
      },
      {
        "crate": "num_enum_derive",
        "version": "0.7.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num_enum_derive@0.7.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num_enum_derive-0.7.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num_enum_derive-0.7.2/Cargo.toml"
      },
      {
        "crate": "thiserror-impl",
        "version": "1.0.56",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror-impl@1.0.56",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.56",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.56/Cargo.toml"
      },
      {
        "crate": "tiny-skia-path",
        "version": "0.11.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tiny-skia-path@0.11.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tiny-skia-path-0.11.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tiny-skia-path-0.11.4/Cargo.toml"
      },
      {
        "crate": "wayland-backend",
        "version": "0.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-backend@0.3.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-backend-0.3.3/Cargo.toml"
      },
      {
        "crate": "wayland-client",
        "version": "0.31.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-client@0.31.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-client-0.31.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-client-0.31.2/Cargo.toml"
      },
      {
        "crate": "wayland-cursor",
        "version": "0.31.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-cursor@0.31.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-cursor-0.31.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-cursor-0.31.1/Cargo.toml"
      },
      {
        "crate": "x11rb-protocol",
        "version": "0.12.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb-protocol@0.12.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-protocol-0.12.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-protocol-0.12.0/Cargo.toml"
      },
      {
        "crate": "x11rb-protocol",
        "version": "0.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb-protocol@0.13.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-protocol-0.13.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-protocol-0.13.0/Cargo.toml"
      },
      {
        "crate": "core-graphics",
        "version": "0.23.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-graphics@0.23.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-graphics-0.23.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-graphics-0.23.1/Cargo.toml"
      },
      {
        "crate": "linux-raw-sys",
        "version": "0.4.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.13",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.13",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.13/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.196",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.196",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.196",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.196/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml"
      },
      {
        "crate": "winapi-wsapoll",
        "version": "0.1.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-wsapoll@0.1.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-wsapoll-0.1.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-wsapoll-0.1.1/Cargo.toml"
      },
      {
        "crate": "foreign-types",
        "version": "0.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#foreign-types@0.5.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foreign-types-0.5.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foreign-types-0.5.0/Cargo.toml"
      },
      {
        "crate": "linux-raw-sys",
        "version": "0.6.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.6.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.6.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.6.4/Cargo.toml"
      },
      {
        "crate": "redox_syscall",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.3.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/redox_syscall-0.3.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/redox_syscall-0.3.5/Cargo.toml"
      },
      {
        "crate": "redox_syscall",
        "version": "0.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.4.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/redox_syscall-0.4.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/redox_syscall-0.4.1/Cargo.toml"
      },
      {
        "crate": "simple_logger",
        "version": "4.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#simple_logger@4.3.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/simple_logger-4.3.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/simple_logger-4.3.3/Cargo.toml"
      },
      {
        "crate": "toml_datetime",
        "version": "0.6.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@0.6.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.5/Cargo.toml"
      },
      {
        "crate": "tracing-core",
        "version": "0.1.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tracing-core@0.1.32",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tracing-core-0.1.32",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tracing-core-0.1.32/Cargo.toml"
      },
      {
        "crate": "version_check",
        "version": "0.9.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.4/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen",
        "version": "0.2.91",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.91",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.91",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.91/Cargo.toml"
      },
      {
        "crate": "atomic-waker",
        "version": "1.1.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#atomic-waker@1.1.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2/Cargo.toml"
      },
      {
        "crate": "objc2-encode",
        "version": "3.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc2-encode@3.0.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/objc2-encode-3.0.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/objc2-encode-3.0.0/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.78",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.78",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78/Cargo.toml"
      },
      {
        "crate": "sctk-adwaita",
        "version": "0.8.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#sctk-adwaita@0.8.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sctk-adwaita-0.8.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/sctk-adwaita-0.8.1/Cargo.toml"
      },
      {
        "crate": "simd-adler32",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#simd-adler32@0.3.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/simd-adler32-0.3.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/simd-adler32-0.3.7/Cargo.toml"
      },
      {
        "crate": "wayland-sys",
        "version": "0.31.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-sys@0.31.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-sys-0.31.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wayland-sys-0.31.1/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.45.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.45.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.45.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.45.0/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.48.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.48.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.52.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.52.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.52.0/Cargo.toml"
      },
      {
        "crate": "xkbcommon-dl",
        "version": "0.4.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#xkbcommon-dl@0.4.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/xkbcommon-dl-0.4.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/xkbcommon-dl-0.4.2/Cargo.toml"
      },
      {
        "crate": "cfg_aliases",
        "version": "0.1.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg_aliases@0.1.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg_aliases-0.1.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg_aliases-0.1.1/Cargo.toml"
      },
      {
        "crate": "color_quant",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#color_quant@1.1.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/color_quant-1.1.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/color_quant-1.1.0/Cargo.toml"
      },
      {
        "crate": "console_log",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#console_log@1.0.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console_log-1.0.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console_log-1.0.0/Cargo.toml"
      },
      {
        "crate": "cursor-icon",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cursor-icon@1.1.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cursor-icon-1.1.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cursor-icon-1.1.0/Cargo.toml"
      },
      {
        "crate": "downcast-rs",
        "version": "1.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#downcast-rs@1.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/downcast-rs-1.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/downcast-rs-1.2.0/Cargo.toml"
      },
      {
        "crate": "gethostname",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#gethostname@0.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gethostname-0.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gethostname-0.3.0/Cargo.toml"
      },
      {
        "crate": "gethostname",
        "version": "0.4.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#gethostname@0.4.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gethostname-0.4.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gethostname-0.4.3/Cargo.toml"
      },
      {
        "crate": "miniz_oxide",
        "version": "0.7.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#miniz_oxide@0.7.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/miniz_oxide-0.7.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/miniz_oxide-0.7.2/Cargo.toml"
      },
      {
        "crate": "ndk-context",
        "version": "0.1.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ndk-context@0.1.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ndk-context-0.1.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ndk-context-0.1.1/Cargo.toml"
      },
      {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18/Cargo.toml"
      },
      {
        "crate": "pkg-config",
        "version": "0.3.29",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.29",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.29",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.29/Cargo.toml"
      },
      {
        "crate": "toml_edit",
        "version": "0.19.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_edit@0.19.15",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.19.15",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.19.15/Cargo.toml"
      },
      {
        "crate": "ttf-parser",
        "version": "0.20.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ttf-parser@0.20.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ttf-parser-0.20.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ttf-parser-0.20.0/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6/Cargo.toml"
      },
      {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm-fourcc@2.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-fourcc-2.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-fourcc-2.2.0/Cargo.toml"
      },
      {
        "crate": "equivalent",
        "version": "1.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.1/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.2.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.12",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.12/Cargo.toml"
      },
      {
        "crate": "hashbrown",
        "version": "0.14.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.14.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.14.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.14.3/Cargo.toml"
      },
      {
        "crate": "jobserver",
        "version": "0.1.27",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#jobserver@0.1.27",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/jobserver-0.1.27",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/jobserver-0.1.27/Cargo.toml"
      },
      {
        "crate": "libloading",
        "version": "0.7.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.7.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.7.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.7.4/Cargo.toml"
      },
      {
        "crate": "libloading",
        "version": "0.8.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.8.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.1/Cargo.toml"
      },
      {
        "crate": "malloc_buf",
        "version": "0.0.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#malloc_buf@0.0.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/malloc_buf-0.0.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/malloc_buf-0.0.6/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.19.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.19.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.19.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.19.0/Cargo.toml"
      },
      {
        "crate": "orbclient",
        "version": "0.3.47",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#orbclient@0.3.47",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/orbclient-0.3.47",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/orbclient-0.3.47/Cargo.toml"
      },
      {
        "crate": "quick-xml",
        "version": "0.31.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quick-xml@0.31.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quick-xml-0.31.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quick-xml-0.31.0/Cargo.toml"
      },
      {
        "crate": "scoped-tls",
        "version": "1.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#scoped-tls@1.0.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scoped-tls-1.0.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scoped-tls-1.0.1/Cargo.toml"
      },
      {
        "crate": "softbuffer",
        "version": "0.3.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#softbuffer@0.3.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/softbuffer-0.3.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/softbuffer-0.3.4/Cargo.toml"
      },
      {
        "crate": "strict-num",
        "version": "0.1.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#strict-num@0.1.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strict-num-0.1.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strict-num-0.1.1/Cargo.toml"
      },
      {
        "crate": "thiserror",
        "version": "1.0.56",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror@1.0.56",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.56",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.56/Cargo.toml"
      },
      {
        "crate": "tiny-skia",
        "version": "0.11.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tiny-skia@0.11.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tiny-skia-0.11.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tiny-skia-0.11.4/Cargo.toml"
      },
      {
        "crate": "ab_glyph",
        "version": "0.2.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ab_glyph@0.2.23",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ab_glyph-0.2.23",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ab_glyph-0.2.23/Cargo.toml"
      },
      {
        "crate": "block-sys",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#block-sys@0.2.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/block-sys-0.2.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/block-sys-0.2.1/Cargo.toml"
      },
      {
        "crate": "bytemuck",
        "version": "1.14.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bytemuck@1.14.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.14.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytemuck-1.14.2/Cargo.toml"
      },
      {
        "crate": "byteorder",
        "version": "1.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#byteorder@1.5.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0/Cargo.toml"
      },
      {
        "crate": "crc32fast",
        "version": "1.3.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crc32fast@1.3.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crc32fast-1.3.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crc32fast-1.3.2/Cargo.toml"
      },
      {
        "crate": "memoffset",
        "version": "0.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.7.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.7.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.7.1/Cargo.toml"
      },
      {
        "crate": "same-file",
        "version": "1.0.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml"
      },
      {
        "crate": "smallvec",
        "version": "1.13.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#smallvec@1.13.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smallvec-1.13.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smallvec-1.13.1/Cargo.toml"
      },
      {
        "crate": "tiny-xlib",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tiny-xlib@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tiny-xlib-0.2.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tiny-xlib-0.2.2/Cargo.toml"
      },
      {
        "crate": "zerocopy",
        "version": "0.7.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy@0.7.32",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.7.32",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.7.32/Cargo.toml"
      },
      {
        "crate": "arrayref",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayref@0.3.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arrayref-0.3.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arrayref-0.3.7/Cargo.toml"
      },
      {
        "crate": "arrayvec",
        "version": "0.7.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayvec@0.7.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arrayvec-0.7.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arrayvec-0.7.4/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "1.3.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "2.4.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.4.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.2/Cargo.toml"
      },
      {
        "crate": "bumpalo",
        "version": "3.14.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml"
      },
      {
        "crate": "calloop",
        "version": "0.12.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#calloop@0.12.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-0.12.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/calloop-0.12.4/Cargo.toml"
      },
      {
        "crate": "dispatch",
        "version": "0.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#dispatch@0.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dispatch-0.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dispatch-0.2.0/Cargo.toml"
      },
      {
        "crate": "fastrand",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.0.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.0.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.0.1/Cargo.toml"
      },
      {
        "crate": "fdeflate",
        "version": "0.3.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fdeflate@0.3.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fdeflate-0.3.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fdeflate-0.3.4/Cargo.toml"
      },
      {
        "crate": "indexmap",
        "version": "2.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.2.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.2.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.2.2/Cargo.toml"
      },
      {
        "crate": "libredox",
        "version": "0.0.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libredox@0.0.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libredox-0.0.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libredox-0.0.2/Cargo.toml"
      },
      {
        "crate": "num_enum",
        "version": "0.7.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num_enum@0.7.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num_enum-0.7.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num_enum-0.7.2/Cargo.toml"
      },
      {
        "crate": "objc-sys",
        "version": "0.3.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc-sys@0.3.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/objc-sys-0.3.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/objc-sys-0.3.2/Cargo.toml"
      },
      {
        "crate": "rustix",
        "version": "0.38.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.31/Cargo.toml"
      },
      {
        "crate": "smol_str",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#smol_str@0.2.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smol_str-0.2.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smol_str-0.2.1/Cargo.toml"
      },
      {
        "crate": "tracing",
        "version": "0.1.40",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tracing@0.1.40",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tracing-0.1.40",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tracing-0.1.40/Cargo.toml"
      },
      {
        "crate": "web-sys",
        "version": "0.3.68",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.68",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.68",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.68/Cargo.toml"
      },
      {
        "crate": "web-time",
        "version": "0.2.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-time@0.2.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-time-0.2.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-time-0.2.4/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml"
      },
      {
        "crate": "combine",
        "version": "4.6.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#combine@4.6.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/combine-4.6.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/combine-4.6.6/Cargo.toml"
      },
      {
        "crate": "drm-ffi",
        "version": "0.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm-ffi@0.7.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-ffi-0.7.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-ffi-0.7.1/Cargo.toml"
      },
      {
        "crate": "drm-sys",
        "version": "0.6.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm-sys@0.6.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-sys-0.6.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-sys-0.6.1/Cargo.toml"
      },
      {
        "crate": "flate2",
        "version": "1.0.28",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#flate2@1.0.28",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/flate2-1.0.28",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/flate2-1.0.28/Cargo.toml"
      },
      {
        "crate": "jni-sys",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#jni-sys@0.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/jni-sys-0.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/jni-sys-0.3.0/Cargo.toml"
      },
      {
        "crate": "js-sys",
        "version": "0.3.68",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.68",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.68",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.68/Cargo.toml"
      },
      {
        "crate": "memmap2",
        "version": "0.9.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memmap2@0.9.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memmap2-0.9.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memmap2-0.9.4/Cargo.toml"
      },
      {
        "crate": "polling",
        "version": "3.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#polling@3.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/polling-3.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/polling-3.4.0/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.196",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.196",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.196",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.196/Cargo.toml"
      },
      {
        "crate": "walkdir",
        "version": "2.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0/Cargo.toml"
      },
      {
        "crate": "winnow",
        "version": "0.5.39",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@0.5.39",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.5.39",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.5.39/Cargo.toml"
      },
      {
        "crate": "x11-dl",
        "version": "2.21.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11-dl@2.21.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11-dl-2.21.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11-dl-2.21.0/Cargo.toml"
      },
      {
        "crate": "xcursor",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#xcursor@0.3.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/xcursor-0.3.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/xcursor-0.3.5/Cargo.toml"
      },
      {
        "crate": "xkeysym",
        "version": "0.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#xkeysym@0.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/xkeysym-0.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/xkeysym-0.2.0/Cargo.toml"
      },
      {
        "crate": "block2",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#block2@0.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/block2-0.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/block2-0.3.0/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml"
      },
      {
        "crate": "cocoa",
        "version": "0.25.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cocoa@0.25.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cocoa-0.25.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cocoa-0.25.0/Cargo.toml"
      },
      {
        "crate": "icrate",
        "version": "0.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#icrate@0.0.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icrate-0.0.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icrate-0.0.4/Cargo.toml"
      },
      {
        "crate": "image",
        "version": "0.24.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#image@0.24.8",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/image-0.24.8",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/image-0.24.8/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.153",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.153/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.1/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.35",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.35",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "x11rb",
        "version": "0.12.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb@0.12.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.12.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.12.0/Cargo.toml"
      },
      {
        "crate": "x11rb",
        "version": "0.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb@0.13.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.13.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/x11rb-0.13.0/Cargo.toml"
      },
      {
        "crate": "adler",
        "version": "1.0.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#adler@1.0.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/adler-1.0.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/adler-1.0.2/Cargo.toml"
      },
      {
        "crate": "ahash",
        "version": "0.8.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ahash@0.8.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.8.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.8.7/Cargo.toml"
      },
      {
        "crate": "block",
        "version": "0.1.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#block@0.1.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/block-0.1.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/block-0.1.6/Cargo.toml"
      },
      {
        "crate": "bytes",
        "version": "1.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bytes@1.5.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytes-1.5.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytes-1.5.0/Cargo.toml"
      },
      {
        "crate": "cesu8",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cesu8@1.1.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cesu8-1.1.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cesu8-1.1.0/Cargo.toml"
      },
      {
        "crate": "errno",
        "version": "0.3.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.8",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.8",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.8/Cargo.toml"
      },
      {
        "crate": "objc2",
        "version": "0.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc2@0.4.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/objc2-0.4.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/objc2-0.4.1/Cargo.toml"
      },
      {
        "crate": "png",
        "version": "0.17.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#png@0.17.11",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/png-0.17.11",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/png-0.17.11/Cargo.toml"
      },
      {
        "crate": "ctor",
        "version": "0.2.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ctor@0.2.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ctor-0.2.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ctor-0.2.6/Cargo.toml"
      },
      {
        "crate": "dlib",
        "version": "0.5.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#dlib@0.5.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dlib-0.5.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dlib-0.5.2/Cargo.toml"
      },
      {
        "crate": "drm",
        "version": "0.11.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm@0.11.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-0.11.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/drm-0.11.1/Cargo.toml"
      },
      {
        "crate": "jni",
        "version": "0.21.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#jni@0.21.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/jni-0.21.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/jni-0.21.1/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml"
      },
      {
        "crate": "nix",
        "version": "0.26.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#nix@0.26.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nix-0.26.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/nix-0.26.4/Cargo.toml"
      },
      {
        "crate": "objc",
        "version": "0.2.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc@0.2.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/objc-0.2.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/objc-0.2.7/Cargo.toml"
      },
      {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.9/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.48",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.48",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.48",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.48/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.0.83",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/Cargo.toml"
      },
      {
        "crate": "ndk",
        "version": "0.8.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ndk@0.8.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ndk-0.8.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ndk-0.8.0/Cargo.toml"
      },
      {
        "crate": "winit",
        "version": "0.29.15",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15/Cargo.toml"
      }
    ],
    "attributed_event_count": 19,
    "unattributed_event_count": 4,
    "owners": [
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "event_count": 15,
        "kind_counts": {
          "exec": 1,
          "used_input": 10,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "winit",
        "version": "0.29.15",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ab_glyph@0.2.23",
          "name": "ab_glyph",
          "version": "0.2.23",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ab_glyph-0.2.23\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ab_glyph-0.2.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ab_glyph_rasterizer@0.1.8",
          "name": "ab_glyph_rasterizer",
          "version": "0.1.8",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ab_glyph_rasterizer-0.1.8\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ab_glyph_rasterizer-0.1.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#adler@1.0.2",
          "name": "adler",
          "version": "1.0.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler-1.0.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler-1.0.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ahash@0.8.7",
          "name": "ahash",
          "version": "0.8.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ahash-0.8.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ahash-0.8.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#android-activity@0.5.2",
          "name": "android-activity",
          "version": "0.5.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\android-activity-0.5.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\android-activity-0.5.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#android-properties@0.2.2",
          "name": "android-properties",
          "version": "0.2.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\android-properties-0.2.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\android-properties-0.2.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayref@0.3.7",
          "name": "arrayref",
          "version": "0.3.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayvec@0.7.4",
          "name": "arrayvec",
          "version": "0.7.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#as-raw-xcb-connection@1.0.1",
          "name": "as-raw-xcb-connection",
          "version": "1.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\as-raw-xcb-connection-1.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\as-raw-xcb-connection-1.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#atomic-waker@1.1.2",
          "name": "atomic-waker",
          "version": "1.1.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atomic-waker-1.1.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atomic-waker-1.1.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
          "name": "autocfg",
          "version": "1.1.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.1.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
          "name": "bitflags",
          "version": "1.3.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.4.2",
          "name": "bitflags",
          "version": "2.4.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#block@0.1.6",
          "name": "block",
          "version": "0.1.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-0.1.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-0.1.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#block-sys@0.2.1",
          "name": "block-sys",
          "version": "0.2.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-sys-0.2.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-sys-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#block2@0.3.0",
          "name": "block2",
          "version": "0.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block2-0.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block2-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
          "name": "bumpalo",
          "version": "3.14.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.14.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.14.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bytemuck@1.14.2",
          "name": "bytemuck",
          "version": "1.14.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytemuck-1.14.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytemuck-1.14.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bytemuck_derive@1.6.0",
          "name": "bytemuck_derive",
          "version": "1.6.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytemuck_derive-1.6.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytemuck_derive-1.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#byteorder@1.5.0",
          "name": "byteorder",
          "version": "1.5.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\byteorder-1.5.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\byteorder-1.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bytes@1.5.0",
          "name": "bytes",
          "version": "1.5.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytes-1.5.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bytes-1.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#calloop@0.12.4",
          "name": "calloop",
          "version": "0.12.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\calloop-0.12.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\calloop-0.12.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#calloop-wayland-source@0.2.0",
          "name": "calloop-wayland-source",
          "version": "0.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\calloop-wayland-source-0.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\calloop-wayland-source-0.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
          "name": "cc",
          "version": "1.0.83",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.83\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.83"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cesu8@1.1.0",
          "name": "cesu8",
          "version": "1.1.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cesu8-1.1.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cesu8-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg_aliases@0.1.1",
          "name": "cfg_aliases",
          "version": "0.1.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cocoa@0.25.0",
          "name": "cocoa",
          "version": "0.25.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cocoa-0.25.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cocoa-0.25.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cocoa-foundation@0.1.2",
          "name": "cocoa-foundation",
          "version": "0.1.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cocoa-foundation-0.1.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cocoa-foundation-0.1.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#color_quant@1.1.0",
          "name": "color_quant",
          "version": "1.1.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\color_quant-1.1.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\color_quant-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#combine@4.6.6",
          "name": "combine",
          "version": "4.6.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\combine-4.6.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\combine-4.6.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#concurrent-queue@2.4.0",
          "name": "concurrent-queue",
          "version": "2.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\concurrent-queue-2.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\concurrent-queue-2.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#console_log@1.0.0",
          "name": "console_log",
          "version": "1.0.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\console_log-1.0.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\console_log-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-foundation@0.9.4",
          "name": "core-foundation",
          "version": "0.9.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-foundation-0.9.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-foundation-0.9.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-foundation-sys@0.8.6",
          "name": "core-foundation-sys",
          "version": "0.8.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-foundation-sys-0.8.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-foundation-sys-0.8.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-graphics@0.23.1",
          "name": "core-graphics",
          "version": "0.23.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-graphics-0.23.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-graphics-0.23.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#core-graphics-types@0.1.3",
          "name": "core-graphics-types",
          "version": "0.1.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-graphics-types-0.1.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\core-graphics-types-0.1.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crc32fast@1.3.2",
          "name": "crc32fast",
          "version": "1.3.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crc32fast-1.3.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crc32fast-1.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.19",
          "name": "crossbeam-utils",
          "version": "0.8.19",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.19\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ctor@0.2.6",
          "name": "ctor",
          "version": "0.2.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ctor-0.2.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ctor-0.2.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cursor-icon@1.1.0",
          "name": "cursor-icon",
          "version": "1.1.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#dispatch@0.2.0",
          "name": "dispatch",
          "version": "0.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dispatch-0.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dispatch-0.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#dlib@0.5.2",
          "name": "dlib",
          "version": "0.5.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dlib-0.5.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dlib-0.5.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#downcast-rs@1.2.0",
          "name": "downcast-rs",
          "version": "1.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\downcast-rs-1.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\downcast-rs-1.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm@0.11.1",
          "name": "drm",
          "version": "0.11.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-0.11.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-0.11.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm-ffi@0.7.1",
          "name": "drm-ffi",
          "version": "0.7.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-ffi-0.7.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-ffi-0.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm-fourcc@2.2.0",
          "name": "drm-fourcc",
          "version": "2.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-fourcc-2.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-fourcc-2.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#drm-sys@0.6.1",
          "name": "drm-sys",
          "version": "0.6.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-sys-0.6.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\drm-sys-0.6.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.1",
          "name": "equivalent",
          "version": "1.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.8",
          "name": "errno",
          "version": "0.3.8",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.8\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.0.1",
          "name": "fastrand",
          "version": "2.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fdeflate@0.3.4",
          "name": "fdeflate",
          "version": "0.3.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fdeflate-0.3.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fdeflate-0.3.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#flate2@1.0.28",
          "name": "flate2",
          "version": "1.0.28",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\flate2-1.0.28\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\flate2-1.0.28"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#foreign-types@0.5.0",
          "name": "foreign-types",
          "version": "0.5.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-0.5.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-0.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#foreign-types-macros@0.2.3",
          "name": "foreign-types-macros",
          "version": "0.2.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-macros-0.2.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-macros-0.2.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#foreign-types-shared@0.3.1",
          "name": "foreign-types-shared",
          "version": "0.3.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-shared-0.3.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foreign-types-shared-0.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#gethostname@0.3.0",
          "name": "gethostname",
          "version": "0.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gethostname-0.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gethostname-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#gethostname@0.4.3",
          "name": "gethostname",
          "version": "0.4.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gethostname-0.4.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\gethostname-0.4.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.12",
          "name": "getrandom",
          "version": "0.2.12",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.2.12\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.2.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.14.3",
          "name": "hashbrown",
          "version": "0.14.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.14.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.14.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#icrate@0.0.4",
          "name": "icrate",
          "version": "0.0.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\icrate-0.0.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\icrate-0.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#image@0.24.8",
          "name": "image",
          "version": "0.24.8",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\image-0.24.8\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\image-0.24.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.2.2",
          "name": "indexmap",
          "version": "2.2.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.2.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.2.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#jni@0.21.1",
          "name": "jni",
          "version": "0.21.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jni-0.21.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jni-0.21.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#jni-sys@0.3.0",
          "name": "jni-sys",
          "version": "0.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jni-sys-0.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jni-sys-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#jobserver@0.1.27",
          "name": "jobserver",
          "version": "0.1.27",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jobserver-0.1.27\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\jobserver-0.1.27"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.68",
          "name": "js-sys",
          "version": "0.3.68",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.68\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.68"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.153",
          "name": "libc",
          "version": "0.2.153",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.153\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.153"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.7.4",
          "name": "libloading",
          "version": "0.7.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libloading-0.7.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libloading-0.7.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libloading@0.8.1",
          "name": "libloading",
          "version": "0.8.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libloading-0.8.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libloading-0.8.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libredox@0.0.2",
          "name": "libredox",
          "version": "0.0.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libredox-0.0.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libredox-0.0.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.13",
          "name": "linux-raw-sys",
          "version": "0.4.13",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.4.13\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.4.13"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.6.4",
          "name": "linux-raw-sys",
          "version": "0.6.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.6.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.6.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
          "name": "log",
          "version": "0.4.20",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#malloc_buf@0.0.6",
          "name": "malloc_buf",
          "version": "0.0.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\malloc_buf-0.0.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\malloc_buf-0.0.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.1",
          "name": "memchr",
          "version": "2.7.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memmap2@0.9.4",
          "name": "memmap2",
          "version": "0.9.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memmap2-0.9.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memmap2-0.9.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.7.1",
          "name": "memoffset",
          "version": "0.7.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.7.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#miniz_oxide@0.7.2",
          "name": "miniz_oxide",
          "version": "0.7.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.7.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.7.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ndk@0.8.0",
          "name": "ndk",
          "version": "0.8.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-0.8.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-0.8.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ndk-context@0.1.1",
          "name": "ndk-context",
          "version": "0.1.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-context-0.1.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-context-0.1.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ndk-sys@0.5.0+25.2.9519653",
          "name": "ndk-sys",
          "version": "0.5.0+25.2.9519653",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-sys-0.5.0+25.2.9519653\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ndk-sys-0.5.0+25.2.9519653"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#nix@0.26.4",
          "name": "nix",
          "version": "0.26.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\nix-0.26.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\nix-0.26.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
          "name": "num-traits",
          "version": "0.2.18",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.18\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num_enum@0.7.2",
          "name": "num_enum",
          "version": "0.7.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num_enum-0.7.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num_enum-0.7.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num_enum_derive@0.7.2",
          "name": "num_enum_derive",
          "version": "0.7.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num_enum_derive-0.7.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num_enum_derive-0.7.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc@0.2.7",
          "name": "objc",
          "version": "0.2.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc-0.2.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc-0.2.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc-sys@0.3.2",
          "name": "objc-sys",
          "version": "0.3.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc-sys-0.3.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc-sys-0.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc2@0.4.1",
          "name": "objc2",
          "version": "0.4.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc2-0.4.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc2-0.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#objc2-encode@3.0.0",
          "name": "objc2-encode",
          "version": "3.0.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc2-encode-3.0.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\objc2-encode-3.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.19.0",
          "name": "once_cell",
          "version": "1.19.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#orbclient@0.3.47",
          "name": "orbclient",
          "version": "0.3.47",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\orbclient-0.3.47\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\orbclient-0.3.47"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#owned_ttf_parser@0.20.0",
          "name": "owned_ttf_parser",
          "version": "0.20.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\owned_ttf_parser-0.20.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\owned_ttf_parser-0.20.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#percent-encoding@2.3.1",
          "name": "percent-encoding",
          "version": "2.3.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\percent-encoding-2.3.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\percent-encoding-2.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.13",
          "name": "pin-project-lite",
          "version": "0.2.13",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.13\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.13"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.29",
          "name": "pkg-config",
          "version": "0.3.29",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.29\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.29"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#png@0.17.11",
          "name": "png",
          "version": "0.17.11",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\png-0.17.11\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\png-0.17.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#polling@3.4.0",
          "name": "polling",
          "version": "3.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\polling-3.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\polling-3.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro-crate@1.3.1",
          "name": "proc-macro-crate",
          "version": "1.3.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro-crate-1.3.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro-crate-1.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.78",
          "name": "proc-macro2",
          "version": "1.0.78",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.78\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.78"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quick-xml@0.31.0",
          "name": "quick-xml",
          "version": "0.31.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quick-xml-0.31.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quick-xml-0.31.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.35",
          "name": "quote",
          "version": "1.0.35",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.35\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.35"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#raw-window-handle@0.5.2",
          "name": "raw-window-handle",
          "version": "0.5.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.5.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.5.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#raw-window-handle@0.6.0",
          "name": "raw-window-handle",
          "version": "0.6.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.3.5",
          "name": "redox_syscall",
          "version": "0.3.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.3.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.4.1",
          "name": "redox_syscall",
          "version": "0.4.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.4.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.31",
          "name": "rustix",
          "version": "0.38.31",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-0.38.31\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-0.38.31"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
          "name": "same-file",
          "version": "1.0.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#scoped-tls@1.0.1",
          "name": "scoped-tls",
          "version": "1.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scoped-tls-1.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scoped-tls-1.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#sctk-adwaita@0.8.1",
          "name": "sctk-adwaita",
          "version": "0.8.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\sctk-adwaita-0.8.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\sctk-adwaita-0.8.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.196",
          "name": "serde",
          "version": "1.0.196",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.196\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.196"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.196",
          "name": "serde_derive",
          "version": "1.0.196",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.196\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.196"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#simd-adler32@0.3.7",
          "name": "simd-adler32",
          "version": "0.3.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\simd-adler32-0.3.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\simd-adler32-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#simple_logger@4.3.3",
          "name": "simple_logger",
          "version": "4.3.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\simple_logger-4.3.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\simple_logger-4.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.9",
          "name": "slab",
          "version": "0.4.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#smallvec@1.13.1",
          "name": "smallvec",
          "version": "1.13.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.13.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.13.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#smithay-client-toolkit@0.18.0",
          "name": "smithay-client-toolkit",
          "version": "0.18.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smithay-client-toolkit-0.18.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smithay-client-toolkit-0.18.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#smol_str@0.2.1",
          "name": "smol_str",
          "version": "0.2.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#softbuffer@0.3.4",
          "name": "softbuffer",
          "version": "0.3.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\softbuffer-0.3.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\softbuffer-0.3.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#strict-num@0.1.1",
          "name": "strict-num",
          "version": "0.1.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\strict-num-0.1.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\strict-num-0.1.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.48",
          "name": "syn",
          "version": "2.0.48",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.48\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.48"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror@1.0.56",
          "name": "thiserror",
          "version": "1.0.56",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-1.0.56\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-1.0.56"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#thiserror-impl@1.0.56",
          "name": "thiserror-impl",
          "version": "1.0.56",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-1.0.56\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\thiserror-impl-1.0.56"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tiny-skia@0.11.4",
          "name": "tiny-skia",
          "version": "0.11.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-skia-0.11.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-skia-0.11.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tiny-skia-path@0.11.4",
          "name": "tiny-skia-path",
          "version": "0.11.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-skia-path-0.11.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-skia-path-0.11.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tiny-xlib@0.2.2",
          "name": "tiny-xlib",
          "version": "0.2.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-xlib-0.2.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tiny-xlib-0.2.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@0.6.5",
          "name": "toml_datetime",
          "version": "0.6.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_datetime-0.6.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_datetime-0.6.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_edit@0.19.15",
          "name": "toml_edit",
          "version": "0.19.15",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_edit-0.19.15\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\toml_edit-0.19.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tracing@0.1.40",
          "name": "tracing",
          "version": "0.1.40",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tracing-0.1.40\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tracing-0.1.40"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tracing-core@0.1.32",
          "name": "tracing-core",
          "version": "0.1.32",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tracing-core-0.1.32\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tracing-core-0.1.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ttf-parser@0.20.0",
          "name": "ttf-parser",
          "version": "0.20.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ttf-parser-0.20.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ttf-parser-0.20.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
          "name": "unicode-ident",
          "version": "1.0.12",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.12\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-segmentation@1.11.0",
          "name": "unicode-segmentation",
          "version": "1.11.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.4",
          "name": "version_check",
          "version": "0.9.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\version_check-0.9.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\version_check-0.9.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.4.0",
          "name": "walkdir",
          "version": "2.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
          "name": "wasi",
          "version": "0.11.0+wasi-snapshot-preview1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.11.0+wasi-snapshot-preview1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.11.0+wasi-snapshot-preview1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.91",
          "name": "wasm-bindgen",
          "version": "0.2.91",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.91\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.91"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.91",
          "name": "wasm-bindgen-backend",
          "version": "0.2.91",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-backend-0.2.91\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-backend-0.2.91"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-futures@0.4.41",
          "name": "wasm-bindgen-futures",
          "version": "0.4.41",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-futures-0.4.41\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-futures-0.4.41"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.91",
          "name": "wasm-bindgen-macro",
          "version": "0.2.91",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.91\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.91"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.91",
          "name": "wasm-bindgen-macro-support",
          "version": "0.2.91",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.91\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.91"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.91",
          "name": "wasm-bindgen-shared",
          "version": "0.2.91",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.91\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.91"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-backend@0.3.3",
          "name": "wayland-backend",
          "version": "0.3.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-backend-0.3.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-backend-0.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-client@0.31.2",
          "name": "wayland-client",
          "version": "0.31.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-client-0.31.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-client-0.31.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-csd-frame@0.3.0",
          "name": "wayland-csd-frame",
          "version": "0.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-csd-frame-0.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-csd-frame-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-cursor@0.31.1",
          "name": "wayland-cursor",
          "version": "0.31.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-cursor-0.31.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-cursor-0.31.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-protocols@0.31.2",
          "name": "wayland-protocols",
          "version": "0.31.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-0.31.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-0.31.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-protocols-plasma@0.2.0",
          "name": "wayland-protocols-plasma",
          "version": "0.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-plasma-0.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-plasma-0.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-protocols-wlr@0.2.0",
          "name": "wayland-protocols-wlr",
          "version": "0.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-wlr-0.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-protocols-wlr-0.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-scanner@0.31.1",
          "name": "wayland-scanner",
          "version": "0.31.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-scanner-0.31.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-scanner-0.31.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wayland-sys@0.31.1",
          "name": "wayland-sys",
          "version": "0.31.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-sys-0.31.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wayland-sys-0.31.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.68",
          "name": "web-sys",
          "version": "0.3.68",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.68\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.68"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-time@0.2.4",
          "name": "web-time",
          "version": "0.2.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-time-0.2.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-time-0.2.4"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-wsapoll@0.1.1",
          "name": "winapi-wsapoll",
          "version": "0.1.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-wsapoll-0.1.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-wsapoll-0.1.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
          "name": "winapi-x86_64-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.45.0",
          "name": "windows-sys",
          "version": "0.45.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.45.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.45.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.48.0",
          "name": "windows-sys",
          "version": "0.48.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.52.0",
          "name": "windows-sys",
          "version": "0.52.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.52.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.52.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.42.2",
          "name": "windows-targets",
          "version": "0.42.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.42.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.42.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.48.5",
          "name": "windows-targets",
          "version": "0.48.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.0",
          "name": "windows-targets",
          "version": "0.52.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.42.2",
          "name": "windows_aarch64_gnullvm",
          "version": "0.42.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.42.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.42.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.48.5",
          "name": "windows_aarch64_gnullvm",
          "version": "0.48.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.48.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.0",
          "name": "windows_aarch64_gnullvm",
          "version": "0.52.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.52.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.52.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.42.2",
          "name": "windows_aarch64_msvc",
          "version": "0.42.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.42.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.42.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.48.5",
          "name": "windows_aarch64_msvc",
          "version": "0.48.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.48.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.0",
          "name": "windows_aarch64_msvc",
          "version": "0.52.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.52.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.52.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.42.2",
          "name": "windows_i686_gnu",
          "version": "0.42.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.42.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.42.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.48.5",
          "name": "windows_i686_gnu",
          "version": "0.48.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.48.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.0",
          "name": "windows_i686_gnu",
          "version": "0.52.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.52.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.52.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.42.2",
          "name": "windows_i686_msvc",
          "version": "0.42.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.42.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.42.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.48.5",
          "name": "windows_i686_msvc",
          "version": "0.48.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.48.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.0",
          "name": "windows_i686_msvc",
          "version": "0.52.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.52.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.52.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.42.2",
          "name": "windows_x86_64_gnu",
          "version": "0.42.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.42.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.42.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.48.5",
          "name": "windows_x86_64_gnu",
          "version": "0.48.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.48.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.0",
          "name": "windows_x86_64_gnu",
          "version": "0.52.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.52.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.52.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.42.2",
          "name": "windows_x86_64_gnullvm",
          "version": "0.42.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.42.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.42.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.48.5",
          "name": "windows_x86_64_gnullvm",
          "version": "0.48.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.48.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.0",
          "name": "windows_x86_64_gnullvm",
          "version": "0.52.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.52.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.52.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.42.2",
          "name": "windows_x86_64_msvc",
          "version": "0.42.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.42.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.42.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
          "name": "windows_x86_64_msvc",
          "version": "0.48.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.0",
          "name": "windows_x86_64_msvc",
          "version": "0.52.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.0"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
          "name": "winit",
          "version": "0.29.15",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@0.5.39",
          "name": "winnow",
          "version": "0.5.39",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winnow-0.5.39\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winnow-0.5.39"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11-dl@2.21.0",
          "name": "x11-dl",
          "version": "2.21.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11-dl-2.21.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11-dl-2.21.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb@0.12.0",
          "name": "x11rb",
          "version": "0.12.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-0.12.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-0.12.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb@0.13.0",
          "name": "x11rb",
          "version": "0.13.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-0.13.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-0.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb-protocol@0.12.0",
          "name": "x11rb-protocol",
          "version": "0.12.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-protocol-0.12.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-protocol-0.12.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#x11rb-protocol@0.13.0",
          "name": "x11rb-protocol",
          "version": "0.13.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-protocol-0.13.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\x11rb-protocol-0.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#xcursor@0.3.5",
          "name": "xcursor",
          "version": "0.3.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xcursor-0.3.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xcursor-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#xkbcommon-dl@0.4.2",
          "name": "xkbcommon-dl",
          "version": "0.4.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xkbcommon-dl-0.4.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xkbcommon-dl-0.4.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#xkeysym@0.2.0",
          "name": "xkeysym",
          "version": "0.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xkeysym-0.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\xkeysym-0.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy@0.7.32",
          "name": "zerocopy",
          "version": "0.7.32",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-0.7.32\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-0.7.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy-derive@0.7.32",
          "name": "zerocopy-derive",
          "version": "0.7.32",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-derive-0.7.32\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-derive-0.7.32"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17348,
      "ppid": 6468,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:afba339e1afeea72:386a9de7aa2301cd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
      "pid": 17348,
      "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:72442d78d66b2f5c:386a9de7aa2301cd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
      "pid": 17348,
      "sha256": "59f62eb15f6d83ac62ef451179ce318623825939c8ba5b446fc2b514836f4d08",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:c0b293330aa97d47:386a9de7aa2301cd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
      "pid": 17348,
      "sha256": "f8422d6d05925df913081382846c65efd458d0db01b1770342457c42cbabede0",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:1ceda9c220daf075:386a9de7aa2301cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "kernel32.lib",
      "pid": 17348,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:1ceda9c220daf075:386a9de7aa2301cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "kernel32.lib",
      "pid": 17348,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:1ceda9c220daf075:386a9de7aa2301cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "kernel32.lib",
      "pid": 17348,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:1db9512c4d5c31e6:386a9de7aa2301cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "ntdll.lib",
      "pid": 17348,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:861f0814f9c52599:386a9de7aa2301cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "userenv.lib",
      "pid": 17348,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:50848825683fdca9:386a9de7aa2301cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "ws2_32.lib",
      "pid": 17348,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "used:link:6b43f26fd17962e1:df7d4e53c08047f7:386a9de7aa2301cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "path": "dbghelp.lib",
      "pid": 17348,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib"
      ],
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.48.5",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 17348,
      "ppid": 6468,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\rustcn32qeH\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.build_script_build.a737754ac1f6dcea-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.dc58ththy4wru6enw9v2xruap.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build_script_build-17383b75150b7180.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "directories": [
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000148       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000198       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001d0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000288       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002b8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000148       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000198       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-17348-1783961319258456300.map",
      "pid": 17348,
      "ppid": 6468,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-17348-1783961319258456300.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15912,
      "ppid": 3632,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "winit",
        "version": "0.29.15",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "winit",
        "version": "0.29.15",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "cargo_pkg_name": "winit",
      "cargo_pkg_version": "0.29.15",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 15912,
      "ppid": 3632,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "_owner": {
        "crate": "winit",
        "version": "0.29.15",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-19640-1783961312649\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\rustcA5u4w9\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000148       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000198       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001d0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002b8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000148       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140027148     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000198       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140027198     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400271b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400271d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400271e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400271f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140027288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400272a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400272b8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-15912-1783961319455906700.map",
      "pid": 15912,
      "ppid": 3632,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\.tmp\\native-trace-link-link-15912-1783961319455906700.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "winit",
        "version": "0.29.15",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15#winit@0.29.15",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "windows_x86_64_msvc",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "event_id": "bsrun:c40213baefe8fbb9:8f05b09d80a10b7e:f8fa522367f92fec",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15/target/debug/build/windows_x86_64_msvc-17383b75150b7180\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-dfbn_7qr/src/winit-0.29.15/target/debug/build/windows_x86_64_msvc-17383b75150b7180/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
      "success": true,
      "target": null,
      "version": "0.48.5",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "source": "cwd_prefix"
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
      "raw_event_count": 15175,
      "parsed_event_count": 15175,
      "parse_error_count": 0,
      "command_line_event_count": 15175,
      "build_script_root_event_count": 346,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 1350,
      "dropped_event_count": 7854
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16064,
      "ppid": 9664,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T16:48:39.460671+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180\\build-script-build.exe",
      "root_cargo_pid": 8280,
      "build_script_root_pid": 16064,
      "build_script_related": true,
      "build_script_target_dir": "windows_x86_64_msvc-17383b75150b7180"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 10856,
      "ppid": 9664,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T16:48:39.886119+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3\\build-script-build.exe",
      "root_cargo_pid": 8280,
      "build_script_root_pid": 10856,
      "build_script_related": true,
      "build_script_target_dir": "winit-717c5d300b98a4e3"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 20580,
      "ppid": 13052,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
      "time": "2026-07-13T16:48:32.881089+00:00",
      "end_time": "2026-07-13T16:48:32.900764+00:00",
      "start_unix_nanos": 1783961312881089500,
      "end_unix_nanos": 1783961312900763600,
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
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 3280,
      "ppid": 13052,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
      "time": "2026-07-13T16:48:32.907386+00:00",
      "end_time": "2026-07-13T16:48:32.927854+00:00",
      "start_unix_nanos": 1783961312907385600,
      "end_unix_nanos": 1783961312927854300,
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
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 17556,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
      "time": "2026-07-13T16:48:38.956205+00:00",
      "end_time": "2026-07-13T16:48:38.975552+00:00",
      "start_unix_nanos": 1783961318956205100,
      "end_unix_nanos": 1783961318975552000,
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
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 21252,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
      "time": "2026-07-13T16:48:38.983271+00:00",
      "end_time": "2026-07-13T16:48:39.007308+00:00",
      "start_unix_nanos": 1783961318983270700,
      "end_unix_nanos": 1783961319007308000,
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
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 7300,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
      "time": "2026-07-13T16:48:39.057383+00:00",
      "end_time": "2026-07-13T16:48:39.076129+00:00",
      "start_unix_nanos": 1783961319057382500,
      "end_unix_nanos": 1783961319076128700,
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
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 15704,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\build.rs",
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
        "metadata=6db132d4d00a965f",
        "-C",
        "extra-filename=-17383b75150b7180",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=6db132d4d00a965f -C extra-filename=-17383b75150b7180 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\build.rs",
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
        "metadata=6db132d4d00a965f",
        "-C",
        "extra-filename=-17383b75150b7180",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.105130+00:00",
      "end_time": "2026-07-13T16:48:39.367442+00:00",
      "start_unix_nanos": 1783961319105129900,
      "end_unix_nanos": 1783961319367442100,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\windows_x86_64_msvc-17383b75150b7180"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 9192,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cfg_aliases",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1\\src\\lib.rs",
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
        "metadata=71aaad46bdefbb7a",
        "-C",
        "extra-filename=-58fc099ce75d46bd",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cfg_aliases --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=71aaad46bdefbb7a -C extra-filename=-58fc099ce75d46bd --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cfg_aliases",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg_aliases-0.1.1\\src\\lib.rs",
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
        "metadata=71aaad46bdefbb7a",
        "-C",
        "extra-filename=-58fc099ce75d46bd",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.108201+00:00",
      "end_time": "2026-07-13T16:48:39.173235+00:00",
      "start_unix_nanos": 1783961319108200500,
      "end_unix_nanos": 1783961319173235200,
      "crate_name": "cfg_aliases",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 836,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cursor_icon",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0\\src\\lib.rs",
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
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"serde\", \"std\"))",
        "-C",
        "metadata=d31e111c2d3a29f0",
        "-C",
        "extra-filename=-7064bb38659984d2",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cursor_icon --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=d31e111c2d3a29f0 -C extra-filename=-7064bb38659984d2 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cursor_icon",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cursor-icon-1.1.0\\src\\lib.rs",
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
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"serde\", \"std\"))",
        "-C",
        "metadata=d31e111c2d3a29f0",
        "-C",
        "extra-filename=-7064bb38659984d2",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.110804+00:00",
      "end_time": "2026-07-13T16:48:39.210739+00:00",
      "start_unix_nanos": 1783961319110803600,
      "end_unix_nanos": 1783961319210739200,
      "crate_name": "cursor_icon",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 18996,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "unicode_segmentation",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0\\src\\lib.rs",
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
        "cfg(feature, values(\"no_std\"))",
        "-C",
        "metadata=7a34b5f1be54d454",
        "-C",
        "extra-filename=-82c365516f112666",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name unicode_segmentation --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"no_std\\\"))\" -C metadata=7a34b5f1be54d454 -C extra-filename=-82c365516f112666 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "unicode_segmentation",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-segmentation-1.11.0\\src\\lib.rs",
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
        "cfg(feature, values(\"no_std\"))",
        "-C",
        "metadata=7a34b5f1be54d454",
        "-C",
        "extra-filename=-82c365516f112666",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.113660+00:00",
      "end_time": "2026-07-13T16:48:39.453711+00:00",
      "start_unix_nanos": 1783961319113659900,
      "end_unix_nanos": 1783961319453710700,
      "crate_name": "unicode_segmentation",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 5428,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "bitflags",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2\\src\\lib.rs",
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
        "cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std\"))",
        "-C",
        "metadata=9c7ce8c554b06bba",
        "-C",
        "extra-filename=-0667b619dfc545b1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name bitflags --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"bytemuck\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"example_generated\\\", \\\"rustc-dep-of-std\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=9c7ce8c554b06bba -C extra-filename=-0667b619dfc545b1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "bitflags",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.4.2\\src\\lib.rs",
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
        "cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std\"))",
        "-C",
        "metadata=9c7ce8c554b06bba",
        "-C",
        "extra-filename=-0667b619dfc545b1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.116404+00:00",
      "end_time": "2026-07-13T16:48:39.284625+00:00",
      "start_unix_nanos": 1783961319116404300,
      "end_unix_nanos": 1783961319284624500,
      "crate_name": "bitflags",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 16244,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "once_cell",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0\\src\\lib.rs",
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
        "cfg(feature, values(\"alloc\", \"atomic-polyfill\", \"critical-section\", \"default\", \"parking_lot\", \"portable-atomic\", \"race\", \"std\", \"unstable\"))",
        "-C",
        "metadata=b67124b64dad4f71",
        "-C",
        "extra-filename=-d076018eae555cad",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name once_cell --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"race\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"atomic-polyfill\\\", \\\"critical-section\\\", \\\"default\\\", \\\"parking_lot\\\", \\\"portable-atomic\\\", \\\"race\\\", \\\"std\\\", \\\"unstable\\\"))\" -C metadata=b67124b64dad4f71 -C extra-filename=-d076018eae555cad --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "once_cell",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.19.0\\src\\lib.rs",
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
        "cfg(feature, values(\"alloc\", \"atomic-polyfill\", \"critical-section\", \"default\", \"parking_lot\", \"portable-atomic\", \"race\", \"std\", \"unstable\"))",
        "-C",
        "metadata=b67124b64dad4f71",
        "-C",
        "extra-filename=-d076018eae555cad",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.119662+00:00",
      "end_time": "2026-07-13T16:48:39.275128+00:00",
      "start_unix_nanos": 1783961319119662400,
      "end_unix_nanos": 1783961319275127700,
      "crate_name": "once_cell",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 16100,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "log",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20\\src\\lib.rs",
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
        "cfg(feature, values(\"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_error\", \"max_level_info\", \"max_level_off\", \"max_level_trace\", \"max_level_warn\", \"release_max_level_debug\", \"release_max_level_error\", \"release_max_level_info\", \"release_max_level_off\", \"release_max_level_trace\", \"release_max_level_warn\", \"serde\", \"std\", \"sval\", \"sval_ref\", \"value-bag\"))",
        "-C",
        "metadata=b7e189e74a236304",
        "-C",
        "extra-filename=-c49eeec8812cf892",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name log --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"kv_unstable\\\", \\\"kv_unstable_serde\\\", \\\"kv_unstable_std\\\", \\\"kv_unstable_sval\\\", \\\"max_level_debug\\\", \\\"max_level_error\\\", \\\"max_level_info\\\", \\\"max_level_off\\\", \\\"max_level_trace\\\", \\\"max_level_warn\\\", \\\"release_max_level_debug\\\", \\\"release_max_level_error\\\", \\\"release_max_level_info\\\", \\\"release_max_level_off\\\", \\\"release_max_level_trace\\\", \\\"release_max_level_warn\\\", \\\"serde\\\", \\\"std\\\", \\\"sval\\\", \\\"sval_ref\\\", \\\"value-bag\\\"))\" -C metadata=b7e189e74a236304 -C extra-filename=-c49eeec8812cf892 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "log",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.20\\src\\lib.rs",
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
        "cfg(feature, values(\"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_error\", \"max_level_info\", \"max_level_off\", \"max_level_trace\", \"max_level_warn\", \"release_max_level_debug\", \"release_max_level_error\", \"release_max_level_info\", \"release_max_level_off\", \"release_max_level_trace\", \"release_max_level_warn\", \"serde\", \"std\", \"sval\", \"sval_ref\", \"value-bag\"))",
        "-C",
        "metadata=b7e189e74a236304",
        "-C",
        "extra-filename=-c49eeec8812cf892",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.122745+00:00",
      "end_time": "2026-07-13T16:48:39.278522+00:00",
      "start_unix_nanos": 1783961319122744500,
      "end_unix_nanos": 1783961319278522400,
      "crate_name": "log",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 20548,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "raw_window_handle",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0\\src\\lib.rs",
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
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"std\", \"wasm-bindgen\", \"wasm-bindgen-0-2\"))",
        "-C",
        "metadata=fb00f7ee4ae98682",
        "-C",
        "extra-filename=-8084b02d24173edc",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name raw_window_handle --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"std\\\", \\\"wasm-bindgen\\\", \\\"wasm-bindgen-0-2\\\"))\" -C metadata=fb00f7ee4ae98682 -C extra-filename=-8084b02d24173edc --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "raw_window_handle",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\raw-window-handle-0.6.0\\src\\lib.rs",
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
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"std\", \"wasm-bindgen\", \"wasm-bindgen-0-2\"))",
        "-C",
        "metadata=fb00f7ee4ae98682",
        "-C",
        "extra-filename=-8084b02d24173edc",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.125971+00:00",
      "end_time": "2026-07-13T16:48:39.303971+00:00",
      "start_unix_nanos": 1783961319125971300,
      "end_unix_nanos": 1783961319303971100,
      "crate_name": "raw_window_handle",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 18908,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "smol_str",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1\\src\\lib.rs",
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
        "cfg(feature, values(\"arbitrary\", \"default\", \"serde\", \"std\"))",
        "-C",
        "metadata=643fc940d43059b7",
        "-C",
        "extra-filename=-a58cc8446871329b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name smol_str --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"default\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=643fc940d43059b7 -C extra-filename=-a58cc8446871329b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "smol_str",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smol_str-0.2.1\\src\\lib.rs",
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
        "cfg(feature, values(\"arbitrary\", \"default\", \"serde\", \"std\"))",
        "-C",
        "metadata=643fc940d43059b7",
        "-C",
        "extra-filename=-a58cc8446871329b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.129431+00:00",
      "end_time": "2026-07-13T16:48:39.310435+00:00",
      "start_unix_nanos": 1783961319129430500,
      "end_unix_nanos": 1783961319310435200,
      "crate_name": "smol_str",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 12620,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
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
        "feature=\"ahash\"",
        "--cfg",
        "feature=\"bytemuck\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"memmap2\"",
        "--cfg",
        "feature=\"percent-encoding\"",
        "--cfg",
        "feature=\"rwh_06\"",
        "--cfg",
        "feature=\"sctk\"",
        "--cfg",
        "feature=\"sctk-adwaita\"",
        "--cfg",
        "feature=\"wayland\"",
        "--cfg",
        "feature=\"wayland-backend\"",
        "--cfg",
        "feature=\"wayland-client\"",
        "--cfg",
        "feature=\"wayland-csd-adwaita\"",
        "--cfg",
        "feature=\"wayland-dlopen\"",
        "--cfg",
        "feature=\"wayland-protocols\"",
        "--cfg",
        "feature=\"wayland-protocols-plasma\"",
        "--cfg",
        "feature=\"x11\"",
        "--cfg",
        "feature=\"x11-dl\"",
        "--cfg",
        "feature=\"x11rb\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"ahash\", \"android-game-activity\", \"android-native-activity\", \"bytemuck\", \"default\", \"memmap2\", \"mint\", \"percent-encoding\", \"rwh_04\", \"rwh_05\", \"rwh_06\", \"sctk\", \"sctk-adwaita\", \"serde\", \"wayland\", \"wayland-backend\", \"wayland-client\", \"wayland-csd-adwaita\", \"wayland-csd-adwaita-crossfont\", \"wayland-csd-adwaita-notitle\", \"wayland-dlopen\", \"wayland-protocols\", \"wayland-protocols-plasma\", \"x11\", \"x11-dl\", \"x11rb\"))",
        "-C",
        "metadata=c8a5096ab5ff811a",
        "-C",
        "extra-filename=-717c5d300b98a4e3",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--extern",
        "cfg_aliases=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcfg_aliases-58fc099ce75d46bd.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"ahash\\\"\" --cfg \"feature=\\\"bytemuck\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"memmap2\\\"\" --cfg \"feature=\\\"percent-encoding\\\"\" --cfg \"feature=\\\"rwh_06\\\"\" --cfg \"feature=\\\"sctk\\\"\" --cfg \"feature=\\\"sctk-adwaita\\\"\" --cfg \"feature=\\\"wayland\\\"\" --cfg \"feature=\\\"wayland-backend\\\"\" --cfg \"feature=\\\"wayland-client\\\"\" --cfg \"feature=\\\"wayland-csd-adwaita\\\"\" --cfg \"feature=\\\"wayland-dlopen\\\"\" --cfg \"feature=\\\"wayland-protocols\\\"\" --cfg \"feature=\\\"wayland-protocols-plasma\\\"\" --cfg \"feature=\\\"x11\\\"\" --cfg \"feature=\\\"x11-dl\\\"\" --cfg \"feature=\\\"x11rb\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"ahash\\\", \\\"android-game-activity\\\", \\\"android-native-activity\\\", \\\"bytemuck\\\", \\\"default\\\", \\\"memmap2\\\", \\\"mint\\\", \\\"percent-encoding\\\", \\\"rwh_04\\\", \\\"rwh_05\\\", \\\"rwh_06\\\", \\\"sctk\\\", \\\"sctk-adwaita\\\", \\\"serde\\\", \\\"wayland\\\", \\\"wayland-backend\\\", \\\"wayland-client\\\", \\\"wayland-csd-adwaita\\\", \\\"wayland-csd-adwaita-crossfont\\\", \\\"wayland-csd-adwaita-notitle\\\", \\\"wayland-dlopen\\\", \\\"wayland-protocols\\\", \\\"wayland-protocols-plasma\\\", \\\"x11\\\", \\\"x11-dl\\\", \\\"x11rb\\\"))\" -C metadata=c8a5096ab5ff811a -C extra-filename=-717c5d300b98a4e3 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --extern cfg_aliases=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcfg_aliases-58fc099ce75d46bd.rlib",
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
        "feature=\"ahash\"",
        "--cfg",
        "feature=\"bytemuck\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"memmap2\"",
        "--cfg",
        "feature=\"percent-encoding\"",
        "--cfg",
        "feature=\"rwh_06\"",
        "--cfg",
        "feature=\"sctk\"",
        "--cfg",
        "feature=\"sctk-adwaita\"",
        "--cfg",
        "feature=\"wayland\"",
        "--cfg",
        "feature=\"wayland-backend\"",
        "--cfg",
        "feature=\"wayland-client\"",
        "--cfg",
        "feature=\"wayland-csd-adwaita\"",
        "--cfg",
        "feature=\"wayland-dlopen\"",
        "--cfg",
        "feature=\"wayland-protocols\"",
        "--cfg",
        "feature=\"wayland-protocols-plasma\"",
        "--cfg",
        "feature=\"x11\"",
        "--cfg",
        "feature=\"x11-dl\"",
        "--cfg",
        "feature=\"x11rb\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"ahash\", \"android-game-activity\", \"android-native-activity\", \"bytemuck\", \"default\", \"memmap2\", \"mint\", \"percent-encoding\", \"rwh_04\", \"rwh_05\", \"rwh_06\", \"sctk\", \"sctk-adwaita\", \"serde\", \"wayland\", \"wayland-backend\", \"wayland-client\", \"wayland-csd-adwaita\", \"wayland-csd-adwaita-crossfont\", \"wayland-csd-adwaita-notitle\", \"wayland-dlopen\", \"wayland-protocols\", \"wayland-protocols-plasma\", \"x11\", \"x11-dl\", \"x11rb\"))",
        "-C",
        "metadata=c8a5096ab5ff811a",
        "-C",
        "extra-filename=-717c5d300b98a4e3",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--extern",
        "cfg_aliases=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcfg_aliases-58fc099ce75d46bd.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.218183+00:00",
      "end_time": "2026-07-13T16:48:39.802593+00:00",
      "start_unix_nanos": 1783961319218183300,
      "end_unix_nanos": 1783961319802593200,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\build\\winit-717c5d300b98a4e3"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 15924,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_x86_64_msvc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\src\\lib.rs",
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
        "metadata=ec5e69bf4147ead9",
        "-C",
        "extra-filename=-90661bad6bd70640",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_x86_64_msvc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=ec5e69bf4147ead9 -C extra-filename=-90661bad6bd70640 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_x86_64_msvc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\src\\lib.rs",
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
        "metadata=ec5e69bf4147ead9",
        "-C",
        "extra-filename=-90661bad6bd70640",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.478541+00:00",
      "end_time": "2026-07-13T16:48:39.528642+00:00",
      "start_unix_nanos": 1783961319478540600,
      "end_unix_nanos": 1783961319528642500,
      "crate_name": "windows_x86_64_msvc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 14980,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_targets",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5\\src\\lib.rs",
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
        "metadata=3179a779a073e2bf",
        "-C",
        "extra-filename=-cf26163e4cd2c220",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--extern",
        "windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_x86_64_msvc-90661bad6bd70640.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_targets --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=3179a779a073e2bf -C extra-filename=-cf26163e4cd2c220 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --extern windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_x86_64_msvc-90661bad6bd70640.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_targets",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.48.5\\src\\lib.rs",
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
        "metadata=3179a779a073e2bf",
        "-C",
        "extra-filename=-cf26163e4cd2c220",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--extern",
        "windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_x86_64_msvc-90661bad6bd70640.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.510060+00:00",
      "end_time": "2026-07-13T16:48:39.559257+00:00",
      "start_unix_nanos": 1783961319510060300,
      "end_unix_nanos": 1783961319559256900,
      "crate_name": "windows_targets",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 19008,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_sys",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0\\src\\lib.rs",
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
        "feature=\"Win32\"",
        "--cfg",
        "feature=\"Win32_Devices\"",
        "--cfg",
        "feature=\"Win32_Devices_HumanInterfaceDevice\"",
        "--cfg",
        "feature=\"Win32_Foundation\"",
        "--cfg",
        "feature=\"Win32_Globalization\"",
        "--cfg",
        "feature=\"Win32_Graphics\"",
        "--cfg",
        "feature=\"Win32_Graphics_Dwm\"",
        "--cfg",
        "feature=\"Win32_Graphics_Gdi\"",
        "--cfg",
        "feature=\"Win32_Media\"",
        "--cfg",
        "feature=\"Win32_System\"",
        "--cfg",
        "feature=\"Win32_System_Com\"",
        "--cfg",
        "feature=\"Win32_System_Com_StructuredStorage\"",
        "--cfg",
        "feature=\"Win32_System_LibraryLoader\"",
        "--cfg",
        "feature=\"Win32_System_Ole\"",
        "--cfg",
        "feature=\"Win32_System_SystemInformation\"",
        "--cfg",
        "feature=\"Win32_System_SystemServices\"",
        "--cfg",
        "feature=\"Win32_System_Threading\"",
        "--cfg",
        "feature=\"Win32_System_WindowsProgramming\"",
        "--cfg",
        "feature=\"Win32_UI\"",
        "--cfg",
        "feature=\"Win32_UI_Accessibility\"",
        "--cfg",
        "feature=\"Win32_UI_Controls\"",
        "--cfg",
        "feature=\"Win32_UI_HiDpi\"",
        "--cfg",
        "feature=\"Win32_UI_Input\"",
        "--cfg",
        "feature=\"Win32_UI_Input_Ime\"",
        "--cfg",
        "feature=\"Win32_UI_Input_KeyboardAndMouse\"",
        "--cfg",
        "feature=\"Win32_UI_Input_Pointer\"",
        "--cfg",
        "feature=\"Win32_UI_Input_Touch\"",
        "--cfg",
        "feature=\"Win32_UI_Shell\"",
        "--cfg",
        "feature=\"Win32_UI_TextServices\"",
        "--cfg",
        "feature=\"Win32_UI_WindowsAndMessaging\"",
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"Wdk\", \"Wdk_System\", \"Wdk_System_OfflineRegistry\", \"Win32\", \"Win32_Data\", \"Win32_Data_HtmlHelp\", \"Win32_Data_RightsManagement\", \"Win32_Data_Xml\", \"Win32_Data_Xml_MsXml\", \"Win32_Data_Xml_XmlLite\", \"Win32_Devices\", \"Win32_Devices_AllJoyn\", \"Win32_Devices_BiometricFramework\", \"Win32_Devices_Bluetooth\", \"Win32_Devices_Communication\", \"Win32_Devices_DeviceAccess\", \"Win32_Devices_DeviceAndDriverInstallation\", \"Win32_Devices_DeviceQuery\", \"Win32_Devices_Display\", \"Win32_Devices_Enumeration\", \"Win32_Devices_Enumeration_Pnp\", \"Win32_Devices_Fax\", \"Win32_Devices_FunctionDiscovery\", \"Win32_Devices_Geolocation\", \"Win32_Devices_HumanInterfaceDevice\", \"Win32_Devices_ImageAcquisition\", \"Win32_Devices_PortableDevices\", \"Win32_Devices_Properties\", \"Win32_Devices_Pwm\", \"Win32_Devices_Sensors\", \"Win32_Devices_SerialCommunication\", \"Win32_Devices_Tapi\", \"Win32_Devices_Usb\", \"Win32_Devices_WebServicesOnDevices\", \"Win32_Foundation\", \"Win32_Gaming\", \"Win32_Globalization\", \"Win32_Graphics\", \"Win32_Graphics_Dwm\", \"Win32_Graphics_Gdi\", \"Win32_Graphics_Hlsl\", \"Win32_Graphics_OpenGL\", \"Win32_Graphics_Printing\", \"Win32_Graphics_Printing_PrintTicket\", \"Win32_Management\", \"Win32_Management_MobileDeviceManagementRegistration\", \"Win32_Media\", \"Win32_Media_Audio\", \"Win32_Media_Audio_Apo\", \"Win32_Media_Audio_DirectMusic\", \"Win32_Media_Audio_Endpoints\", \"Win32_Media_Audio_XAudio2\", \"Win32_Media_DeviceManager\", \"Win32_Media_DxMediaObjects\", \"Win32_Media_KernelStreaming\", \"Win32_Media_LibrarySharingServices\", \"Win32_Media_MediaPlayer\", \"Win32_Media_Multimedia\", \"Win32_Media_Speech\", \"Win32_Media_Streaming\", \"Win32_Media_WindowsMediaFormat\", \"Win32_NetworkManagement\", \"Win32_NetworkManagement_Dhcp\", \"Win32_NetworkManagement_Dns\", \"Win32_NetworkManagement_InternetConnectionWizard\", \"Win32_NetworkManagement_IpHelper\", \"Win32_NetworkManagement_MobileBroadband\", \"Win32_NetworkManagement_Multicast\", \"Win32_NetworkManagement_Ndis\", \"Win32_NetworkManagement_NetBios\", \"Win32_NetworkManagement_NetManagement\", \"Win32_NetworkManagement_NetShell\", \"Win32_NetworkManagement_NetworkDiagnosticsFramework\", \"Win32_NetworkManagement_NetworkPolicyServer\", \"Win32_NetworkManagement_P2P\", \"Win32_NetworkManagement_QoS\", \"Win32_NetworkManagement_Rras\", \"Win32_NetworkManagement_Snmp\", \"Win32_NetworkManagement_WNet\", \"Win32_NetworkManagement_WebDav\", \"Win32_NetworkManagement_WiFi\", \"Win32_NetworkManagement_WindowsConnectNow\", \"Win32_NetworkManagement_WindowsConnectionManager\", \"Win32_NetworkManagement_WindowsFilteringPlatform\", \"Win32_NetworkManagement_WindowsFirewall\", \"Win32_NetworkManagement_WindowsNetworkVirtualization\", \"Win32_Networking\", \"Win32_Networking_ActiveDirectory\", \"Win32_Networking_BackgroundIntelligentTransferService\", \"Win32_Networking_Clustering\", \"Win32_Networking_HttpServer\", \"Win32_Networking_Ldap\", \"Win32_Networking_NetworkListManager\", \"Win32_Networking_RemoteDifferentialCompression\", \"Win32_Networking_WebSocket\", \"Win32_Networking_WinHttp\", \"Win32_Networking_WinInet\", \"Win32_Networking_WinSock\", \"Win32_Networking_WindowsWebServices\", \"Win32_Security\", \"Win32_Security_AppLocker\", \"Win32_Security_Authentication\", \"Win32_Security_Authentication_Identity\", \"Win32_Security_Authentication_Identity_Provider\", \"Win32_Security_Authorization\", \"Win32_Security_Authorization_UI\", \"Win32_Security_ConfigurationSnapin\", \"Win32_Security_Credentials\", \"Win32_Security_Cryptography\", \"Win32_Security_Cryptography_Catalog\", \"Win32_Security_Cryptography_Certificates\", \"Win32_Security_Cryptography_Sip\", \"Win32_Security_Cryptography_UI\", \"Win32_Security_DiagnosticDataQuery\", \"Win32_Security_DirectoryServices\", \"Win32_Security_EnterpriseData\", \"Win32_Security_ExtensibleAuthenticationProtocol\", \"Win32_Security_Isolation\", \"Win32_Security_LicenseProtection\", \"Win32_Security_NetworkAccessProtection\", \"Win32_Security_Tpm\", \"Win32_Security_WinTrust\", \"Win32_Security_WinWlx\", \"Win32_Storage\", \"Win32_Storage_Cabinets\", \"Win32_Storage_CloudFilters\", \"Win32_Storage_Compression\", \"Win32_Storage_DataDeduplication\", \"Win32_Storage_DistributedFileSystem\", \"Win32_Storage_EnhancedStorage\", \"Win32_Storage_FileHistory\", \"Win32_Storage_FileServerResourceManager\", \"Win32_Storage_FileSystem\", \"Win32_Storage_Imapi\", \"Win32_Storage_IndexServer\", \"Win32_Storage_InstallableFileSystems\", \"Win32_Storage_IscsiDisc\", \"Win32_Storage_Jet\", \"Win32_Storage_OfflineFiles\", \"Win32_Storage_OperationRecorder\", \"Win32_Storage_Packaging\", \"Win32_Storage_Packaging_Appx\", \"Win32_Storage_Packaging_Opc\", \"Win32_Storage_ProjectedFileSystem\", \"Win32_Storage_StructuredStorage\", \"Win32_Storage_Vhd\", \"Win32_Storage_VirtualDiskService\", \"Win32_Storage_Vss\", \"Win32_Storage_Xps\", \"Win32_Storage_Xps_Printing\", \"Win32_System\", \"Win32_System_AddressBook\", \"Win32_System_Antimalware\", \"Win32_System_ApplicationInstallationAndServicing\", \"Win32_System_ApplicationVerifier\", \"Win32_System_AssessmentTool\", \"Win32_System_ClrHosting\", \"Win32_System_Com\", \"Win32_System_Com_CallObj\", \"Win32_System_Com_ChannelCredentials\", \"Win32_System_Com_Events\", \"Win32_System_Com_Marshal\", \"Win32_System_Com_StructuredStorage\", \"Win32_System_Com_UI\", \"Win32_System_Com_Urlmon\", \"Win32_System_ComponentServices\", \"Win32_System_Console\", \"Win32_System_Contacts\", \"Win32_System_CorrelationVector\", \"Win32_System_DataExchange\", \"Win32_System_DeploymentServices\", \"Win32_System_DesktopSharing\", \"Win32_System_DeveloperLicensing\", \"Win32_System_Diagnostics\", \"Win32_System_Diagnostics_Ceip\", \"Win32_System_Diagnostics_ClrProfiling\", \"Win32_System_Diagnostics_Debug\", \"Win32_System_Diagnostics_Debug_ActiveScript\", \"Win32_System_Diagnostics_Debug_Extensions\", \"Win32_System_Diagnostics_Etw\", \"Win32_System_Diagnostics_ProcessSnapshotting\", \"Win32_System_Diagnostics_ToolHelp\", \"Win32_System_DistributedTransactionCoordinator\", \"Win32_System_Environment\", \"Win32_System_ErrorReporting\", \"Win32_System_EventCollector\", \"Win32_System_EventLog\", \"Win32_System_EventNotificationService\", \"Win32_System_GroupPolicy\", \"Win32_System_HostCompute\", \"Win32_System_HostComputeNetwork\", \"Win32_System_HostComputeSystem\", \"Win32_System_Hypervisor\", \"Win32_System_IO\", \"Win32_System_Iis\", \"Win32_System_Ioctl\", \"Win32_System_JobObjects\", \"Win32_System_Js\", \"Win32_System_Kernel\", \"Win32_System_LibraryLoader\", \"Win32_System_Mailslots\", \"Win32_System_Mapi\", \"Win32_System_Memory\", \"Win32_System_Memory_NonVolatile\", \"Win32_System_MessageQueuing\", \"Win32_System_MixedReality\", \"Win32_System_Mmc\", \"Win32_System_Ole\", \"Win32_System_ParentalControls\", \"Win32_System_PasswordManagement\", \"Win32_System_Performance\", \"Win32_System_Performance_HardwareCounterProfiling\", \"Win32_System_Pipes\", \"Win32_System_Power\", \"Win32_System_ProcessStatus\", \"Win32_System_RealTimeCommunications\", \"Win32_System_Recovery\", \"Win32_System_Registry\", \"Win32_System_RemoteAssistance\", \"Win32_System_RemoteDesktop\", \"Win32_System_RemoteManagement\", \"Win32_System_RestartManager\", \"Win32_System_Restore\", \"Win32_System_Rpc\", \"Win32_System_Search\", \"Win32_System_Search_Common\", \"Win32_System_SecurityCenter\", \"Win32_System_ServerBackup\", \"Win32_System_Services\", \"Win32_System_SettingsManagementInfrastructure\", \"Win32_System_SetupAndMigration\", \"Win32_System_Shutdown\", \"Win32_System_StationsAndDesktops\", \"Win32_System_SubsystemForLinux\", \"Win32_System_SystemInformation\", \"Win32_System_SystemServices\", \"Win32_System_TaskScheduler\", \"Win32_System_Threading\", \"Win32_System_Time\", \"Win32_System_TpmBaseServices\", \"Win32_System_UpdateAgent\", \"Win32_System_UpdateAssessment\", \"Win32_System_UserAccessLogging\", \"Win32_System_VirtualDosMachines\", \"Win32_System_WindowsProgramming\", \"Win32_System_WindowsSync\", \"Win32_System_Wmi\", \"Win32_UI\", \"Win32_UI_Accessibility\", \"Win32_UI_Animation\", \"Win32_UI_ColorSystem\", \"Win32_UI_Controls\", \"Win32_UI_Controls_Dialogs\", \"Win32_UI_Controls_RichEdit\", \"Win32_UI_HiDpi\", \"Win32_UI_Input\", \"Win32_UI_Input_Ime\", \"Win32_UI_Input_Ink\", \"Win32_UI_Input_KeyboardAndMouse\", \"Win32_UI_Input_Pointer\", \"Win32_UI_Input_Radial\", \"Win32_UI_Input_Touch\", \"Win32_UI_Input_XboxController\", \"Win32_UI_InteractionContext\", \"Win32_UI_LegacyWindowsEnvironmentFeatures\", \"Win32_UI_Magnification\", \"Win32_UI_Notifications\", \"Win32_UI_Ribbon\", \"Win32_UI_Shell\", \"Win32_UI_Shell_Common\", \"Win32_UI_Shell_PropertiesSystem\", \"Win32_UI_TabletPC\", \"Win32_UI_TextServices\", \"Win32_UI_WindowsAndMessaging\", \"Win32_UI_Wpf\", \"Win32_Web\", \"Win32_Web_InternetExplorer\", \"default\"))",
        "-C",
        "metadata=b5b51020364d6d0c",
        "-C",
        "extra-filename=-80bdfb6f4e0c903e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--extern",
        "windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_targets-cf26163e4cd2c220.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_sys --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"Win32\\\"\" --cfg \"feature=\\\"Win32_Devices\\\"\" --cfg \"feature=\\\"Win32_Devices_HumanInterfaceDevice\\\"\" --cfg \"feature=\\\"Win32_Foundation\\\"\" --cfg \"feature=\\\"Win32_Globalization\\\"\" --cfg \"feature=\\\"Win32_Graphics\\\"\" --cfg \"feature=\\\"Win32_Graphics_Dwm\\\"\" --cfg \"feature=\\\"Win32_Graphics_Gdi\\\"\" --cfg \"feature=\\\"Win32_Media\\\"\" --cfg \"feature=\\\"Win32_System\\\"\" --cfg \"feature=\\\"Win32_System_Com\\\"\" --cfg \"feature=\\\"Win32_System_Com_StructuredStorage\\\"\" --cfg \"feature=\\\"Win32_System_LibraryLoader\\\"\" --cfg \"feature=\\\"Win32_System_Ole\\\"\" --cfg \"feature=\\\"Win32_System_SystemInformation\\\"\" --cfg \"feature=\\\"Win32_System_SystemServices\\\"\" --cfg \"feature=\\\"Win32_System_Threading\\\"\" --cfg \"feature=\\\"Win32_System_WindowsProgramming\\\"\" --cfg \"feature=\\\"Win32_UI\\\"\" --cfg \"feature=\\\"Win32_UI_Accessibility\\\"\" --cfg \"feature=\\\"Win32_UI_Controls\\\"\" --cfg \"feature=\\\"Win32_UI_HiDpi\\\"\" --cfg \"feature=\\\"Win32_UI_Input\\\"\" --cfg \"feature=\\\"Win32_UI_Input_Ime\\\"\" --cfg \"feature=\\\"Win32_UI_Input_KeyboardAndMouse\\\"\" --cfg \"feature=\\\"Win32_UI_Input_Pointer\\\"\" --cfg \"feature=\\\"Win32_UI_Input_Touch\\\"\" --cfg \"feature=\\\"Win32_UI_Shell\\\"\" --cfg \"feature=\\\"Win32_UI_TextServices\\\"\" --cfg \"feature=\\\"Win32_UI_WindowsAndMessaging\\\"\" --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"Wdk\\\", \\\"Wdk_System\\\", \\\"Wdk_System_OfflineRegistry\\\", \\\"Win32\\\", \\\"Win32_Data\\\", \\\"Win32_Data_HtmlHelp\\\", \\\"Win32_Data_RightsManagement\\\", \\\"Win32_Data_Xml\\\", \\\"Win32_Data_Xml_MsXml\\\", \\\"Win32_Data_Xml_XmlLite\\\", \\\"Win32_Devices\\\", \\\"Win32_Devices_AllJoyn\\\", \\\"Win32_Devices_BiometricFramework\\\", \\\"Win32_Devices_Bluetooth\\\", \\\"Win32_Devices_Communication\\\", \\\"Win32_Devices_DeviceAccess\\\", \\\"Win32_Devices_DeviceAndDriverInstallation\\\", \\\"Win32_Devices_DeviceQuery\\\", \\\"Win32_Devices_Display\\\", \\\"Win32_Devices_Enumeration\\\", \\\"Win32_Devices_Enumeration_Pnp\\\", \\\"Win32_Devices_Fax\\\", \\\"Win32_Devices_FunctionDiscovery\\\", \\\"Win32_Devices_Geolocation\\\", \\\"Win32_Devices_HumanInterfaceDevice\\\", \\\"Win32_Devices_ImageAcquisition\\\", \\\"Win32_Devices_PortableDevices\\\", \\\"Win32_Devices_Properties\\\", \\\"Win32_Devices_Pwm\\\", \\\"Win32_Devices_Sensors\\\", \\\"Win32_Devices_SerialCommunication\\\", \\\"Win32_Devices_Tapi\\\", \\\"Win32_Devices_Usb\\\", \\\"Win32_Devices_WebServicesOnDevices\\\", \\\"Win32_Foundation\\\", \\\"Win32_Gaming\\\", \\\"Win32_Globalization\\\", \\\"Win32_Graphics\\\", \\\"Win32_Graphics_Dwm\\\", \\\"Win32_Graphics_Gdi\\\", \\\"Win32_Graphics_Hlsl\\\", \\\"Win32_Graphics_OpenGL\\\", \\\"Win32_Graphics_Printing\\\", \\\"Win32_Graphics_Printing_PrintTicket\\\", \\\"Win32_Management\\\", \\\"Win32_Management_MobileDeviceManagementRegistration\\\", \\\"Win32_Media\\\", \\\"Win32_Media_Audio\\\", \\\"Win32_Media_Audio_Apo\\\", \\\"Win32_Media_Audio_DirectMusic\\\", \\\"Win32_Media_Audio_Endpoints\\\", \\\"Win32_Media_Audio_XAudio2\\\", \\\"Win32_Media_DeviceManager\\\", \\\"Win32_Media_DxMediaObjects\\\", \\\"Win32_Media_KernelStreaming\\\", \\\"Win32_Media_LibrarySharingServices\\\", \\\"Win32_Media_MediaPlayer\\\", \\\"Win32_Media_Multimedia\\\", \\\"Win32_Media_Speech\\\", \\\"Win32_Media_Streaming\\\", \\\"Win32_Media_WindowsMediaFormat\\\", \\\"Win32_NetworkManagement\\\", \\\"Win32_NetworkManagement_Dhcp\\\", \\\"Win32_NetworkManagement_Dns\\\", \\\"Win32_NetworkManagement_InternetConnectionWizard\\\", \\\"Win32_NetworkManagement_IpHelper\\\", \\\"Win32_NetworkManagement_MobileBroadband\\\", \\\"Win32_NetworkManagement_Multicast\\\", \\\"Win32_NetworkManagement_Ndis\\\", \\\"Win32_NetworkManagement_NetBios\\\", \\\"Win32_NetworkManagement_NetManagement\\\", \\\"Win32_NetworkManagement_NetShell\\\", \\\"Win32_NetworkManagement_NetworkDiagnosticsFramework\\\", \\\"Win32_NetworkManagement_NetworkPolicyServer\\\", \\\"Win32_NetworkManagement_P2P\\\", \\\"Win32_NetworkManagement_QoS\\\", \\\"Win32_NetworkManagement_Rras\\\", \\\"Win32_NetworkManagement_Snmp\\\", \\\"Win32_NetworkManagement_WNet\\\", \\\"Win32_NetworkManagement_WebDav\\\", \\\"Win32_NetworkManagement_WiFi\\\", \\\"Win32_NetworkManagement_WindowsConnectNow\\\", \\\"Win32_NetworkManagement_WindowsConnectionManager\\\", \\\"Win32_NetworkManagement_WindowsFilteringPlatform\\\", \\\"Win32_NetworkManagement_WindowsFirewall\\\", \\\"Win32_NetworkManagement_WindowsNetworkVirtualization\\\", \\\"Win32_Networking\\\", \\\"Win32_Networking_ActiveDirectory\\\", \\\"Win32_Networking_BackgroundIntelligentTransferService\\\", \\\"Win32_Networking_Clustering\\\", \\\"Win32_Networking_HttpServer\\\", \\\"Win32_Networking_Ldap\\\", \\\"Win32_Networking_NetworkListManager\\\", \\\"Win32_Networking_RemoteDifferentialCompression\\\", \\\"Win32_Networking_WebSocket\\\", \\\"Win32_Networking_WinHttp\\\", \\\"Win32_Networking_WinInet\\\", \\\"Win32_Networking_WinSock\\\", \\\"Win32_Networking_WindowsWebServices\\\", \\\"Win32_Security\\\", \\\"Win32_Security_AppLocker\\\", \\\"Win32_Security_Authentication\\\", \\\"Win32_Security_Authentication_Identity\\\", \\\"Win32_Security_Authentication_Identity_Provider\\\", \\\"Win32_Security_Authorization\\\", \\\"Win32_Security_Authorization_UI\\\", \\\"Win32_Security_ConfigurationSnapin\\\", \\\"Win32_Security_Credentials\\\", \\\"Win32_Security_Cryptography\\\", \\\"Win32_Security_Cryptography_Catalog\\\", \\\"Win32_Security_Cryptography_Certificates\\\", \\\"Win32_Security_Cryptography_Sip\\\", \\\"Win32_Security_Cryptography_UI\\\", \\\"Win32_Security_DiagnosticDataQuery\\\", \\\"Win32_Security_DirectoryServices\\\", \\\"Win32_Security_EnterpriseData\\\", \\\"Win32_Security_ExtensibleAuthenticationProtocol\\\", \\\"Win32_Security_Isolation\\\", \\\"Win32_Security_LicenseProtection\\\", \\\"Win32_Security_NetworkAccessProtection\\\", \\\"Win32_Security_Tpm\\\", \\\"Win32_Security_WinTrust\\\", \\\"Win32_Security_WinWlx\\\", \\\"Win32_Storage\\\", \\\"Win32_Storage_Cabinets\\\", \\\"Win32_Storage_CloudFilters\\\", \\\"Win32_Storage_Compression\\\", \\\"Win32_Storage_DataDeduplication\\\", \\\"Win32_Storage_DistributedFileSystem\\\", \\\"Win32_Storage_EnhancedStorage\\\", \\\"Win32_Storage_FileHistory\\\", \\\"Win32_Storage_FileServerResourceManager\\\", \\\"Win32_Storage_FileSystem\\\", \\\"Win32_Storage_Imapi\\\", \\\"Win32_Storage_IndexServer\\\", \\\"Win32_Storage_InstallableFileSystems\\\", \\\"Win32_Storage_IscsiDisc\\\", \\\"Win32_Storage_Jet\\\", \\\"Win32_Storage_OfflineFiles\\\", \\\"Win32_Storage_OperationRecorder\\\", \\\"Win32_Storage_Packaging\\\", \\\"Win32_Storage_Packaging_Appx\\\", \\\"Win32_Storage_Packaging_Opc\\\", \\\"Win32_Storage_ProjectedFileSystem\\\", \\\"Win32_Storage_StructuredStorage\\\", \\\"Win32_Storage_Vhd\\\", \\\"Win32_Storage_VirtualDiskService\\\", \\\"Win32_Storage_Vss\\\", \\\"Win32_Storage_Xps\\\", \\\"Win32_Storage_Xps_Printing\\\", \\\"Win32_System\\\", \\\"Win32_System_AddressBook\\\", \\\"Win32_System_Antimalware\\\", \\\"Win32_System_ApplicationInstallationAndServicing\\\", \\\"Win32_System_ApplicationVerifier\\\", \\\"Win32_System_AssessmentTool\\\", \\\"Win32_System_ClrHosting\\\", \\\"Win32_System_Com\\\", \\\"Win32_System_Com_CallObj\\\", \\\"Win32_System_Com_ChannelCredentials\\\", \\\"Win32_System_Com_Events\\\", \\\"Win32_System_Com_Marshal\\\", \\\"Win32_System_Com_StructuredStorage\\\", \\\"Win32_System_Com_UI\\\", \\\"Win32_System_Com_Urlmon\\\", \\\"Win32_System_ComponentServices\\\", \\\"Win32_System_Console\\\", \\\"Win32_System_Contacts\\\", \\\"Win32_System_CorrelationVector\\\", \\\"Win32_System_DataExchange\\\", \\\"Win32_System_DeploymentServices\\\", \\\"Win32_System_DesktopSharing\\\", \\\"Win32_System_DeveloperLicensing\\\", \\\"Win32_System_Diagnostics\\\", \\\"Win32_System_Diagnostics_Ceip\\\", \\\"Win32_System_Diagnostics_ClrProfiling\\\", \\\"Win32_System_Diagnostics_Debug\\\", \\\"Win32_System_Diagnostics_Debug_ActiveScript\\\", \\\"Win32_System_Diagnostics_Debug_Extensions\\\", \\\"Win32_System_Diagnostics_Etw\\\", \\\"Win32_System_Diagnostics_ProcessSnapshotting\\\", \\\"Win32_System_Diagnostics_ToolHelp\\\", \\\"Win32_System_DistributedTransactionCoordinator\\\", \\\"Win32_System_Environment\\\", \\\"Win32_System_ErrorReporting\\\", \\\"Win32_System_EventCollector\\\", \\\"Win32_System_EventLog\\\", \\\"Win32_System_EventNotificationService\\\", \\\"Win32_System_GroupPolicy\\\", \\\"Win32_System_HostCompute\\\", \\\"Win32_System_HostComputeNetwork\\\", \\\"Win32_System_HostComputeSystem\\\", \\\"Win32_System_Hypervisor\\\", \\\"Win32_System_IO\\\", \\\"Win32_System_Iis\\\", \\\"Win32_System_Ioctl\\\", \\\"Win32_System_JobObjects\\\", \\\"Win32_System_Js\\\", \\\"Win32_System_Kernel\\\", \\\"Win32_System_LibraryLoader\\\", \\\"Win32_System_Mailslots\\\", \\\"Win32_System_Mapi\\\", \\\"Win32_System_Memory\\\", \\\"Win32_System_Memory_NonVolatile\\\", \\\"Win32_System_MessageQueuing\\\", \\\"Win32_System_MixedReality\\\", \\\"Win32_System_Mmc\\\", \\\"Win32_System_Ole\\\", \\\"Win32_System_ParentalControls\\\", \\\"Win32_System_PasswordManagement\\\", \\\"Win32_System_Performance\\\", \\\"Win32_System_Performance_HardwareCounterProfiling\\\", \\\"Win32_System_Pipes\\\", \\\"Win32_System_Power\\\", \\\"Win32_System_ProcessStatus\\\", \\\"Win32_System_RealTimeCommunications\\\", \\\"Win32_System_Recovery\\\", \\\"Win32_System_Registry\\\", \\\"Win32_System_RemoteAssistance\\\", \\\"Win32_System_RemoteDesktop\\\", \\\"Win32_System_RemoteManagement\\\", \\\"Win32_System_RestartManager\\\", \\\"Win32_System_Restore\\\", \\\"Win32_System_Rpc\\\", \\\"Win32_System_Search\\\", \\\"Win32_System_Search_Common\\\", \\\"Win32_System_SecurityCenter\\\", \\\"Win32_System_ServerBackup\\\", \\\"Win32_System_Services\\\", \\\"Win32_System_SettingsManagementInfrastructure\\\", \\\"Win32_System_SetupAndMigration\\\", \\\"Win32_System_Shutdown\\\", \\\"Win32_System_StationsAndDesktops\\\", \\\"Win32_System_SubsystemForLinux\\\", \\\"Win32_System_SystemInformation\\\", \\\"Win32_System_SystemServices\\\", \\\"Win32_System_TaskScheduler\\\", \\\"Win32_System_Threading\\\", \\\"Win32_System_Time\\\", \\\"Win32_System_TpmBaseServices\\\", \\\"Win32_System_UpdateAgent\\\", \\\"Win32_System_UpdateAssessment\\\", \\\"Win32_System_UserAccessLogging\\\", \\\"Win32_System_VirtualDosMachines\\\", \\\"Win32_System_WindowsProgramming\\\", \\\"Win32_System_WindowsSync\\\", \\\"Win32_System_Wmi\\\", \\\"Win32_UI\\\", \\\"Win32_UI_Accessibility\\\", \\\"Win32_UI_Animation\\\", \\\"Win32_UI_ColorSystem\\\", \\\"Win32_UI_Controls\\\", \\\"Win32_UI_Controls_Dialogs\\\", \\\"Win32_UI_Controls_RichEdit\\\", \\\"Win32_UI_HiDpi\\\", \\\"Win32_UI_Input\\\", \\\"Win32_UI_Input_Ime\\\", \\\"Win32_UI_Input_Ink\\\", \\\"Win32_UI_Input_KeyboardAndMouse\\\", \\\"Win32_UI_Input_Pointer\\\", \\\"Win32_UI_Input_Radial\\\", \\\"Win32_UI_Input_Touch\\\", \\\"Win32_UI_Input_XboxController\\\", \\\"Win32_UI_InteractionContext\\\", \\\"Win32_UI_LegacyWindowsEnvironmentFeatures\\\", \\\"Win32_UI_Magnification\\\", \\\"Win32_UI_Notifications\\\", \\\"Win32_UI_Ribbon\\\", \\\"Win32_UI_Shell\\\", \\\"Win32_UI_Shell_Common\\\", \\\"Win32_UI_Shell_PropertiesSystem\\\", \\\"Win32_UI_TabletPC\\\", \\\"Win32_UI_TextServices\\\", \\\"Win32_UI_WindowsAndMessaging\\\", \\\"Win32_UI_Wpf\\\", \\\"Win32_Web\\\", \\\"Win32_Web_InternetExplorer\\\", \\\"default\\\"))\" -C metadata=b5b51020364d6d0c -C extra-filename=-80bdfb6f4e0c903e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --extern windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_targets-cf26163e4cd2c220.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_sys",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.48.0\\src\\lib.rs",
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
        "feature=\"Win32\"",
        "--cfg",
        "feature=\"Win32_Devices\"",
        "--cfg",
        "feature=\"Win32_Devices_HumanInterfaceDevice\"",
        "--cfg",
        "feature=\"Win32_Foundation\"",
        "--cfg",
        "feature=\"Win32_Globalization\"",
        "--cfg",
        "feature=\"Win32_Graphics\"",
        "--cfg",
        "feature=\"Win32_Graphics_Dwm\"",
        "--cfg",
        "feature=\"Win32_Graphics_Gdi\"",
        "--cfg",
        "feature=\"Win32_Media\"",
        "--cfg",
        "feature=\"Win32_System\"",
        "--cfg",
        "feature=\"Win32_System_Com\"",
        "--cfg",
        "feature=\"Win32_System_Com_StructuredStorage\"",
        "--cfg",
        "feature=\"Win32_System_LibraryLoader\"",
        "--cfg",
        "feature=\"Win32_System_Ole\"",
        "--cfg",
        "feature=\"Win32_System_SystemInformation\"",
        "--cfg",
        "feature=\"Win32_System_SystemServices\"",
        "--cfg",
        "feature=\"Win32_System_Threading\"",
        "--cfg",
        "feature=\"Win32_System_WindowsProgramming\"",
        "--cfg",
        "feature=\"Win32_UI\"",
        "--cfg",
        "feature=\"Win32_UI_Accessibility\"",
        "--cfg",
        "feature=\"Win32_UI_Controls\"",
        "--cfg",
        "feature=\"Win32_UI_HiDpi\"",
        "--cfg",
        "feature=\"Win32_UI_Input\"",
        "--cfg",
        "feature=\"Win32_UI_Input_Ime\"",
        "--cfg",
        "feature=\"Win32_UI_Input_KeyboardAndMouse\"",
        "--cfg",
        "feature=\"Win32_UI_Input_Pointer\"",
        "--cfg",
        "feature=\"Win32_UI_Input_Touch\"",
        "--cfg",
        "feature=\"Win32_UI_Shell\"",
        "--cfg",
        "feature=\"Win32_UI_TextServices\"",
        "--cfg",
        "feature=\"Win32_UI_WindowsAndMessaging\"",
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"Wdk\", \"Wdk_System\", \"Wdk_System_OfflineRegistry\", \"Win32\", \"Win32_Data\", \"Win32_Data_HtmlHelp\", \"Win32_Data_RightsManagement\", \"Win32_Data_Xml\", \"Win32_Data_Xml_MsXml\", \"Win32_Data_Xml_XmlLite\", \"Win32_Devices\", \"Win32_Devices_AllJoyn\", \"Win32_Devices_BiometricFramework\", \"Win32_Devices_Bluetooth\", \"Win32_Devices_Communication\", \"Win32_Devices_DeviceAccess\", \"Win32_Devices_DeviceAndDriverInstallation\", \"Win32_Devices_DeviceQuery\", \"Win32_Devices_Display\", \"Win32_Devices_Enumeration\", \"Win32_Devices_Enumeration_Pnp\", \"Win32_Devices_Fax\", \"Win32_Devices_FunctionDiscovery\", \"Win32_Devices_Geolocation\", \"Win32_Devices_HumanInterfaceDevice\", \"Win32_Devices_ImageAcquisition\", \"Win32_Devices_PortableDevices\", \"Win32_Devices_Properties\", \"Win32_Devices_Pwm\", \"Win32_Devices_Sensors\", \"Win32_Devices_SerialCommunication\", \"Win32_Devices_Tapi\", \"Win32_Devices_Usb\", \"Win32_Devices_WebServicesOnDevices\", \"Win32_Foundation\", \"Win32_Gaming\", \"Win32_Globalization\", \"Win32_Graphics\", \"Win32_Graphics_Dwm\", \"Win32_Graphics_Gdi\", \"Win32_Graphics_Hlsl\", \"Win32_Graphics_OpenGL\", \"Win32_Graphics_Printing\", \"Win32_Graphics_Printing_PrintTicket\", \"Win32_Management\", \"Win32_Management_MobileDeviceManagementRegistration\", \"Win32_Media\", \"Win32_Media_Audio\", \"Win32_Media_Audio_Apo\", \"Win32_Media_Audio_DirectMusic\", \"Win32_Media_Audio_Endpoints\", \"Win32_Media_Audio_XAudio2\", \"Win32_Media_DeviceManager\", \"Win32_Media_DxMediaObjects\", \"Win32_Media_KernelStreaming\", \"Win32_Media_LibrarySharingServices\", \"Win32_Media_MediaPlayer\", \"Win32_Media_Multimedia\", \"Win32_Media_Speech\", \"Win32_Media_Streaming\", \"Win32_Media_WindowsMediaFormat\", \"Win32_NetworkManagement\", \"Win32_NetworkManagement_Dhcp\", \"Win32_NetworkManagement_Dns\", \"Win32_NetworkManagement_InternetConnectionWizard\", \"Win32_NetworkManagement_IpHelper\", \"Win32_NetworkManagement_MobileBroadband\", \"Win32_NetworkManagement_Multicast\", \"Win32_NetworkManagement_Ndis\", \"Win32_NetworkManagement_NetBios\", \"Win32_NetworkManagement_NetManagement\", \"Win32_NetworkManagement_NetShell\", \"Win32_NetworkManagement_NetworkDiagnosticsFramework\", \"Win32_NetworkManagement_NetworkPolicyServer\", \"Win32_NetworkManagement_P2P\", \"Win32_NetworkManagement_QoS\", \"Win32_NetworkManagement_Rras\", \"Win32_NetworkManagement_Snmp\", \"Win32_NetworkManagement_WNet\", \"Win32_NetworkManagement_WebDav\", \"Win32_NetworkManagement_WiFi\", \"Win32_NetworkManagement_WindowsConnectNow\", \"Win32_NetworkManagement_WindowsConnectionManager\", \"Win32_NetworkManagement_WindowsFilteringPlatform\", \"Win32_NetworkManagement_WindowsFirewall\", \"Win32_NetworkManagement_WindowsNetworkVirtualization\", \"Win32_Networking\", \"Win32_Networking_ActiveDirectory\", \"Win32_Networking_BackgroundIntelligentTransferService\", \"Win32_Networking_Clustering\", \"Win32_Networking_HttpServer\", \"Win32_Networking_Ldap\", \"Win32_Networking_NetworkListManager\", \"Win32_Networking_RemoteDifferentialCompression\", \"Win32_Networking_WebSocket\", \"Win32_Networking_WinHttp\", \"Win32_Networking_WinInet\", \"Win32_Networking_WinSock\", \"Win32_Networking_WindowsWebServices\", \"Win32_Security\", \"Win32_Security_AppLocker\", \"Win32_Security_Authentication\", \"Win32_Security_Authentication_Identity\", \"Win32_Security_Authentication_Identity_Provider\", \"Win32_Security_Authorization\", \"Win32_Security_Authorization_UI\", \"Win32_Security_ConfigurationSnapin\", \"Win32_Security_Credentials\", \"Win32_Security_Cryptography\", \"Win32_Security_Cryptography_Catalog\", \"Win32_Security_Cryptography_Certificates\", \"Win32_Security_Cryptography_Sip\", \"Win32_Security_Cryptography_UI\", \"Win32_Security_DiagnosticDataQuery\", \"Win32_Security_DirectoryServices\", \"Win32_Security_EnterpriseData\", \"Win32_Security_ExtensibleAuthenticationProtocol\", \"Win32_Security_Isolation\", \"Win32_Security_LicenseProtection\", \"Win32_Security_NetworkAccessProtection\", \"Win32_Security_Tpm\", \"Win32_Security_WinTrust\", \"Win32_Security_WinWlx\", \"Win32_Storage\", \"Win32_Storage_Cabinets\", \"Win32_Storage_CloudFilters\", \"Win32_Storage_Compression\", \"Win32_Storage_DataDeduplication\", \"Win32_Storage_DistributedFileSystem\", \"Win32_Storage_EnhancedStorage\", \"Win32_Storage_FileHistory\", \"Win32_Storage_FileServerResourceManager\", \"Win32_Storage_FileSystem\", \"Win32_Storage_Imapi\", \"Win32_Storage_IndexServer\", \"Win32_Storage_InstallableFileSystems\", \"Win32_Storage_IscsiDisc\", \"Win32_Storage_Jet\", \"Win32_Storage_OfflineFiles\", \"Win32_Storage_OperationRecorder\", \"Win32_Storage_Packaging\", \"Win32_Storage_Packaging_Appx\", \"Win32_Storage_Packaging_Opc\", \"Win32_Storage_ProjectedFileSystem\", \"Win32_Storage_StructuredStorage\", \"Win32_Storage_Vhd\", \"Win32_Storage_VirtualDiskService\", \"Win32_Storage_Vss\", \"Win32_Storage_Xps\", \"Win32_Storage_Xps_Printing\", \"Win32_System\", \"Win32_System_AddressBook\", \"Win32_System_Antimalware\", \"Win32_System_ApplicationInstallationAndServicing\", \"Win32_System_ApplicationVerifier\", \"Win32_System_AssessmentTool\", \"Win32_System_ClrHosting\", \"Win32_System_Com\", \"Win32_System_Com_CallObj\", \"Win32_System_Com_ChannelCredentials\", \"Win32_System_Com_Events\", \"Win32_System_Com_Marshal\", \"Win32_System_Com_StructuredStorage\", \"Win32_System_Com_UI\", \"Win32_System_Com_Urlmon\", \"Win32_System_ComponentServices\", \"Win32_System_Console\", \"Win32_System_Contacts\", \"Win32_System_CorrelationVector\", \"Win32_System_DataExchange\", \"Win32_System_DeploymentServices\", \"Win32_System_DesktopSharing\", \"Win32_System_DeveloperLicensing\", \"Win32_System_Diagnostics\", \"Win32_System_Diagnostics_Ceip\", \"Win32_System_Diagnostics_ClrProfiling\", \"Win32_System_Diagnostics_Debug\", \"Win32_System_Diagnostics_Debug_ActiveScript\", \"Win32_System_Diagnostics_Debug_Extensions\", \"Win32_System_Diagnostics_Etw\", \"Win32_System_Diagnostics_ProcessSnapshotting\", \"Win32_System_Diagnostics_ToolHelp\", \"Win32_System_DistributedTransactionCoordinator\", \"Win32_System_Environment\", \"Win32_System_ErrorReporting\", \"Win32_System_EventCollector\", \"Win32_System_EventLog\", \"Win32_System_EventNotificationService\", \"Win32_System_GroupPolicy\", \"Win32_System_HostCompute\", \"Win32_System_HostComputeNetwork\", \"Win32_System_HostComputeSystem\", \"Win32_System_Hypervisor\", \"Win32_System_IO\", \"Win32_System_Iis\", \"Win32_System_Ioctl\", \"Win32_System_JobObjects\", \"Win32_System_Js\", \"Win32_System_Kernel\", \"Win32_System_LibraryLoader\", \"Win32_System_Mailslots\", \"Win32_System_Mapi\", \"Win32_System_Memory\", \"Win32_System_Memory_NonVolatile\", \"Win32_System_MessageQueuing\", \"Win32_System_MixedReality\", \"Win32_System_Mmc\", \"Win32_System_Ole\", \"Win32_System_ParentalControls\", \"Win32_System_PasswordManagement\", \"Win32_System_Performance\", \"Win32_System_Performance_HardwareCounterProfiling\", \"Win32_System_Pipes\", \"Win32_System_Power\", \"Win32_System_ProcessStatus\", \"Win32_System_RealTimeCommunications\", \"Win32_System_Recovery\", \"Win32_System_Registry\", \"Win32_System_RemoteAssistance\", \"Win32_System_RemoteDesktop\", \"Win32_System_RemoteManagement\", \"Win32_System_RestartManager\", \"Win32_System_Restore\", \"Win32_System_Rpc\", \"Win32_System_Search\", \"Win32_System_Search_Common\", \"Win32_System_SecurityCenter\", \"Win32_System_ServerBackup\", \"Win32_System_Services\", \"Win32_System_SettingsManagementInfrastructure\", \"Win32_System_SetupAndMigration\", \"Win32_System_Shutdown\", \"Win32_System_StationsAndDesktops\", \"Win32_System_SubsystemForLinux\", \"Win32_System_SystemInformation\", \"Win32_System_SystemServices\", \"Win32_System_TaskScheduler\", \"Win32_System_Threading\", \"Win32_System_Time\", \"Win32_System_TpmBaseServices\", \"Win32_System_UpdateAgent\", \"Win32_System_UpdateAssessment\", \"Win32_System_UserAccessLogging\", \"Win32_System_VirtualDosMachines\", \"Win32_System_WindowsProgramming\", \"Win32_System_WindowsSync\", \"Win32_System_Wmi\", \"Win32_UI\", \"Win32_UI_Accessibility\", \"Win32_UI_Animation\", \"Win32_UI_ColorSystem\", \"Win32_UI_Controls\", \"Win32_UI_Controls_Dialogs\", \"Win32_UI_Controls_RichEdit\", \"Win32_UI_HiDpi\", \"Win32_UI_Input\", \"Win32_UI_Input_Ime\", \"Win32_UI_Input_Ink\", \"Win32_UI_Input_KeyboardAndMouse\", \"Win32_UI_Input_Pointer\", \"Win32_UI_Input_Radial\", \"Win32_UI_Input_Touch\", \"Win32_UI_Input_XboxController\", \"Win32_UI_InteractionContext\", \"Win32_UI_LegacyWindowsEnvironmentFeatures\", \"Win32_UI_Magnification\", \"Win32_UI_Notifications\", \"Win32_UI_Ribbon\", \"Win32_UI_Shell\", \"Win32_UI_Shell_Common\", \"Win32_UI_Shell_PropertiesSystem\", \"Win32_UI_TabletPC\", \"Win32_UI_TextServices\", \"Win32_UI_WindowsAndMessaging\", \"Win32_UI_Wpf\", \"Win32_Web\", \"Win32_Web_InternetExplorer\", \"default\"))",
        "-C",
        "metadata=b5b51020364d6d0c",
        "-C",
        "extra-filename=-80bdfb6f4e0c903e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--extern",
        "windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_targets-cf26163e4cd2c220.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:39.543694+00:00",
      "end_time": "2026-07-13T16:48:42.158612+00:00",
      "start_unix_nanos": 1783961319543694000,
      "end_unix_nanos": 1783961322158612500,
      "crate_name": "windows_sys",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "winit:0.29.15:17260",
      "root_process_pid": 8280,
      "pid": 7700,
      "ppid": 9664,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "winit",
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
        "feature=\"ahash\"",
        "--cfg",
        "feature=\"bytemuck\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"memmap2\"",
        "--cfg",
        "feature=\"percent-encoding\"",
        "--cfg",
        "feature=\"rwh_06\"",
        "--cfg",
        "feature=\"sctk\"",
        "--cfg",
        "feature=\"sctk-adwaita\"",
        "--cfg",
        "feature=\"wayland\"",
        "--cfg",
        "feature=\"wayland-backend\"",
        "--cfg",
        "feature=\"wayland-client\"",
        "--cfg",
        "feature=\"wayland-csd-adwaita\"",
        "--cfg",
        "feature=\"wayland-dlopen\"",
        "--cfg",
        "feature=\"wayland-protocols\"",
        "--cfg",
        "feature=\"wayland-protocols-plasma\"",
        "--cfg",
        "feature=\"x11\"",
        "--cfg",
        "feature=\"x11-dl\"",
        "--cfg",
        "feature=\"x11rb\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"ahash\", \"android-game-activity\", \"android-native-activity\", \"bytemuck\", \"default\", \"memmap2\", \"mint\", \"percent-encoding\", \"rwh_04\", \"rwh_05\", \"rwh_06\", \"sctk\", \"sctk-adwaita\", \"serde\", \"wayland\", \"wayland-backend\", \"wayland-client\", \"wayland-csd-adwaita\", \"wayland-csd-adwaita-crossfont\", \"wayland-csd-adwaita-notitle\", \"wayland-dlopen\", \"wayland-protocols\", \"wayland-protocols-plasma\", \"x11\", \"x11-dl\", \"x11rb\"))",
        "-C",
        "metadata=735ce2361f38dada",
        "-C",
        "extra-filename=-651ac98e096969a1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--extern",
        "bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libbitflags-0667b619dfc545b1.rmeta",
        "--extern",
        "cursor_icon=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcursor_icon-7064bb38659984d2.rmeta",
        "--extern",
        "log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\liblog-c49eeec8812cf892.rmeta",
        "--extern",
        "once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libonce_cell-d076018eae555cad.rmeta",
        "--extern",
        "rwh_06=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libraw_window_handle-8084b02d24173edc.rmeta",
        "--extern",
        "smol_str=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libsmol_str-a58cc8446871329b.rmeta",
        "--extern",
        "unicode_segmentation=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libunicode_segmentation-82c365516f112666.rmeta",
        "--extern",
        "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_sys-80bdfb6f4e0c903e.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
        "--cfg",
        "windows_platform"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name winit --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"ahash\\\"\" --cfg \"feature=\\\"bytemuck\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"memmap2\\\"\" --cfg \"feature=\\\"percent-encoding\\\"\" --cfg \"feature=\\\"rwh_06\\\"\" --cfg \"feature=\\\"sctk\\\"\" --cfg \"feature=\\\"sctk-adwaita\\\"\" --cfg \"feature=\\\"wayland\\\"\" --cfg \"feature=\\\"wayland-backend\\\"\" --cfg \"feature=\\\"wayland-client\\\"\" --cfg \"feature=\\\"wayland-csd-adwaita\\\"\" --cfg \"feature=\\\"wayland-dlopen\\\"\" --cfg \"feature=\\\"wayland-protocols\\\"\" --cfg \"feature=\\\"wayland-protocols-plasma\\\"\" --cfg \"feature=\\\"x11\\\"\" --cfg \"feature=\\\"x11-dl\\\"\" --cfg \"feature=\\\"x11rb\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"ahash\\\", \\\"android-game-activity\\\", \\\"android-native-activity\\\", \\\"bytemuck\\\", \\\"default\\\", \\\"memmap2\\\", \\\"mint\\\", \\\"percent-encoding\\\", \\\"rwh_04\\\", \\\"rwh_05\\\", \\\"rwh_06\\\", \\\"sctk\\\", \\\"sctk-adwaita\\\", \\\"serde\\\", \\\"wayland\\\", \\\"wayland-backend\\\", \\\"wayland-client\\\", \\\"wayland-csd-adwaita\\\", \\\"wayland-csd-adwaita-crossfont\\\", \\\"wayland-csd-adwaita-notitle\\\", \\\"wayland-dlopen\\\", \\\"wayland-protocols\\\", \\\"wayland-protocols-plasma\\\", \\\"x11\\\", \\\"x11-dl\\\", \\\"x11rb\\\"))\" -C metadata=735ce2361f38dada -C extra-filename=-651ac98e096969a1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps --extern bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libbitflags-0667b619dfc545b1.rmeta --extern cursor_icon=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcursor_icon-7064bb38659984d2.rmeta --extern log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\liblog-c49eeec8812cf892.rmeta --extern once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libonce_cell-d076018eae555cad.rmeta --extern rwh_06=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libraw_window_handle-8084b02d24173edc.rmeta --extern smol_str=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libsmol_str-a58cc8446871329b.rmeta --extern unicode_segmentation=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libunicode_segmentation-82c365516f112666.rmeta --extern windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_sys-80bdfb6f4e0c903e.rmeta -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib --cfg windows_platform",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "winit",
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
        "feature=\"ahash\"",
        "--cfg",
        "feature=\"bytemuck\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"memmap2\"",
        "--cfg",
        "feature=\"percent-encoding\"",
        "--cfg",
        "feature=\"rwh_06\"",
        "--cfg",
        "feature=\"sctk\"",
        "--cfg",
        "feature=\"sctk-adwaita\"",
        "--cfg",
        "feature=\"wayland\"",
        "--cfg",
        "feature=\"wayland-backend\"",
        "--cfg",
        "feature=\"wayland-client\"",
        "--cfg",
        "feature=\"wayland-csd-adwaita\"",
        "--cfg",
        "feature=\"wayland-dlopen\"",
        "--cfg",
        "feature=\"wayland-protocols\"",
        "--cfg",
        "feature=\"wayland-protocols-plasma\"",
        "--cfg",
        "feature=\"x11\"",
        "--cfg",
        "feature=\"x11-dl\"",
        "--cfg",
        "feature=\"x11rb\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"ahash\", \"android-game-activity\", \"android-native-activity\", \"bytemuck\", \"default\", \"memmap2\", \"mint\", \"percent-encoding\", \"rwh_04\", \"rwh_05\", \"rwh_06\", \"sctk\", \"sctk-adwaita\", \"serde\", \"wayland\", \"wayland-backend\", \"wayland-client\", \"wayland-csd-adwaita\", \"wayland-csd-adwaita-crossfont\", \"wayland-csd-adwaita-notitle\", \"wayland-dlopen\", \"wayland-protocols\", \"wayland-protocols-plasma\", \"x11\", \"x11-dl\", \"x11rb\"))",
        "-C",
        "metadata=735ce2361f38dada",
        "-C",
        "extra-filename=-651ac98e096969a1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps",
        "--extern",
        "bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libbitflags-0667b619dfc545b1.rmeta",
        "--extern",
        "cursor_icon=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libcursor_icon-7064bb38659984d2.rmeta",
        "--extern",
        "log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\liblog-c49eeec8812cf892.rmeta",
        "--extern",
        "once_cell=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libonce_cell-d076018eae555cad.rmeta",
        "--extern",
        "rwh_06=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libraw_window_handle-8084b02d24173edc.rmeta",
        "--extern",
        "smol_str=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libsmol_str-a58cc8446871329b.rmeta",
        "--extern",
        "unicode_segmentation=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libunicode_segmentation-82c365516f112666.rmeta",
        "--extern",
        "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps\\libwindows_sys-80bdfb6f4e0c903e.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.48.5\\lib",
        "--cfg",
        "windows_platform"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T16:48:41.826319+00:00",
      "end_time": "2026-07-13T16:48:45.039551+00:00",
      "start_unix_nanos": 1783961321826318900,
      "end_unix_nanos": 1783961325039550800,
      "crate_name": "winit",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-dfbn_7qr\\src\\winit-0.29.15\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 2160,
    "crate": "winit",
    "version": "0.29.15",
    "crate_id": "4573",
    "version_id": "1080807",
    "downloads": 6293002,
    "cumulative_downloads": 102811124838,
    "cumulative_share_of_global": 0.3843870612232489,
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
