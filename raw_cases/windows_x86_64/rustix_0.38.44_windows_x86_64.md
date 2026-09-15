# `rustix` `0.38.44`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "rustix",
    "version": "0.38.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000001f8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000248       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000268       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000280       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000290       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000350       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000378       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000001f8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000001f8       \\177KERNEL32_NULL_THUNK_DATA 00000001400351f8     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000248       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000248       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140035248     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000268       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000268       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140035268     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000280       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000280       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140035280     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000290       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000290       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140035290     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000002a0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400352a0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000338       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140035338     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000350       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000350       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140035350     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000378       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000378       \\177ntdll_NULL_THUNK_DATA  0000000140035378     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-17072-1783954156837597100.map",
  "pid": 17072,
  "ppid": 6272,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-17072-1783954156837597100.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "rustix",
    "version": "0.38.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#adler2@2.0.0",
      "name": "adler2",
      "version": "2.0.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler2-2.0.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler2-2.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
      "name": "aho-corasick",
      "version": "1.1.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#anes@0.1.6",
      "name": "anes",
      "version": "0.1.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\anes-0.1.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\anes-0.1.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
      "name": "atty",
      "version": "0.2.14",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atty-0.2.14\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atty-0.2.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.4.0",
      "name": "autocfg",
      "version": "1.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
      "name": "bitflags",
      "version": "1.3.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.6.0",
      "name": "bitflags",
      "version": "2.6.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.16.0",
      "name": "bumpalo",
      "version": "3.16.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.16.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.16.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
      "name": "cast",
      "version": "0.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cast-0.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cast-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.2",
      "name": "ciborium",
      "version": "0.2.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-0.2.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-0.2.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-io@0.2.2",
      "name": "ciborium-io",
      "version": "0.2.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-io-0.2.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-io-0.2.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-ll@0.2.2",
      "name": "ciborium-ll",
      "version": "0.2.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-ll-0.2.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-ll-0.2.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@3.2.25",
      "name": "clap",
      "version": "3.2.25",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap-3.2.25\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap-3.2.25"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_lex@0.2.4",
      "name": "clap_lex",
      "version": "0.2.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap_lex-0.2.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap_lex-0.2.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crc32fast@1.4.2",
      "name": "crc32fast",
      "version": "1.4.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crc32fast-1.4.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crc32fast-1.4.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.4.0",
      "name": "criterion",
      "version": "0.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-0.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.5.0",
      "name": "criterion-plot",
      "version": "0.5.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-plot-0.5.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-plot-0.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.6",
      "name": "crossbeam-deque",
      "version": "0.8.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-deque-0.8.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-deque-0.8.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.18",
      "name": "crossbeam-epoch",
      "version": "0.9.18",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-epoch-0.9.18\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-epoch-0.9.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.21",
      "name": "crossbeam-utils",
      "version": "0.8.21",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.21\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.21"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crunchy@0.2.2",
      "name": "crunchy",
      "version": "0.2.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crunchy-0.2.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crunchy-0.2.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#dashmap@5.5.3",
      "name": "dashmap",
      "version": "5.5.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dashmap-5.5.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dashmap-5.5.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.13.0",
      "name": "either",
      "version": "1.13.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\either-1.13.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\either-1.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.10",
      "name": "errno",
      "version": "0.3.10",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.3.0",
      "name": "fastrand",
      "version": "2.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#flate2@1.0.35",
      "name": "flate2",
      "version": "1.0.35",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\flate2-1.0.35\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\flate2-1.0.35"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-executor@0.3.31",
      "name": "futures-executor",
      "version": "0.3.31",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-executor-0.3.31\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-executor-0.3.31"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.15",
      "name": "getrandom",
      "version": "0.2.15",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.2.15\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.2.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@2.4.1",
      "name": "half",
      "version": "2.4.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-2.4.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-2.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.12.3",
      "name": "hashbrown",
      "version": "0.12.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.12.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.12.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.14.5",
      "name": "hashbrown",
      "version": "0.14.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.14.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.14.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
      "name": "hermit-abi",
      "version": "0.1.19",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hermit-abi-0.1.19\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hermit-abi-0.1.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@1.9.3",
      "name": "indexmap",
      "version": "1.9.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-1.9.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-1.9.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
      "name": "itertools",
      "version": "0.10.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itertools-0.10.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itertools-0.10.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
      "name": "itoa",
      "version": "1.0.14",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.76",
      "name": "js-sys",
      "version": "0.3.76",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.76\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.76"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
      "name": "lazy_static",
      "version": "1.5.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lazy_static-1.5.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lazy_static-1.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
      "name": "libc",
      "version": "0.2.169",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.169\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.169"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.15",
      "name": "linux-raw-sys",
      "version": "0.4.15",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.4.15\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.4.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lock_api@0.4.12",
      "name": "lock_api",
      "version": "0.4.12",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lock_api-0.4.12\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lock_api-0.4.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.22",
      "name": "log",
      "version": "0.4.22",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.22\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.22"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
      "name": "memchr",
      "version": "2.7.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.1",
      "name": "memoffset",
      "version": "0.9.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.9.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.9.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#miniz_oxide@0.8.2",
      "name": "miniz_oxide",
      "version": "0.8.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.8.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.8.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
      "name": "num-traits",
      "version": "0.2.19",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.19\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.20.2",
      "name": "once_cell",
      "version": "1.20.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.20.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.20.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.4",
      "name": "oorandom",
      "version": "11.1.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\oorandom-11.1.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\oorandom-11.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#os_str_bytes@6.6.1",
      "name": "os_str_bytes",
      "version": "6.6.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\os_str_bytes-6.6.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\os_str_bytes-6.6.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot@0.12.3",
      "name": "parking_lot",
      "version": "0.12.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot-0.12.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot-0.12.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot_core@0.9.10",
      "name": "parking_lot_core",
      "version": "0.9.10",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot_core-0.9.10\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot_core-0.9.10"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
      "name": "plotters",
      "version": "0.3.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-0.3.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
      "name": "plotters-backend",
      "version": "0.3.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-backend-0.3.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-backend-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
      "name": "plotters-svg",
      "version": "0.3.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-svg-0.3.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-svg-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.92",
      "name": "proc-macro2",
      "version": "1.0.92",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.92\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.92"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
      "name": "quote",
      "version": "1.0.38",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.38\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.38"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.10.0",
      "name": "rayon",
      "version": "1.10.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-1.10.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-1.10.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.12.1",
      "name": "rayon-core",
      "version": "1.12.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-core-1.12.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-core-1.12.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.5.8",
      "name": "redox_syscall",
      "version": "0.5.8",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.5.8\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.5.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.11.1",
      "name": "regex",
      "version": "1.11.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
      "name": "regex-automata",
      "version": "0.4.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.5",
      "name": "regex-syntax",
      "version": "0.8.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.43",
      "name": "rustix",
      "version": "0.38.43",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-0.38.43\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-0.38.43"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
      "name": "rustix",
      "version": "0.38.44",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.18",
      "name": "ryu",
      "version": "1.0.18",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
      "name": "same-file",
      "version": "1.0.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
      "name": "scopeguard",
      "version": "1.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scopeguard-1.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scopeguard-1.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
      "name": "serde",
      "version": "1.0.217",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
      "name": "serde_derive",
      "version": "1.0.217",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.217\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.217"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.135",
      "name": "serde_json",
      "version": "1.0.135",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.135\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.135"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serial_test@2.0.0",
      "name": "serial_test",
      "version": "2.0.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serial_test-2.0.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serial_test-2.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serial_test_derive@2.0.0",
      "name": "serial_test_derive",
      "version": "2.0.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serial_test_derive-2.0.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serial_test_derive-2.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.9",
      "name": "slab",
      "version": "0.4.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#smallvec@1.13.2",
      "name": "smallvec",
      "version": "1.13.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.13.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.13.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#static_assertions@1.1.0",
      "name": "static_assertions",
      "version": "1.1.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\static_assertions-1.1.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\static_assertions-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.95",
      "name": "syn",
      "version": "2.0.95",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.95\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.95"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tempfile@3.15.0",
      "name": "tempfile",
      "version": "3.15.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tempfile-3.15.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tempfile-3.15.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.16.1",
      "name": "textwrap",
      "version": "0.16.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\textwrap-0.16.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\textwrap-0.16.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
      "name": "tinytemplate",
      "version": "1.2.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tinytemplate-1.2.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tinytemplate-1.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.14",
      "name": "unicode-ident",
      "version": "1.0.14",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.14\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
      "name": "walkdir",
      "version": "2.5.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.5.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
      "name": "wasi",
      "version": "0.11.0+wasi-snapshot-preview1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.11.0+wasi-snapshot-preview1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.11.0+wasi-snapshot-preview1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.99",
      "name": "wasm-bindgen",
      "version": "0.2.99",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.99\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.99"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.99",
      "name": "wasm-bindgen-backend",
      "version": "0.2.99",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-backend-0.2.99\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-backend-0.2.99"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.99",
      "name": "wasm-bindgen-macro",
      "version": "0.2.99",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.99\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.99"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.99",
      "name": "wasm-bindgen-macro-support",
      "version": "0.2.99",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.99\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.99"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.99",
      "name": "wasm-bindgen-shared",
      "version": "0.2.99",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.99\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.99"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.76",
      "name": "web-sys",
      "version": "0.3.76",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.76\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.76"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.9",
      "name": "winapi-util",
      "version": "0.1.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
      "name": "winapi-x86_64-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
      "name": "windows-sys",
      "version": "0.59.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
      "name": "windows-targets",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.6",
      "name": "windows_aarch64_gnullvm",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.6",
      "name": "windows_aarch64_msvc",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
      "name": "windows_i686_gnu",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.6",
      "name": "windows_i686_gnullvm",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnullvm-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnullvm-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
      "name": "windows_i686_msvc",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
      "name": "windows_x86_64_gnu",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.6",
      "name": "windows_x86_64_gnullvm",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
      "name": "windows_x86_64_msvc",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "exit_code": 0,
  "kind": "exec",
  "pid": 9268,
  "ppid": 10760,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:3aff0bc856f31bfd:e8de79f1eb1779bb",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
  "pid": 9268,
  "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:7e0f63e5ff214ab3:e8de79f1eb1779bb",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
  "pid": 9268,
  "sha256": "e64fa3fcaf1d5daf1907f7ad5f635c73081f2a499b21932a59efdac305d92c00",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:8020e6d8e2bae565:e8de79f1eb1779bb",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
  "pid": 9268,
  "sha256": "634a3a0773b3d31265e3d84380f06a40098c1bc7a23c6c9db7ead60d604ee899",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:1ceda9c220daf075:e8de79f1eb1779bb",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "kernel32.lib",
  "pid": 9268,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:1ceda9c220daf075:e8de79f1eb1779bb",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "kernel32.lib",
  "pid": 9268,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:1ceda9c220daf075:e8de79f1eb1779bb",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "kernel32.lib",
  "pid": 9268,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:1db9512c4d5c31e6:e8de79f1eb1779bb",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "ntdll.lib",
  "pid": 9268,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:861f0814f9c52599:e8de79f1eb1779bb",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "userenv.lib",
  "pid": 9268,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:50848825683fdca9:e8de79f1eb1779bb",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "ws2_32.lib",
  "pid": 9268,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "used:link:e4dabb9c925fb3b9:df7d4e53c08047f7:e8de79f1eb1779bb",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "path": "dbghelp.lib",
  "pid": 9268,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o"
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
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "cargo_pkg_name": "windows_x86_64_msvc",
  "cargo_pkg_version": "0.52.6",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 9268,
  "ppid": 10760,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "directories": [
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000148       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000198       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000288       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-9268-1783954156770894200.map",
  "pid": 9268,
  "ppid": 10760,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-9268-1783954156770894200.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17072,
  "ppid": 6272,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "rustix",
    "version": "0.38.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "rustix",
    "version": "0.38.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "cargo_pkg_name": "rustix",
  "cargo_pkg_version": "0.38.44",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 17072,
  "ppid": 6272,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "_owner": {
    "crate": "rustix",
    "version": "0.38.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000001f8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000248       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000268       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000280       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000290       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000350       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000378       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000001f8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000001f8       \\177KERNEL32_NULL_THUNK_DATA 00000001400351f8     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000248       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000248       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140035248     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000268       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000268       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140035268     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000280       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000280       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140035280     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000290       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000290       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140035290     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000002a0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400352a0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000338       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140035338     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000350       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000350       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140035350     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000378       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000378       \\177ntdll_NULL_THUNK_DATA  0000000140035378     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-17072-1783954156837597100.map",
  "pid": 17072,
  "ppid": 6272,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-17072-1783954156837597100.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "rustix",
    "version": "0.38.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "crate": "windows_x86_64_msvc",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "event_id": "bsrun:74c91b68f6495963:d5cd19ac9cf9f506:ba1ac6a86aa25d04",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44/target/debug/build/windows_x86_64_msvc-d70364700e1c05c8\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44/target/debug/build/windows_x86_64_msvc-d70364700e1c05c8/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
  "success": true,
  "target": null,
  "version": "0.52.6",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
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
  "raw_event_count": 2771,
  "parsed_event_count": 2771,
  "parse_error_count": 0,
  "command_line_event_count": 2771,
  "build_script_root_event_count": 54,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 192,
  "dropped_event_count": 1402
}
```

#### Record 22

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11104,
  "ppid": 10292,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:49:16.938118+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build-script-build.exe",
  "root_cargo_pid": 2908,
  "build_script_root_pid": 11104,
  "build_script_related": true,
  "build_script_target_dir": "windows_x86_64_msvc-d70364700e1c05c8",
  "_owner": {
    "crate": "windows_x86_64_msvc",
    "version": "0.52.6",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44/target/debug/build/windows_x86_64_msvc-d70364700e1c05c8/out"
}
```

#### Record 23

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 5024,
  "ppid": 10404,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
  "time": "2026-07-13T14:49:15.594039+00:00",
  "end_time": "2026-07-13T14:49:15.612106+00:00",
  "start_unix_nanos": 1783954155594039000,
  "end_unix_nanos": 1783954155612106300,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 3216,
  "ppid": 10404,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
  "time": "2026-07-13T14:49:15.618282+00:00",
  "end_time": "2026-07-13T14:49:15.636690+00:00",
  "start_unix_nanos": 1783954155618282400,
  "end_unix_nanos": 1783954155636689900,
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

#### Record 25

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 11144,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
  "time": "2026-07-13T14:49:16.513548+00:00",
  "end_time": "2026-07-13T14:49:16.530687+00:00",
  "start_unix_nanos": 1783954156513548200,
  "end_unix_nanos": 1783954156530686900,
  "crate_name": null,
  "crate_type": [],
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 5064,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
  "time": "2026-07-13T14:49:16.536899+00:00",
  "end_time": "2026-07-13T14:49:16.556631+00:00",
  "start_unix_nanos": 1783954156536899400,
  "end_unix_nanos": 1783954156556630600,
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

#### Record 27

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 14360,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
  "time": "2026-07-13T14:49:16.585212+00:00",
  "end_time": "2026-07-13T14:49:16.604410+00:00",
  "start_unix_nanos": 1783954156585211700,
  "end_unix_nanos": 1783954156604409800,
  "crate_name": null,
  "crate_type": [],
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 1920,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\build.rs",
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
    "metadata=c40b9585e3e79a94",
    "-C",
    "extra-filename=-d70364700e1c05c8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=c40b9585e3e79a94 -C extra-filename=-d70364700e1c05c8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\build.rs",
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
    "metadata=c40b9585e3e79a94",
    "-C",
    "extra-filename=-d70364700e1c05c8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:16.633493+00:00",
  "end_time": "2026-07-13T14:49:16.867832+00:00",
  "start_unix_nanos": 1783954156633493500,
  "end_unix_nanos": 1783954156867832100,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8"
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 16456,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "bitflags",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0\\src\\lib.rs",
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
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std\"))",
    "-C",
    "metadata=75eee6cc8dbe924b",
    "-C",
    "extra-filename=-4db8ea0490b59b49",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name bitflags --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"bytemuck\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"example_generated\\\", \\\"rustc-dep-of-std\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=75eee6cc8dbe924b -C extra-filename=-4db8ea0490b59b49 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "bitflags",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0\\src\\lib.rs",
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
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std\"))",
    "-C",
    "metadata=75eee6cc8dbe924b",
    "-C",
    "extra-filename=-4db8ea0490b59b49",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:16.636323+00:00",
  "end_time": "2026-07-13T14:49:16.821174+00:00",
  "start_unix_nanos": 1783954156636322900,
  "end_unix_nanos": 1783954156821174400,
  "crate_name": "bitflags",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 12964,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(alloc_c_string)",
    "--check-cfg",
    "cfg(alloc_ffi)",
    "--check-cfg",
    "cfg(apple)",
    "--check-cfg",
    "cfg(asm_experimental_arch)",
    "--check-cfg",
    "cfg(bsd)",
    "--check-cfg",
    "cfg(core_c_str)",
    "--check-cfg",
    "cfg(core_ffi_c)",
    "--check-cfg",
    "cfg(core_intrinsics)",
    "--check-cfg",
    "cfg(criterion)",
    "--check-cfg",
    "cfg(document_experimental_runtime_api)",
    "--check-cfg",
    "cfg(fix_y2038)",
    "--check-cfg",
    "cfg(freebsdlike)",
    "--check-cfg",
    "cfg(libc)",
    "--check-cfg",
    "cfg(linux_kernel)",
    "--check-cfg",
    "cfg(linux_like)",
    "--check-cfg",
    "cfg(linux_raw)",
    "--check-cfg",
    "cfg(netbsdlike)",
    "--check-cfg",
    "cfg(rustc_attrs)",
    "--check-cfg",
    "cfg(solarish)",
    "--check-cfg",
    "cfg(staged_api)",
    "--check-cfg",
    "cfg(static_assertions)",
    "--check-cfg",
    "cfg(thumb_mode)",
    "--check-cfg",
    "cfg(wasi)",
    "--check-cfg",
    "cfg(wasi_ext)",
    "--check-cfg",
    "cfg(target_arch, values(\"xtensa\"))",
    "--cfg",
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"libc-extra-traits\"",
    "--cfg",
    "feature=\"std\"",
    "--cfg",
    "feature=\"use-libc-auxv\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"all-apis\", \"alloc\", \"cc\", \"compiler_builtins\", \"core\", \"default\", \"event\", \"fs\", \"io_uring\", \"itoa\", \"libc\", \"libc-extra-traits\", \"libc_errno\", \"linux_4_11\", \"linux_latest\", \"mm\", \"mount\", \"net\", \"once_cell\", \"param\", \"pipe\", \"process\", \"procfs\", \"pty\", \"rand\", \"runtime\", \"rustc-dep-of-std\", \"rustc-std-workspace-alloc\", \"shm\", \"std\", \"stdio\", \"system\", \"termios\", \"thread\", \"time\", \"try_close\", \"use-explicitly-provided-auxv\", \"use-libc\", \"use-libc-auxv\"))",
    "-C",
    "metadata=ae0438f501f3af71",
    "-C",
    "extra-filename=-cd5fd26b3ac4112f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg cfg(apple) --check-cfg cfg(asm_experimental_arch) --check-cfg cfg(bsd) --check-cfg cfg(core_c_str) --check-cfg cfg(core_ffi_c) --check-cfg cfg(core_intrinsics) --check-cfg cfg(criterion) --check-cfg cfg(document_experimental_runtime_api) --check-cfg cfg(fix_y2038) --check-cfg cfg(freebsdlike) --check-cfg cfg(libc) --check-cfg cfg(linux_kernel) --check-cfg cfg(linux_like) --check-cfg cfg(linux_raw) --check-cfg cfg(netbsdlike) --check-cfg cfg(rustc_attrs) --check-cfg cfg(solarish) --check-cfg cfg(staged_api) --check-cfg cfg(static_assertions) --check-cfg cfg(thumb_mode) --check-cfg cfg(wasi) --check-cfg cfg(wasi_ext) --check-cfg \"cfg(target_arch, values(\\\"xtensa\\\"))\" --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"libc-extra-traits\\\"\" --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"use-libc-auxv\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"all-apis\\\", \\\"alloc\\\", \\\"cc\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"event\\\", \\\"fs\\\", \\\"io_uring\\\", \\\"itoa\\\", \\\"libc\\\", \\\"libc-extra-traits\\\", \\\"libc_errno\\\", \\\"linux_4_11\\\", \\\"linux_latest\\\", \\\"mm\\\", \\\"mount\\\", \\\"net\\\", \\\"once_cell\\\", \\\"param\\\", \\\"pipe\\\", \\\"process\\\", \\\"procfs\\\", \\\"pty\\\", \\\"rand\\\", \\\"runtime\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-alloc\\\", \\\"shm\\\", \\\"std\\\", \\\"stdio\\\", \\\"system\\\", \\\"termios\\\", \\\"thread\\\", \\\"time\\\", \\\"try_close\\\", \\\"use-explicitly-provided-auxv\\\", \\\"use-libc\\\", \\\"use-libc-auxv\\\"))\" -C metadata=ae0438f501f3af71 -C extra-filename=-cd5fd26b3ac4112f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
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
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(alloc_c_string)",
    "--check-cfg",
    "cfg(alloc_ffi)",
    "--check-cfg",
    "cfg(apple)",
    "--check-cfg",
    "cfg(asm_experimental_arch)",
    "--check-cfg",
    "cfg(bsd)",
    "--check-cfg",
    "cfg(core_c_str)",
    "--check-cfg",
    "cfg(core_ffi_c)",
    "--check-cfg",
    "cfg(core_intrinsics)",
    "--check-cfg",
    "cfg(criterion)",
    "--check-cfg",
    "cfg(document_experimental_runtime_api)",
    "--check-cfg",
    "cfg(fix_y2038)",
    "--check-cfg",
    "cfg(freebsdlike)",
    "--check-cfg",
    "cfg(libc)",
    "--check-cfg",
    "cfg(linux_kernel)",
    "--check-cfg",
    "cfg(linux_like)",
    "--check-cfg",
    "cfg(linux_raw)",
    "--check-cfg",
    "cfg(netbsdlike)",
    "--check-cfg",
    "cfg(rustc_attrs)",
    "--check-cfg",
    "cfg(solarish)",
    "--check-cfg",
    "cfg(staged_api)",
    "--check-cfg",
    "cfg(static_assertions)",
    "--check-cfg",
    "cfg(thumb_mode)",
    "--check-cfg",
    "cfg(wasi)",
    "--check-cfg",
    "cfg(wasi_ext)",
    "--check-cfg",
    "cfg(target_arch, values(\"xtensa\"))",
    "--cfg",
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"libc-extra-traits\"",
    "--cfg",
    "feature=\"std\"",
    "--cfg",
    "feature=\"use-libc-auxv\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"all-apis\", \"alloc\", \"cc\", \"compiler_builtins\", \"core\", \"default\", \"event\", \"fs\", \"io_uring\", \"itoa\", \"libc\", \"libc-extra-traits\", \"libc_errno\", \"linux_4_11\", \"linux_latest\", \"mm\", \"mount\", \"net\", \"once_cell\", \"param\", \"pipe\", \"process\", \"procfs\", \"pty\", \"rand\", \"runtime\", \"rustc-dep-of-std\", \"rustc-std-workspace-alloc\", \"shm\", \"std\", \"stdio\", \"system\", \"termios\", \"thread\", \"time\", \"try_close\", \"use-explicitly-provided-auxv\", \"use-libc\", \"use-libc-auxv\"))",
    "-C",
    "metadata=ae0438f501f3af71",
    "-C",
    "extra-filename=-cd5fd26b3ac4112f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:16.639356+00:00",
  "end_time": "2026-07-13T14:49:17.271338+00:00",
  "start_unix_nanos": 1783954156639356300,
  "end_unix_nanos": 1783954157271337600,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f"
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 15308,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_x86_64_msvc",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\src\\lib.rs",
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
    "metadata=2c7388cfc29d58e3",
    "-C",
    "extra-filename=-c5c5726af64828cf",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_x86_64_msvc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=2c7388cfc29d58e3 -C extra-filename=-c5c5726af64828cf --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_x86_64_msvc",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\src\\lib.rs",
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
    "metadata=2c7388cfc29d58e3",
    "-C",
    "extra-filename=-c5c5726af64828cf",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:16.958290+00:00",
  "end_time": "2026-07-13T14:49:17.024756+00:00",
  "start_unix_nanos": 1783954156958289900,
  "end_unix_nanos": 1783954157024756200,
  "crate_name": "windows_x86_64_msvc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 15232,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_targets",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--warn=rust_2018_idioms",
    "--warn=unexpected_cfgs",
    "--warn=missing_docs",
    "--check-cfg",
    "cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=6bcdc394d921aa7b",
    "-C",
    "extra-filename=-b170585257b0d7b4",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--extern",
    "windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_x86_64_msvc-c5c5726af64828cf.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_targets --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=unexpected_cfgs --warn=missing_docs --check-cfg \"cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=6bcdc394d921aa7b -C extra-filename=-b170585257b0d7b4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --extern windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_x86_64_msvc-c5c5726af64828cf.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_targets",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--warn=rust_2018_idioms",
    "--warn=unexpected_cfgs",
    "--warn=missing_docs",
    "--check-cfg",
    "cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=6bcdc394d921aa7b",
    "-C",
    "extra-filename=-b170585257b0d7b4",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--extern",
    "windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_x86_64_msvc-c5c5726af64828cf.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:17.006344+00:00",
  "end_time": "2026-07-13T14:49:17.056560+00:00",
  "start_unix_nanos": 1783954157006343800,
  "end_unix_nanos": 1783954157056560300,
  "crate_name": "windows_targets",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 9624,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_sys",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--warn=rust_2018_idioms",
    "--warn=unexpected_cfgs",
    "--warn=missing_docs",
    "--check-cfg",
    "cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)",
    "--cfg",
    "feature=\"Win32\"",
    "--cfg",
    "feature=\"Win32_Foundation\"",
    "--cfg",
    "feature=\"Win32_NetworkManagement\"",
    "--cfg",
    "feature=\"Win32_NetworkManagement_IpHelper\"",
    "--cfg",
    "feature=\"Win32_Networking\"",
    "--cfg",
    "feature=\"Win32_Networking_WinSock\"",
    "--cfg",
    "feature=\"Win32_System\"",
    "--cfg",
    "feature=\"Win32_System_Diagnostics\"",
    "--cfg",
    "feature=\"Win32_System_Diagnostics_Debug\"",
    "--cfg",
    "feature=\"Win32_System_Threading\"",
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"Wdk\", \"Wdk_Devices\", \"Wdk_Devices_Bluetooth\", \"Wdk_Devices_HumanInterfaceDevice\", \"Wdk_Foundation\", \"Wdk_Graphics\", \"Wdk_Graphics_Direct3D\", \"Wdk_NetworkManagement\", \"Wdk_NetworkManagement_Ndis\", \"Wdk_NetworkManagement_WindowsFilteringPlatform\", \"Wdk_Storage\", \"Wdk_Storage_FileSystem\", \"Wdk_Storage_FileSystem_Minifilters\", \"Wdk_System\", \"Wdk_System_IO\", \"Wdk_System_Memory\", \"Wdk_System_OfflineRegistry\", \"Wdk_System_Registry\", \"Wdk_System_SystemInformation\", \"Wdk_System_SystemServices\", \"Wdk_System_Threading\", \"Win32\", \"Win32_Data\", \"Win32_Data_HtmlHelp\", \"Win32_Data_RightsManagement\", \"Win32_Devices\", \"Win32_Devices_AllJoyn\", \"Win32_Devices_BiometricFramework\", \"Win32_Devices_Bluetooth\", \"Win32_Devices_Communication\", \"Win32_Devices_DeviceAndDriverInstallation\", \"Win32_Devices_DeviceQuery\", \"Win32_Devices_Display\", \"Win32_Devices_Enumeration\", \"Win32_Devices_Enumeration_Pnp\", \"Win32_Devices_Fax\", \"Win32_Devices_HumanInterfaceDevice\", \"Win32_Devices_PortableDevices\", \"Win32_Devices_Properties\", \"Win32_Devices_Pwm\", \"Win32_Devices_Sensors\", \"Win32_Devices_SerialCommunication\", \"Win32_Devices_Tapi\", \"Win32_Devices_Usb\", \"Win32_Devices_WebServicesOnDevices\", \"Win32_Foundation\", \"Win32_Gaming\", \"Win32_Globalization\", \"Win32_Graphics\", \"Win32_Graphics_Dwm\", \"Win32_Graphics_Gdi\", \"Win32_Graphics_GdiPlus\", \"Win32_Graphics_Hlsl\", \"Win32_Graphics_OpenGL\", \"Win32_Graphics_Printing\", \"Win32_Graphics_Printing_PrintTicket\", \"Win32_Management\", \"Win32_Management_MobileDeviceManagementRegistration\", \"Win32_Media\", \"Win32_Media_Audio\", \"Win32_Media_DxMediaObjects\", \"Win32_Media_KernelStreaming\", \"Win32_Media_Multimedia\", \"Win32_Media_Streaming\", \"Win32_Media_WindowsMediaFormat\", \"Win32_NetworkManagement\", \"Win32_NetworkManagement_Dhcp\", \"Win32_NetworkManagement_Dns\", \"Win32_NetworkManagement_InternetConnectionWizard\", \"Win32_NetworkManagement_IpHelper\", \"Win32_NetworkManagement_Multicast\", \"Win32_NetworkManagement_Ndis\", \"Win32_NetworkManagement_NetBios\", \"Win32_NetworkManagement_NetManagement\", \"Win32_NetworkManagement_NetShell\", \"Win32_NetworkManagement_NetworkDiagnosticsFramework\", \"Win32_NetworkManagement_P2P\", \"Win32_NetworkManagement_QoS\", \"Win32_NetworkManagement_Rras\", \"Win32_NetworkManagement_Snmp\", \"Win32_NetworkManagement_WNet\", \"Win32_NetworkManagement_WebDav\", \"Win32_NetworkManagement_WiFi\", \"Win32_NetworkManagement_WindowsConnectionManager\", \"Win32_NetworkManagement_WindowsFilteringPlatform\", \"Win32_NetworkManagement_WindowsFirewall\", \"Win32_NetworkManagement_WindowsNetworkVirtualization\", \"Win32_Networking\", \"Win32_Networking_ActiveDirectory\", \"Win32_Networking_Clustering\", \"Win32_Networking_HttpServer\", \"Win32_Networking_Ldap\", \"Win32_Networking_WebSocket\", \"Win32_Networking_WinHttp\", \"Win32_Networking_WinInet\", \"Win32_Networking_WinSock\", \"Win32_Networking_WindowsWebServices\", \"Win32_Security\", \"Win32_Security_AppLocker\", \"Win32_Security_Authentication\", \"Win32_Security_Authentication_Identity\", \"Win32_Security_Authorization\", \"Win32_Security_Credentials\", \"Win32_Security_Cryptography\", \"Win32_Security_Cryptography_Catalog\", \"Win32_Security_Cryptography_Certificates\", \"Win32_Security_Cryptography_Sip\", \"Win32_Security_Cryptography_UI\", \"Win32_Security_DiagnosticDataQuery\", \"Win32_Security_DirectoryServices\", \"Win32_Security_EnterpriseData\", \"Win32_Security_ExtensibleAuthenticationProtocol\", \"Win32_Security_Isolation\", \"Win32_Security_LicenseProtection\", \"Win32_Security_NetworkAccessProtection\", \"Win32_Security_WinTrust\", \"Win32_Security_WinWlx\", \"Win32_Storage\", \"Win32_Storage_Cabinets\", \"Win32_Storage_CloudFilters\", \"Win32_Storage_Compression\", \"Win32_Storage_DistributedFileSystem\", \"Win32_Storage_FileHistory\", \"Win32_Storage_FileSystem\", \"Win32_Storage_Imapi\", \"Win32_Storage_IndexServer\", \"Win32_Storage_InstallableFileSystems\", \"Win32_Storage_IscsiDisc\", \"Win32_Storage_Jet\", \"Win32_Storage_Nvme\", \"Win32_Storage_OfflineFiles\", \"Win32_Storage_OperationRecorder\", \"Win32_Storage_Packaging\", \"Win32_Storage_Packaging_Appx\", \"Win32_Storage_ProjectedFileSystem\", \"Win32_Storage_StructuredStorage\", \"Win32_Storage_Vhd\", \"Win32_Storage_Xps\", \"Win32_System\", \"Win32_System_AddressBook\", \"Win32_System_Antimalware\", \"Win32_System_ApplicationInstallationAndServicing\", \"Win32_System_ApplicationVerifier\", \"Win32_System_ClrHosting\", \"Win32_System_Com\", \"Win32_System_Com_Marshal\", \"Win32_System_Com_StructuredStorage\", \"Win32_System_Com_Urlmon\", \"Win32_System_ComponentServices\", \"Win32_System_Console\", \"Win32_System_CorrelationVector\", \"Win32_System_DataExchange\", \"Win32_System_DeploymentServices\", \"Win32_System_DeveloperLicensing\", \"Win32_System_Diagnostics\", \"Win32_System_Diagnostics_Ceip\", \"Win32_System_Diagnostics_Debug\", \"Win32_System_Diagnostics_Debug_Extensions\", \"Win32_System_Diagnostics_Etw\", \"Win32_System_Diagnostics_ProcessSnapshotting\", \"Win32_System_Diagnostics_ToolHelp\", \"Win32_System_Diagnostics_TraceLogging\", \"Win32_System_DistributedTransactionCoordinator\", \"Win32_System_Environment\", \"Win32_System_ErrorReporting\", \"Win32_System_EventCollector\", \"Win32_System_EventLog\", \"Win32_System_EventNotificationService\", \"Win32_System_GroupPolicy\", \"Win32_System_HostCompute\", \"Win32_System_HostComputeNetwork\", \"Win32_System_HostComputeSystem\", \"Win32_System_Hypervisor\", \"Win32_System_IO\", \"Win32_System_Iis\", \"Win32_System_Ioctl\", \"Win32_System_JobObjects\", \"Win32_System_Js\", \"Win32_System_Kernel\", \"Win32_System_LibraryLoader\", \"Win32_System_Mailslots\", \"Win32_System_Mapi\", \"Win32_System_Memory\", \"Win32_System_Memory_NonVolatile\", \"Win32_System_MessageQueuing\", \"Win32_System_MixedReality\", \"Win32_System_Ole\", \"Win32_System_PasswordManagement\", \"Win32_System_Performance\", \"Win32_System_Performance_HardwareCounterProfiling\", \"Win32_System_Pipes\", \"Win32_System_Power\", \"Win32_System_ProcessStatus\", \"Win32_System_Recovery\", \"Win32_System_Registry\", \"Win32_System_RemoteDesktop\", \"Win32_System_RemoteManagement\", \"Win32_System_RestartManager\", \"Win32_System_Restore\", \"Win32_System_Rpc\", \"Win32_System_Search\", \"Win32_System_Search_Common\", \"Win32_System_SecurityCenter\", \"Win32_System_Services\", \"Win32_System_SetupAndMigration\", \"Win32_System_Shutdown\", \"Win32_System_StationsAndDesktops\", \"Win32_System_SubsystemForLinux\", \"Win32_System_SystemInformation\", \"Win32_System_SystemServices\", \"Win32_System_Threading\", \"Win32_System_Time\", \"Win32_System_TpmBaseServices\", \"Win32_System_UserAccessLogging\", \"Win32_System_Variant\", \"Win32_System_VirtualDosMachines\", \"Win32_System_WindowsProgramming\", \"Win32_System_Wmi\", \"Win32_UI\", \"Win32_UI_Accessibility\", \"Win32_UI_ColorSystem\", \"Win32_UI_Controls\", \"Win32_UI_Controls_Dialogs\", \"Win32_UI_HiDpi\", \"Win32_UI_Input\", \"Win32_UI_Input_Ime\", \"Win32_UI_Input_KeyboardAndMouse\", \"Win32_UI_Input_Pointer\", \"Win32_UI_Input_Touch\", \"Win32_UI_Input_XboxController\", \"Win32_UI_InteractionContext\", \"Win32_UI_Magnification\", \"Win32_UI_Shell\", \"Win32_UI_Shell_Common\", \"Win32_UI_Shell_PropertiesSystem\", \"Win32_UI_TabletPC\", \"Win32_UI_TextServices\", \"Win32_UI_WindowsAndMessaging\", \"Win32_Web\", \"Win32_Web_InternetExplorer\", \"default\", \"docs\"))",
    "-C",
    "metadata=badd2551c5aed9ed",
    "-C",
    "extra-filename=-318e9bc24ee987c1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--extern",
    "windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_targets-b170585257b0d7b4.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_sys --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=unexpected_cfgs --warn=missing_docs --check-cfg \"cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)\" --cfg \"feature=\\\"Win32\\\"\" --cfg \"feature=\\\"Win32_Foundation\\\"\" --cfg \"feature=\\\"Win32_NetworkManagement\\\"\" --cfg \"feature=\\\"Win32_NetworkManagement_IpHelper\\\"\" --cfg \"feature=\\\"Win32_Networking\\\"\" --cfg \"feature=\\\"Win32_Networking_WinSock\\\"\" --cfg \"feature=\\\"Win32_System\\\"\" --cfg \"feature=\\\"Win32_System_Diagnostics\\\"\" --cfg \"feature=\\\"Win32_System_Diagnostics_Debug\\\"\" --cfg \"feature=\\\"Win32_System_Threading\\\"\" --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"Wdk\\\", \\\"Wdk_Devices\\\", \\\"Wdk_Devices_Bluetooth\\\", \\\"Wdk_Devices_HumanInterfaceDevice\\\", \\\"Wdk_Foundation\\\", \\\"Wdk_Graphics\\\", \\\"Wdk_Graphics_Direct3D\\\", \\\"Wdk_NetworkManagement\\\", \\\"Wdk_NetworkManagement_Ndis\\\", \\\"Wdk_NetworkManagement_WindowsFilteringPlatform\\\", \\\"Wdk_Storage\\\", \\\"Wdk_Storage_FileSystem\\\", \\\"Wdk_Storage_FileSystem_Minifilters\\\", \\\"Wdk_System\\\", \\\"Wdk_System_IO\\\", \\\"Wdk_System_Memory\\\", \\\"Wdk_System_OfflineRegistry\\\", \\\"Wdk_System_Registry\\\", \\\"Wdk_System_SystemInformation\\\", \\\"Wdk_System_SystemServices\\\", \\\"Wdk_System_Threading\\\", \\\"Win32\\\", \\\"Win32_Data\\\", \\\"Win32_Data_HtmlHelp\\\", \\\"Win32_Data_RightsManagement\\\", \\\"Win32_Devices\\\", \\\"Win32_Devices_AllJoyn\\\", \\\"Win32_Devices_BiometricFramework\\\", \\\"Win32_Devices_Bluetooth\\\", \\\"Win32_Devices_Communication\\\", \\\"Win32_Devices_DeviceAndDriverInstallation\\\", \\\"Win32_Devices_DeviceQuery\\\", \\\"Win32_Devices_Display\\\", \\\"Win32_Devices_Enumeration\\\", \\\"Win32_Devices_Enumeration_Pnp\\\", \\\"Win32_Devices_Fax\\\", \\\"Win32_Devices_HumanInterfaceDevice\\\", \\\"Win32_Devices_PortableDevices\\\", \\\"Win32_Devices_Properties\\\", \\\"Win32_Devices_Pwm\\\", \\\"Win32_Devices_Sensors\\\", \\\"Win32_Devices_SerialCommunication\\\", \\\"Win32_Devices_Tapi\\\", \\\"Win32_Devices_Usb\\\", \\\"Win32_Devices_WebServicesOnDevices\\\", \\\"Win32_Foundation\\\", \\\"Win32_Gaming\\\", \\\"Win32_Globalization\\\", \\\"Win32_Graphics\\\", \\\"Win32_Graphics_Dwm\\\", \\\"Win32_Graphics_Gdi\\\", \\\"Win32_Graphics_GdiPlus\\\", \\\"Win32_Graphics_Hlsl\\\", \\\"Win32_Graphics_OpenGL\\\", \\\"Win32_Graphics_Printing\\\", \\\"Win32_Graphics_Printing_PrintTicket\\\", \\\"Win32_Management\\\", \\\"Win32_Management_MobileDeviceManagementRegistration\\\", \\\"Win32_Media\\\", \\\"Win32_Media_Audio\\\", \\\"Win32_Media_DxMediaObjects\\\", \\\"Win32_Media_KernelStreaming\\\", \\\"Win32_Media_Multimedia\\\", \\\"Win32_Media_Streaming\\\", \\\"Win32_Media_WindowsMediaFormat\\\", \\\"Win32_NetworkManagement\\\", \\\"Win32_NetworkManagement_Dhcp\\\", \\\"Win32_NetworkManagement_Dns\\\", \\\"Win32_NetworkManagement_InternetConnectionWizard\\\", \\\"Win32_NetworkManagement_IpHelper\\\", \\\"Win32_NetworkManagement_Multicast\\\", \\\"Win32_NetworkManagement_Ndis\\\", \\\"Win32_NetworkManagement_NetBios\\\", \\\"Win32_NetworkManagement_NetManagement\\\", \\\"Win32_NetworkManagement_NetShell\\\", \\\"Win32_NetworkManagement_NetworkDiagnosticsFramework\\\", \\\"Win32_NetworkManagement_P2P\\\", \\\"Win32_NetworkManagement_QoS\\\", \\\"Win32_NetworkManagement_Rras\\\", \\\"Win32_NetworkManagement_Snmp\\\", \\\"Win32_NetworkManagement_WNet\\\", \\\"Win32_NetworkManagement_WebDav\\\", \\\"Win32_NetworkManagement_WiFi\\\", \\\"Win32_NetworkManagement_WindowsConnectionManager\\\", \\\"Win32_NetworkManagement_WindowsFilteringPlatform\\\", \\\"Win32_NetworkManagement_WindowsFirewall\\\", \\\"Win32_NetworkManagement_WindowsNetworkVirtualization\\\", \\\"Win32_Networking\\\", \\\"Win32_Networking_ActiveDirectory\\\", \\\"Win32_Networking_Clustering\\\", \\\"Win32_Networking_HttpServer\\\", \\\"Win32_Networking_Ldap\\\", \\\"Win32_Networking_WebSocket\\\", \\\"Win32_Networking_WinHttp\\\", \\\"Win32_Networking_WinInet\\\", \\\"Win32_Networking_WinSock\\\", \\\"Win32_Networking_WindowsWebServices\\\", \\\"Win32_Security\\\", \\\"Win32_Security_AppLocker\\\", \\\"Win32_Security_Authentication\\\", \\\"Win32_Security_Authentication_Identity\\\", \\\"Win32_Security_Authorization\\\", \\\"Win32_Security_Credentials\\\", \\\"Win32_Security_Cryptography\\\", \\\"Win32_Security_Cryptography_Catalog\\\", \\\"Win32_Security_Cryptography_Certificates\\\", \\\"Win32_Security_Cryptography_Sip\\\", \\\"Win32_Security_Cryptography_UI\\\", \\\"Win32_Security_DiagnosticDataQuery\\\", \\\"Win32_Security_DirectoryServices\\\", \\\"Win32_Security_EnterpriseData\\\", \\\"Win32_Security_ExtensibleAuthenticationProtocol\\\", \\\"Win32_Security_Isolation\\\", \\\"Win32_Security_LicenseProtection\\\", \\\"Win32_Security_NetworkAccessProtection\\\", \\\"Win32_Security_WinTrust\\\", \\\"Win32_Security_WinWlx\\\", \\\"Win32_Storage\\\", \\\"Win32_Storage_Cabinets\\\", \\\"Win32_Storage_CloudFilters\\\", \\\"Win32_Storage_Compression\\\", \\\"Win32_Storage_DistributedFileSystem\\\", \\\"Win32_Storage_FileHistory\\\", \\\"Win32_Storage_FileSystem\\\", \\\"Win32_Storage_Imapi\\\", \\\"Win32_Storage_IndexServer\\\", \\\"Win32_Storage_InstallableFileSystems\\\", \\\"Win32_Storage_IscsiDisc\\\", \\\"Win32_Storage_Jet\\\", \\\"Win32_Storage_Nvme\\\", \\\"Win32_Storage_OfflineFiles\\\", \\\"Win32_Storage_OperationRecorder\\\", \\\"Win32_Storage_Packaging\\\", \\\"Win32_Storage_Packaging_Appx\\\", \\\"Win32_Storage_ProjectedFileSystem\\\", \\\"Win32_Storage_StructuredStorage\\\", \\\"Win32_Storage_Vhd\\\", \\\"Win32_Storage_Xps\\\", \\\"Win32_System\\\", \\\"Win32_System_AddressBook\\\", \\\"Win32_System_Antimalware\\\", \\\"Win32_System_ApplicationInstallationAndServicing\\\", \\\"Win32_System_ApplicationVerifier\\\", \\\"Win32_System_ClrHosting\\\", \\\"Win32_System_Com\\\", \\\"Win32_System_Com_Marshal\\\", \\\"Win32_System_Com_StructuredStorage\\\", \\\"Win32_System_Com_Urlmon\\\", \\\"Win32_System_ComponentServices\\\", \\\"Win32_System_Console\\\", \\\"Win32_System_CorrelationVector\\\", \\\"Win32_System_DataExchange\\\", \\\"Win32_System_DeploymentServices\\\", \\\"Win32_System_DeveloperLicensing\\\", \\\"Win32_System_Diagnostics\\\", \\\"Win32_System_Diagnostics_Ceip\\\", \\\"Win32_System_Diagnostics_Debug\\\", \\\"Win32_System_Diagnostics_Debug_Extensions\\\", \\\"Win32_System_Diagnostics_Etw\\\", \\\"Win32_System_Diagnostics_ProcessSnapshotting\\\", \\\"Win32_System_Diagnostics_ToolHelp\\\", \\\"Win32_System_Diagnostics_TraceLogging\\\", \\\"Win32_System_DistributedTransactionCoordinator\\\", \\\"Win32_System_Environment\\\", \\\"Win32_System_ErrorReporting\\\", \\\"Win32_System_EventCollector\\\", \\\"Win32_System_EventLog\\\", \\\"Win32_System_EventNotificationService\\\", \\\"Win32_System_GroupPolicy\\\", \\\"Win32_System_HostCompute\\\", \\\"Win32_System_HostComputeNetwork\\\", \\\"Win32_System_HostComputeSystem\\\", \\\"Win32_System_Hypervisor\\\", \\\"Win32_System_IO\\\", \\\"Win32_System_Iis\\\", \\\"Win32_System_Ioctl\\\", \\\"Win32_System_JobObjects\\\", \\\"Win32_System_Js\\\", \\\"Win32_System_Kernel\\\", \\\"Win32_System_LibraryLoader\\\", \\\"Win32_System_Mailslots\\\", \\\"Win32_System_Mapi\\\", \\\"Win32_System_Memory\\\", \\\"Win32_System_Memory_NonVolatile\\\", \\\"Win32_System_MessageQueuing\\\", \\\"Win32_System_MixedReality\\\", \\\"Win32_System_Ole\\\", \\\"Win32_System_PasswordManagement\\\", \\\"Win32_System_Performance\\\", \\\"Win32_System_Performance_HardwareCounterProfiling\\\", \\\"Win32_System_Pipes\\\", \\\"Win32_System_Power\\\", \\\"Win32_System_ProcessStatus\\\", \\\"Win32_System_Recovery\\\", \\\"Win32_System_Registry\\\", \\\"Win32_System_RemoteDesktop\\\", \\\"Win32_System_RemoteManagement\\\", \\\"Win32_System_RestartManager\\\", \\\"Win32_System_Restore\\\", \\\"Win32_System_Rpc\\\", \\\"Win32_System_Search\\\", \\\"Win32_System_Search_Common\\\", \\\"Win32_System_SecurityCenter\\\", \\\"Win32_System_Services\\\", \\\"Win32_System_SetupAndMigration\\\", \\\"Win32_System_Shutdown\\\", \\\"Win32_System_StationsAndDesktops\\\", \\\"Win32_System_SubsystemForLinux\\\", \\\"Win32_System_SystemInformation\\\", \\\"Win32_System_SystemServices\\\", \\\"Win32_System_Threading\\\", \\\"Win32_System_Time\\\", \\\"Win32_System_TpmBaseServices\\\", \\\"Win32_System_UserAccessLogging\\\", \\\"Win32_System_Variant\\\", \\\"Win32_System_VirtualDosMachines\\\", \\\"Win32_System_WindowsProgramming\\\", \\\"Win32_System_Wmi\\\", \\\"Win32_UI\\\", \\\"Win32_UI_Accessibility\\\", \\\"Win32_UI_ColorSystem\\\", \\\"Win32_UI_Controls\\\", \\\"Win32_UI_Controls_Dialogs\\\", \\\"Win32_UI_HiDpi\\\", \\\"Win32_UI_Input\\\", \\\"Win32_UI_Input_Ime\\\", \\\"Win32_UI_Input_KeyboardAndMouse\\\", \\\"Win32_UI_Input_Pointer\\\", \\\"Win32_UI_Input_Touch\\\", \\\"Win32_UI_Input_XboxController\\\", \\\"Win32_UI_InteractionContext\\\", \\\"Win32_UI_Magnification\\\", \\\"Win32_UI_Shell\\\", \\\"Win32_UI_Shell_Common\\\", \\\"Win32_UI_Shell_PropertiesSystem\\\", \\\"Win32_UI_TabletPC\\\", \\\"Win32_UI_TextServices\\\", \\\"Win32_UI_WindowsAndMessaging\\\", \\\"Win32_Web\\\", \\\"Win32_Web_InternetExplorer\\\", \\\"default\\\", \\\"docs\\\"))\" -C metadata=badd2551c5aed9ed -C extra-filename=-318e9bc24ee987c1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --extern windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_targets-b170585257b0d7b4.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_sys",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--warn=rust_2018_idioms",
    "--warn=unexpected_cfgs",
    "--warn=missing_docs",
    "--check-cfg",
    "cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)",
    "--cfg",
    "feature=\"Win32\"",
    "--cfg",
    "feature=\"Win32_Foundation\"",
    "--cfg",
    "feature=\"Win32_NetworkManagement\"",
    "--cfg",
    "feature=\"Win32_NetworkManagement_IpHelper\"",
    "--cfg",
    "feature=\"Win32_Networking\"",
    "--cfg",
    "feature=\"Win32_Networking_WinSock\"",
    "--cfg",
    "feature=\"Win32_System\"",
    "--cfg",
    "feature=\"Win32_System_Diagnostics\"",
    "--cfg",
    "feature=\"Win32_System_Diagnostics_Debug\"",
    "--cfg",
    "feature=\"Win32_System_Threading\"",
    "--cfg",
    "feature=\"default\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"Wdk\", \"Wdk_Devices\", \"Wdk_Devices_Bluetooth\", \"Wdk_Devices_HumanInterfaceDevice\", \"Wdk_Foundation\", \"Wdk_Graphics\", \"Wdk_Graphics_Direct3D\", \"Wdk_NetworkManagement\", \"Wdk_NetworkManagement_Ndis\", \"Wdk_NetworkManagement_WindowsFilteringPlatform\", \"Wdk_Storage\", \"Wdk_Storage_FileSystem\", \"Wdk_Storage_FileSystem_Minifilters\", \"Wdk_System\", \"Wdk_System_IO\", \"Wdk_System_Memory\", \"Wdk_System_OfflineRegistry\", \"Wdk_System_Registry\", \"Wdk_System_SystemInformation\", \"Wdk_System_SystemServices\", \"Wdk_System_Threading\", \"Win32\", \"Win32_Data\", \"Win32_Data_HtmlHelp\", \"Win32_Data_RightsManagement\", \"Win32_Devices\", \"Win32_Devices_AllJoyn\", \"Win32_Devices_BiometricFramework\", \"Win32_Devices_Bluetooth\", \"Win32_Devices_Communication\", \"Win32_Devices_DeviceAndDriverInstallation\", \"Win32_Devices_DeviceQuery\", \"Win32_Devices_Display\", \"Win32_Devices_Enumeration\", \"Win32_Devices_Enumeration_Pnp\", \"Win32_Devices_Fax\", \"Win32_Devices_HumanInterfaceDevice\", \"Win32_Devices_PortableDevices\", \"Win32_Devices_Properties\", \"Win32_Devices_Pwm\", \"Win32_Devices_Sensors\", \"Win32_Devices_SerialCommunication\", \"Win32_Devices_Tapi\", \"Win32_Devices_Usb\", \"Win32_Devices_WebServicesOnDevices\", \"Win32_Foundation\", \"Win32_Gaming\", \"Win32_Globalization\", \"Win32_Graphics\", \"Win32_Graphics_Dwm\", \"Win32_Graphics_Gdi\", \"Win32_Graphics_GdiPlus\", \"Win32_Graphics_Hlsl\", \"Win32_Graphics_OpenGL\", \"Win32_Graphics_Printing\", \"Win32_Graphics_Printing_PrintTicket\", \"Win32_Management\", \"Win32_Management_MobileDeviceManagementRegistration\", \"Win32_Media\", \"Win32_Media_Audio\", \"Win32_Media_DxMediaObjects\", \"Win32_Media_KernelStreaming\", \"Win32_Media_Multimedia\", \"Win32_Media_Streaming\", \"Win32_Media_WindowsMediaFormat\", \"Win32_NetworkManagement\", \"Win32_NetworkManagement_Dhcp\", \"Win32_NetworkManagement_Dns\", \"Win32_NetworkManagement_InternetConnectionWizard\", \"Win32_NetworkManagement_IpHelper\", \"Win32_NetworkManagement_Multicast\", \"Win32_NetworkManagement_Ndis\", \"Win32_NetworkManagement_NetBios\", \"Win32_NetworkManagement_NetManagement\", \"Win32_NetworkManagement_NetShell\", \"Win32_NetworkManagement_NetworkDiagnosticsFramework\", \"Win32_NetworkManagement_P2P\", \"Win32_NetworkManagement_QoS\", \"Win32_NetworkManagement_Rras\", \"Win32_NetworkManagement_Snmp\", \"Win32_NetworkManagement_WNet\", \"Win32_NetworkManagement_WebDav\", \"Win32_NetworkManagement_WiFi\", \"Win32_NetworkManagement_WindowsConnectionManager\", \"Win32_NetworkManagement_WindowsFilteringPlatform\", \"Win32_NetworkManagement_WindowsFirewall\", \"Win32_NetworkManagement_WindowsNetworkVirtualization\", \"Win32_Networking\", \"Win32_Networking_ActiveDirectory\", \"Win32_Networking_Clustering\", \"Win32_Networking_HttpServer\", \"Win32_Networking_Ldap\", \"Win32_Networking_WebSocket\", \"Win32_Networking_WinHttp\", \"Win32_Networking_WinInet\", \"Win32_Networking_WinSock\", \"Win32_Networking_WindowsWebServices\", \"Win32_Security\", \"Win32_Security_AppLocker\", \"Win32_Security_Authentication\", \"Win32_Security_Authentication_Identity\", \"Win32_Security_Authorization\", \"Win32_Security_Credentials\", \"Win32_Security_Cryptography\", \"Win32_Security_Cryptography_Catalog\", \"Win32_Security_Cryptography_Certificates\", \"Win32_Security_Cryptography_Sip\", \"Win32_Security_Cryptography_UI\", \"Win32_Security_DiagnosticDataQuery\", \"Win32_Security_DirectoryServices\", \"Win32_Security_EnterpriseData\", \"Win32_Security_ExtensibleAuthenticationProtocol\", \"Win32_Security_Isolation\", \"Win32_Security_LicenseProtection\", \"Win32_Security_NetworkAccessProtection\", \"Win32_Security_WinTrust\", \"Win32_Security_WinWlx\", \"Win32_Storage\", \"Win32_Storage_Cabinets\", \"Win32_Storage_CloudFilters\", \"Win32_Storage_Compression\", \"Win32_Storage_DistributedFileSystem\", \"Win32_Storage_FileHistory\", \"Win32_Storage_FileSystem\", \"Win32_Storage_Imapi\", \"Win32_Storage_IndexServer\", \"Win32_Storage_InstallableFileSystems\", \"Win32_Storage_IscsiDisc\", \"Win32_Storage_Jet\", \"Win32_Storage_Nvme\", \"Win32_Storage_OfflineFiles\", \"Win32_Storage_OperationRecorder\", \"Win32_Storage_Packaging\", \"Win32_Storage_Packaging_Appx\", \"Win32_Storage_ProjectedFileSystem\", \"Win32_Storage_StructuredStorage\", \"Win32_Storage_Vhd\", \"Win32_Storage_Xps\", \"Win32_System\", \"Win32_System_AddressBook\", \"Win32_System_Antimalware\", \"Win32_System_ApplicationInstallationAndServicing\", \"Win32_System_ApplicationVerifier\", \"Win32_System_ClrHosting\", \"Win32_System_Com\", \"Win32_System_Com_Marshal\", \"Win32_System_Com_StructuredStorage\", \"Win32_System_Com_Urlmon\", \"Win32_System_ComponentServices\", \"Win32_System_Console\", \"Win32_System_CorrelationVector\", \"Win32_System_DataExchange\", \"Win32_System_DeploymentServices\", \"Win32_System_DeveloperLicensing\", \"Win32_System_Diagnostics\", \"Win32_System_Diagnostics_Ceip\", \"Win32_System_Diagnostics_Debug\", \"Win32_System_Diagnostics_Debug_Extensions\", \"Win32_System_Diagnostics_Etw\", \"Win32_System_Diagnostics_ProcessSnapshotting\", \"Win32_System_Diagnostics_ToolHelp\", \"Win32_System_Diagnostics_TraceLogging\", \"Win32_System_DistributedTransactionCoordinator\", \"Win32_System_Environment\", \"Win32_System_ErrorReporting\", \"Win32_System_EventCollector\", \"Win32_System_EventLog\", \"Win32_System_EventNotificationService\", \"Win32_System_GroupPolicy\", \"Win32_System_HostCompute\", \"Win32_System_HostComputeNetwork\", \"Win32_System_HostComputeSystem\", \"Win32_System_Hypervisor\", \"Win32_System_IO\", \"Win32_System_Iis\", \"Win32_System_Ioctl\", \"Win32_System_JobObjects\", \"Win32_System_Js\", \"Win32_System_Kernel\", \"Win32_System_LibraryLoader\", \"Win32_System_Mailslots\", \"Win32_System_Mapi\", \"Win32_System_Memory\", \"Win32_System_Memory_NonVolatile\", \"Win32_System_MessageQueuing\", \"Win32_System_MixedReality\", \"Win32_System_Ole\", \"Win32_System_PasswordManagement\", \"Win32_System_Performance\", \"Win32_System_Performance_HardwareCounterProfiling\", \"Win32_System_Pipes\", \"Win32_System_Power\", \"Win32_System_ProcessStatus\", \"Win32_System_Recovery\", \"Win32_System_Registry\", \"Win32_System_RemoteDesktop\", \"Win32_System_RemoteManagement\", \"Win32_System_RestartManager\", \"Win32_System_Restore\", \"Win32_System_Rpc\", \"Win32_System_Search\", \"Win32_System_Search_Common\", \"Win32_System_SecurityCenter\", \"Win32_System_Services\", \"Win32_System_SetupAndMigration\", \"Win32_System_Shutdown\", \"Win32_System_StationsAndDesktops\", \"Win32_System_SubsystemForLinux\", \"Win32_System_SystemInformation\", \"Win32_System_SystemServices\", \"Win32_System_Threading\", \"Win32_System_Time\", \"Win32_System_TpmBaseServices\", \"Win32_System_UserAccessLogging\", \"Win32_System_Variant\", \"Win32_System_VirtualDosMachines\", \"Win32_System_WindowsProgramming\", \"Win32_System_Wmi\", \"Win32_UI\", \"Win32_UI_Accessibility\", \"Win32_UI_ColorSystem\", \"Win32_UI_Controls\", \"Win32_UI_Controls_Dialogs\", \"Win32_UI_HiDpi\", \"Win32_UI_Input\", \"Win32_UI_Input_Ime\", \"Win32_UI_Input_KeyboardAndMouse\", \"Win32_UI_Input_Pointer\", \"Win32_UI_Input_Touch\", \"Win32_UI_Input_XboxController\", \"Win32_UI_InteractionContext\", \"Win32_UI_Magnification\", \"Win32_UI_Shell\", \"Win32_UI_Shell_Common\", \"Win32_UI_Shell_PropertiesSystem\", \"Win32_UI_TabletPC\", \"Win32_UI_TextServices\", \"Win32_UI_WindowsAndMessaging\", \"Win32_Web\", \"Win32_Web_InternetExplorer\", \"default\", \"docs\"))",
    "-C",
    "metadata=badd2551c5aed9ed",
    "-C",
    "extra-filename=-318e9bc24ee987c1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--extern",
    "windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_targets-b170585257b0d7b4.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:17.047169+00:00",
  "end_time": "2026-07-13T14:49:17.756696+00:00",
  "start_unix_nanos": 1783954157047169300,
  "end_unix_nanos": 1783954157756695600,
  "crate_name": "windows_sys",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 3216,
  "ppid": 8804,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-type=rlib",
    "--emit=metadata",
    "--target",
    "x86_64-pc-windows-msvc",
    "-o",
    "-",
    "-"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-type=rlib --emit=metadata --target x86_64-pc-windows-msvc -o - -",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-type=rlib",
    "--emit=metadata",
    "--target",
    "x86_64-pc-windows-msvc",
    "-o",
    "-",
    "-"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:17.369683+00:00",
  "end_time": "2026-07-13T14:49:17.406722+00:00",
  "start_unix_nanos": 1783954157369683100,
  "end_unix_nanos": 1783954157406721600,
  "crate_name": null,
  "crate_type": [
    "rlib"
  ],
  "out_dir": null
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 12656,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "errno",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10\\src\\lib.rs",
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
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=d9f10fd880b36604",
    "-C",
    "extra-filename=-405a592150f745eb",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--extern",
    "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name errno --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=d9f10fd880b36604 -C extra-filename=-405a592150f745eb --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --extern windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "errno",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10\\src\\lib.rs",
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
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=d9f10fd880b36604",
    "-C",
    "extra-filename=-405a592150f745eb",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--extern",
    "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta",
    "--cap-lints",
    "allow",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:17.702375+00:00",
  "end_time": "2026-07-13T14:49:17.841838+00:00",
  "start_unix_nanos": 1783954157702375500,
  "end_unix_nanos": 1783954157841838300,
  "crate_name": "errno",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
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
  "run_id": "rustix:0.38.44:13136",
  "root_process_pid": 2908,
  "pid": 16364,
  "ppid": 10292,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "rustix",
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
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(alloc_c_string)",
    "--check-cfg",
    "cfg(alloc_ffi)",
    "--check-cfg",
    "cfg(apple)",
    "--check-cfg",
    "cfg(asm_experimental_arch)",
    "--check-cfg",
    "cfg(bsd)",
    "--check-cfg",
    "cfg(core_c_str)",
    "--check-cfg",
    "cfg(core_ffi_c)",
    "--check-cfg",
    "cfg(core_intrinsics)",
    "--check-cfg",
    "cfg(criterion)",
    "--check-cfg",
    "cfg(document_experimental_runtime_api)",
    "--check-cfg",
    "cfg(fix_y2038)",
    "--check-cfg",
    "cfg(freebsdlike)",
    "--check-cfg",
    "cfg(libc)",
    "--check-cfg",
    "cfg(linux_kernel)",
    "--check-cfg",
    "cfg(linux_like)",
    "--check-cfg",
    "cfg(linux_raw)",
    "--check-cfg",
    "cfg(netbsdlike)",
    "--check-cfg",
    "cfg(rustc_attrs)",
    "--check-cfg",
    "cfg(solarish)",
    "--check-cfg",
    "cfg(staged_api)",
    "--check-cfg",
    "cfg(static_assertions)",
    "--check-cfg",
    "cfg(thumb_mode)",
    "--check-cfg",
    "cfg(wasi)",
    "--check-cfg",
    "cfg(wasi_ext)",
    "--check-cfg",
    "cfg(target_arch, values(\"xtensa\"))",
    "--cfg",
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"libc-extra-traits\"",
    "--cfg",
    "feature=\"std\"",
    "--cfg",
    "feature=\"use-libc-auxv\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"all-apis\", \"alloc\", \"cc\", \"compiler_builtins\", \"core\", \"default\", \"event\", \"fs\", \"io_uring\", \"itoa\", \"libc\", \"libc-extra-traits\", \"libc_errno\", \"linux_4_11\", \"linux_latest\", \"mm\", \"mount\", \"net\", \"once_cell\", \"param\", \"pipe\", \"process\", \"procfs\", \"pty\", \"rand\", \"runtime\", \"rustc-dep-of-std\", \"rustc-std-workspace-alloc\", \"shm\", \"std\", \"stdio\", \"system\", \"termios\", \"thread\", \"time\", \"try_close\", \"use-explicitly-provided-auxv\", \"use-libc\", \"use-libc-auxv\"))",
    "-C",
    "metadata=764e1e143a9009b6",
    "-C",
    "extra-filename=-4bf43304fd3c21e8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--extern",
    "bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libbitflags-4db8ea0490b59b49.rmeta",
    "--extern",
    "libc_errno=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\liberrno-405a592150f745eb.rmeta",
    "--extern",
    "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
    "--cfg",
    "static_assertions",
    "--cfg",
    "libc"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name rustix --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg cfg(apple) --check-cfg cfg(asm_experimental_arch) --check-cfg cfg(bsd) --check-cfg cfg(core_c_str) --check-cfg cfg(core_ffi_c) --check-cfg cfg(core_intrinsics) --check-cfg cfg(criterion) --check-cfg cfg(document_experimental_runtime_api) --check-cfg cfg(fix_y2038) --check-cfg cfg(freebsdlike) --check-cfg cfg(libc) --check-cfg cfg(linux_kernel) --check-cfg cfg(linux_like) --check-cfg cfg(linux_raw) --check-cfg cfg(netbsdlike) --check-cfg cfg(rustc_attrs) --check-cfg cfg(solarish) --check-cfg cfg(staged_api) --check-cfg cfg(static_assertions) --check-cfg cfg(thumb_mode) --check-cfg cfg(wasi) --check-cfg cfg(wasi_ext) --check-cfg \"cfg(target_arch, values(\\\"xtensa\\\"))\" --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"libc-extra-traits\\\"\" --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"use-libc-auxv\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"all-apis\\\", \\\"alloc\\\", \\\"cc\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"event\\\", \\\"fs\\\", \\\"io_uring\\\", \\\"itoa\\\", \\\"libc\\\", \\\"libc-extra-traits\\\", \\\"libc_errno\\\", \\\"linux_4_11\\\", \\\"linux_latest\\\", \\\"mm\\\", \\\"mount\\\", \\\"net\\\", \\\"once_cell\\\", \\\"param\\\", \\\"pipe\\\", \\\"process\\\", \\\"procfs\\\", \\\"pty\\\", \\\"rand\\\", \\\"runtime\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-alloc\\\", \\\"shm\\\", \\\"std\\\", \\\"stdio\\\", \\\"system\\\", \\\"termios\\\", \\\"thread\\\", \\\"time\\\", \\\"try_close\\\", \\\"use-explicitly-provided-auxv\\\", \\\"use-libc\\\", \\\"use-libc-auxv\\\"))\" -C metadata=764e1e143a9009b6 -C extra-filename=-4bf43304fd3c21e8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --extern bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libbitflags-4db8ea0490b59b49.rmeta --extern libc_errno=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\liberrno-405a592150f745eb.rmeta --extern windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib --cfg static_assertions --cfg libc",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "rustix",
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
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(alloc_c_string)",
    "--check-cfg",
    "cfg(alloc_ffi)",
    "--check-cfg",
    "cfg(apple)",
    "--check-cfg",
    "cfg(asm_experimental_arch)",
    "--check-cfg",
    "cfg(bsd)",
    "--check-cfg",
    "cfg(core_c_str)",
    "--check-cfg",
    "cfg(core_ffi_c)",
    "--check-cfg",
    "cfg(core_intrinsics)",
    "--check-cfg",
    "cfg(criterion)",
    "--check-cfg",
    "cfg(document_experimental_runtime_api)",
    "--check-cfg",
    "cfg(fix_y2038)",
    "--check-cfg",
    "cfg(freebsdlike)",
    "--check-cfg",
    "cfg(libc)",
    "--check-cfg",
    "cfg(linux_kernel)",
    "--check-cfg",
    "cfg(linux_like)",
    "--check-cfg",
    "cfg(linux_raw)",
    "--check-cfg",
    "cfg(netbsdlike)",
    "--check-cfg",
    "cfg(rustc_attrs)",
    "--check-cfg",
    "cfg(solarish)",
    "--check-cfg",
    "cfg(staged_api)",
    "--check-cfg",
    "cfg(static_assertions)",
    "--check-cfg",
    "cfg(thumb_mode)",
    "--check-cfg",
    "cfg(wasi)",
    "--check-cfg",
    "cfg(wasi_ext)",
    "--check-cfg",
    "cfg(target_arch, values(\"xtensa\"))",
    "--cfg",
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"libc-extra-traits\"",
    "--cfg",
    "feature=\"std\"",
    "--cfg",
    "feature=\"use-libc-auxv\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"all-apis\", \"alloc\", \"cc\", \"compiler_builtins\", \"core\", \"default\", \"event\", \"fs\", \"io_uring\", \"itoa\", \"libc\", \"libc-extra-traits\", \"libc_errno\", \"linux_4_11\", \"linux_latest\", \"mm\", \"mount\", \"net\", \"once_cell\", \"param\", \"pipe\", \"process\", \"procfs\", \"pty\", \"rand\", \"runtime\", \"rustc-dep-of-std\", \"rustc-std-workspace-alloc\", \"shm\", \"std\", \"stdio\", \"system\", \"termios\", \"thread\", \"time\", \"try_close\", \"use-explicitly-provided-auxv\", \"use-libc\", \"use-libc-auxv\"))",
    "-C",
    "metadata=764e1e143a9009b6",
    "-C",
    "extra-filename=-4bf43304fd3c21e8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
    "--extern",
    "bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libbitflags-4db8ea0490b59b49.rmeta",
    "--extern",
    "libc_errno=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\liberrno-405a592150f745eb.rmeta",
    "--extern",
    "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
    "--cfg",
    "static_assertions",
    "--cfg",
    "libc"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:49:17.768754+00:00",
  "end_time": "2026-07-13T14:49:18.071309+00:00",
  "start_unix_nanos": 1783954157768753500,
  "end_unix_nanos": 1783954158071309100,
  "crate_name": "rustix",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:49:18.997113+00:00",
  "crate": "rustix",
  "version": "0.38.44",
  "duration_seconds": 26.552971499972045,
  "trace_record_count": 22,
  "trace_owner_summary": {
    "owner_package_count": 111,
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
        "version": "0.2.99",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.99",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.99",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.99/Cargo.toml"
      },
      {
        "crate": "winapi-i686-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_gnullvm",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnullvm",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-backend",
        "version": "0.2.99",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.99",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.99",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.99/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnullvm",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-shared",
        "version": "0.2.99",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.99",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.99",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.99/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro",
        "version": "0.2.99",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.99",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.99",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.99/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6/Cargo.toml"
      },
      {
        "crate": "serial_test_derive",
        "version": "2.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serial_test_derive@2.0.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serial_test_derive-2.0.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serial_test_derive-2.0.0/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "futures-executor",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-executor@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-executor-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-executor-0.3.31/Cargo.toml"
      },
      {
        "crate": "parking_lot_core",
        "version": "0.9.10",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot_core@0.9.10",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.10",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.10/Cargo.toml"
      },
      {
        "crate": "pin-project-lite",
        "version": "0.2.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.16",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.16",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.16/Cargo.toml"
      },
      {
        "crate": "static_assertions",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#static_assertions@1.1.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/static_assertions-1.1.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/static_assertions-1.1.0/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6/Cargo.toml"
      },
      {
        "crate": "crossbeam-epoch",
        "version": "0.9.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.18",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.18",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.18/Cargo.toml"
      },
      {
        "crate": "crossbeam-utils",
        "version": "0.8.21",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.21",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.21",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.21/Cargo.toml"
      },
      {
        "crate": "futures-channel",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-channel@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-channel-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-channel-0.3.31/Cargo.toml"
      },
      {
        "crate": "plotters-backend",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6/Cargo.toml"
      },
      {
        "crate": "crossbeam-deque",
        "version": "0.8.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.6/Cargo.toml"
      },
      {
        "crate": "criterion-plot",
        "version": "0.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.5.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0/Cargo.toml"
      },
      {
        "crate": "linux-raw-sys",
        "version": "0.4.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.15",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.14",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.14",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.14/Cargo.toml"
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
        "crate": "redox_syscall",
        "version": "0.5.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.5.8",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/redox_syscall-0.5.8",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/redox_syscall-0.5.8/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen",
        "version": "0.2.99",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.99",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.99",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.99/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3/Cargo.toml"
      },
      {
        "crate": "os_str_bytes",
        "version": "6.6.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#os_str_bytes@6.6.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/os_str_bytes-6.6.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/os_str_bytes-6.6.1/Cargo.toml"
      },
      {
        "crate": "parking_lot",
        "version": "0.12.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot@0.12.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.3/Cargo.toml"
      },
      {
        "crate": "plotters-svg",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.92",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.92",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.92",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.92/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.135",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.135",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.135",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.135/Cargo.toml"
      },
      {
        "crate": "tinytemplate",
        "version": "1.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.59.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml"
      },
      {
        "crate": "ciborium-io",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-io@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.2/Cargo.toml"
      },
      {
        "crate": "ciborium-ll",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-ll@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.2/Cargo.toml"
      },
      {
        "crate": "futures-io",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.31/Cargo.toml"
      },
      {
        "crate": "hermit-abi",
        "version": "0.1.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19/Cargo.toml"
      },
      {
        "crate": "lazy_static",
        "version": "1.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml"
      },
      {
        "crate": "miniz_oxide",
        "version": "0.8.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#miniz_oxide@0.8.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/miniz_oxide-0.8.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/miniz_oxide-0.8.2/Cargo.toml"
      },
      {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/Cargo.toml"
      },
      {
        "crate": "rayon-core",
        "version": "1.12.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.12.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.1/Cargo.toml"
      },
      {
        "crate": "serial_test",
        "version": "2.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serial_test@2.0.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serial_test-2.0.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serial_test-2.0.0/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.9/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.15",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.15",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.15/Cargo.toml"
      },
      {
        "crate": "hashbrown",
        "version": "0.12.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.12.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/Cargo.toml"
      },
      {
        "crate": "hashbrown",
        "version": "0.14.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.14.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.14.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.14.5/Cargo.toml"
      },
      {
        "crate": "itertools",
        "version": "0.10.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.20.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.20.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2/Cargo.toml"
      },
      {
        "crate": "scopeguard",
        "version": "1.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml"
      },
      {
        "crate": "crc32fast",
        "version": "1.4.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crc32fast@1.4.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crc32fast-1.4.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crc32fast-1.4.2/Cargo.toml"
      },
      {
        "crate": "criterion",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.4.0/Cargo.toml"
      },
      {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lock_api@0.4.12",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.12",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.12/Cargo.toml"
      },
      {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.1/Cargo.toml"
      },
      {
        "crate": "oorandom",
        "version": "11.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.4/Cargo.toml"
      },
      {
        "crate": "pin-utils",
        "version": "0.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-utils@0.1.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-utils-0.1.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-utils-0.1.0/Cargo.toml"
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
        "version": "1.13.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#smallvec@1.13.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smallvec-1.13.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/smallvec-1.13.2/Cargo.toml"
      },
      {
        "crate": "tempfile",
        "version": "3.15.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tempfile@3.15.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.15.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.15.0/Cargo.toml"
      },
      {
        "crate": "textwrap",
        "version": "0.16.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.16.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.16.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.16.1/Cargo.toml"
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
        "version": "2.6.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.6.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.6.0/Cargo.toml"
      },
      {
        "crate": "bumpalo",
        "version": "3.16.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.16.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.16.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.16.0/Cargo.toml"
      },
      {
        "crate": "ciborium",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.2/Cargo.toml"
      },
      {
        "crate": "clap_lex",
        "version": "0.2.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_lex@0.2.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.2.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.2.4/Cargo.toml"
      },
      {
        "crate": "fastrand",
        "version": "2.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0/Cargo.toml"
      },
      {
        "crate": "futures",
        "version": "0.3.31",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures@0.3.31",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.31",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.31/Cargo.toml"
      },
      {
        "crate": "indexmap",
        "version": "1.9.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@1.9.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3/Cargo.toml"
      },
      {
        "crate": "plotters",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7/Cargo.toml"
      },
      {
        "crate": "rustix",
        "version": "0.38.43",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.43",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.43",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.43/Cargo.toml"
      },
      {
        "crate": "web-sys",
        "version": "0.3.76",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.76",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.76",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.76/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.4.0/Cargo.toml"
      },
      {
        "crate": "crunchy",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crunchy@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crunchy-0.2.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crunchy-0.2.2/Cargo.toml"
      },
      {
        "crate": "dashmap",
        "version": "5.5.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#dashmap@5.5.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dashmap-5.5.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dashmap-5.5.3/Cargo.toml"
      },
      {
        "crate": "either",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.13.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.13.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.13.0/Cargo.toml"
      },
      {
        "crate": "flate2",
        "version": "1.0.35",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#flate2@1.0.35",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/flate2-1.0.35",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/flate2-1.0.35/Cargo.toml"
      },
      {
        "crate": "js-sys",
        "version": "0.3.76",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.76",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.76",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.76/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217/Cargo.toml"
      },
      {
        "crate": "walkdir",
        "version": "2.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0/Cargo.toml"
      },
      {
        "crate": "adler2",
        "version": "2.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#adler2@2.0.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/adler2-2.0.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/adler2-2.0.0/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml"
      },
      {
        "crate": "errno",
        "version": "0.3.10",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.10",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.10",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.10/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.7.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.38",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38/Cargo.toml"
      },
      {
        "crate": "rayon",
        "version": "1.10.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.10.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.10.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.10.0/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.11.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.11.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "atty",
        "version": "0.2.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14/Cargo.toml"
      },
      {
        "crate": "clap",
        "version": "3.2.25",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@3.2.25",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-3.2.25",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-3.2.25/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14/Cargo.toml"
      },
      {
        "crate": "anes",
        "version": "0.1.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#anes@0.1.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6/Cargo.toml"
      },
      {
        "crate": "cast",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml"
      },
      {
        "crate": "half",
        "version": "2.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@2.4.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-2.4.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-2.4.1/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.22",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.22",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.22/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.18",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.18",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.18/Cargo.toml"
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
        "version": "2.0.95",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.95",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.95",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.95/Cargo.toml"
      },
      {
        "crate": "rustix",
        "version": "0.38.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44/Cargo.toml"
      }
    ],
    "attributed_event_count": 19,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
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
        "crate": "rustix",
        "version": "0.38.44",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#adler2@2.0.0",
          "name": "adler2",
          "version": "2.0.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler2-2.0.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\adler2-2.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
          "name": "aho-corasick",
          "version": "1.1.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#anes@0.1.6",
          "name": "anes",
          "version": "0.1.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\anes-0.1.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\anes-0.1.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
          "name": "atty",
          "version": "0.2.14",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atty-0.2.14\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atty-0.2.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.4.0",
          "name": "autocfg",
          "version": "1.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
          "name": "bitflags",
          "version": "1.3.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.6.0",
          "name": "bitflags",
          "version": "2.6.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.16.0",
          "name": "bumpalo",
          "version": "3.16.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.16.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.16.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
          "name": "cast",
          "version": "0.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cast-0.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cast-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.2",
          "name": "ciborium",
          "version": "0.2.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-0.2.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-0.2.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-io@0.2.2",
          "name": "ciborium-io",
          "version": "0.2.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-io-0.2.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-io-0.2.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-ll@0.2.2",
          "name": "ciborium-ll",
          "version": "0.2.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-ll-0.2.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ciborium-ll-0.2.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@3.2.25",
          "name": "clap",
          "version": "3.2.25",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap-3.2.25\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap-3.2.25"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_lex@0.2.4",
          "name": "clap_lex",
          "version": "0.2.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap_lex-0.2.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap_lex-0.2.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crc32fast@1.4.2",
          "name": "crc32fast",
          "version": "1.4.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crc32fast-1.4.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crc32fast-1.4.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.4.0",
          "name": "criterion",
          "version": "0.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-0.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.5.0",
          "name": "criterion-plot",
          "version": "0.5.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-plot-0.5.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-plot-0.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.6",
          "name": "crossbeam-deque",
          "version": "0.8.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-deque-0.8.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-deque-0.8.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.18",
          "name": "crossbeam-epoch",
          "version": "0.9.18",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-epoch-0.9.18\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-epoch-0.9.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.21",
          "name": "crossbeam-utils",
          "version": "0.8.21",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.21\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.21"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crunchy@0.2.2",
          "name": "crunchy",
          "version": "0.2.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crunchy-0.2.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crunchy-0.2.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#dashmap@5.5.3",
          "name": "dashmap",
          "version": "5.5.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dashmap-5.5.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\dashmap-5.5.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.13.0",
          "name": "either",
          "version": "1.13.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\either-1.13.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\either-1.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.10",
          "name": "errno",
          "version": "0.3.10",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.3.0",
          "name": "fastrand",
          "version": "2.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#flate2@1.0.35",
          "name": "flate2",
          "version": "1.0.35",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\flate2-1.0.35\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\flate2-1.0.35"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-executor@0.3.31",
          "name": "futures-executor",
          "version": "0.3.31",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-executor-0.3.31\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-executor-0.3.31"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.15",
          "name": "getrandom",
          "version": "0.2.15",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.2.15\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.2.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@2.4.1",
          "name": "half",
          "version": "2.4.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-2.4.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-2.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.12.3",
          "name": "hashbrown",
          "version": "0.12.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.12.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.12.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.14.5",
          "name": "hashbrown",
          "version": "0.14.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.14.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.14.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
          "name": "hermit-abi",
          "version": "0.1.19",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hermit-abi-0.1.19\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hermit-abi-0.1.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@1.9.3",
          "name": "indexmap",
          "version": "1.9.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-1.9.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-1.9.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
          "name": "itertools",
          "version": "0.10.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itertools-0.10.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itertools-0.10.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
          "name": "itoa",
          "version": "1.0.14",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.76",
          "name": "js-sys",
          "version": "0.3.76",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.76\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.76"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
          "name": "lazy_static",
          "version": "1.5.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lazy_static-1.5.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lazy_static-1.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
          "name": "libc",
          "version": "0.2.169",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.169\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.169"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.15",
          "name": "linux-raw-sys",
          "version": "0.4.15",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.4.15\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.4.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lock_api@0.4.12",
          "name": "lock_api",
          "version": "0.4.12",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lock_api-0.4.12\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lock_api-0.4.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.22",
          "name": "log",
          "version": "0.4.22",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.22\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.22"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
          "name": "memchr",
          "version": "2.7.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.1",
          "name": "memoffset",
          "version": "0.9.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.9.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memoffset-0.9.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#miniz_oxide@0.8.2",
          "name": "miniz_oxide",
          "version": "0.8.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.8.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\miniz_oxide-0.8.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
          "name": "num-traits",
          "version": "0.2.19",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.19\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.20.2",
          "name": "once_cell",
          "version": "1.20.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.20.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.20.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.4",
          "name": "oorandom",
          "version": "11.1.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\oorandom-11.1.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\oorandom-11.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#os_str_bytes@6.6.1",
          "name": "os_str_bytes",
          "version": "6.6.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\os_str_bytes-6.6.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\os_str_bytes-6.6.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot@0.12.3",
          "name": "parking_lot",
          "version": "0.12.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot-0.12.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot-0.12.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking_lot_core@0.9.10",
          "name": "parking_lot_core",
          "version": "0.9.10",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot_core-0.9.10\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\parking_lot_core-0.9.10"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
          "name": "plotters",
          "version": "0.3.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-0.3.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
          "name": "plotters-backend",
          "version": "0.3.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-backend-0.3.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-backend-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
          "name": "plotters-svg",
          "version": "0.3.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-svg-0.3.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\plotters-svg-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.92",
          "name": "proc-macro2",
          "version": "1.0.92",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.92\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.92"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
          "name": "quote",
          "version": "1.0.38",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.38\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.38"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.10.0",
          "name": "rayon",
          "version": "1.10.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-1.10.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-1.10.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.12.1",
          "name": "rayon-core",
          "version": "1.12.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-core-1.12.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-core-1.12.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#redox_syscall@0.5.8",
          "name": "redox_syscall",
          "version": "0.5.8",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.5.8\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\redox_syscall-0.5.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.11.1",
          "name": "regex",
          "version": "1.11.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
          "name": "regex-automata",
          "version": "0.4.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.5",
          "name": "regex-syntax",
          "version": "0.8.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.43",
          "name": "rustix",
          "version": "0.38.43",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-0.38.43\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-0.38.43"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
          "name": "rustix",
          "version": "0.38.44",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.18",
          "name": "ryu",
          "version": "1.0.18",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
          "name": "same-file",
          "version": "1.0.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
          "name": "scopeguard",
          "version": "1.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scopeguard-1.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\scopeguard-1.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
          "name": "serde",
          "version": "1.0.217",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
          "name": "serde_derive",
          "version": "1.0.217",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.217\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.217"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.135",
          "name": "serde_json",
          "version": "1.0.135",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.135\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.135"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serial_test@2.0.0",
          "name": "serial_test",
          "version": "2.0.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serial_test-2.0.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serial_test-2.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serial_test_derive@2.0.0",
          "name": "serial_test_derive",
          "version": "2.0.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serial_test_derive-2.0.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serial_test_derive-2.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.9",
          "name": "slab",
          "version": "0.4.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#smallvec@1.13.2",
          "name": "smallvec",
          "version": "1.13.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.13.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\smallvec-1.13.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#static_assertions@1.1.0",
          "name": "static_assertions",
          "version": "1.1.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\static_assertions-1.1.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\static_assertions-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.95",
          "name": "syn",
          "version": "2.0.95",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.95\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.95"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tempfile@3.15.0",
          "name": "tempfile",
          "version": "3.15.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tempfile-3.15.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tempfile-3.15.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.16.1",
          "name": "textwrap",
          "version": "0.16.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\textwrap-0.16.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\textwrap-0.16.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
          "name": "tinytemplate",
          "version": "1.2.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tinytemplate-1.2.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tinytemplate-1.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.14",
          "name": "unicode-ident",
          "version": "1.0.14",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.14\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
          "name": "walkdir",
          "version": "2.5.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.5.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
          "name": "wasi",
          "version": "0.11.0+wasi-snapshot-preview1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.11.0+wasi-snapshot-preview1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.11.0+wasi-snapshot-preview1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.99",
          "name": "wasm-bindgen",
          "version": "0.2.99",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.99\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.99"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.99",
          "name": "wasm-bindgen-backend",
          "version": "0.2.99",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-backend-0.2.99\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-backend-0.2.99"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.99",
          "name": "wasm-bindgen-macro",
          "version": "0.2.99",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.99\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.99"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.99",
          "name": "wasm-bindgen-macro-support",
          "version": "0.2.99",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.99\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.99"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.99",
          "name": "wasm-bindgen-shared",
          "version": "0.2.99",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.99\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.99"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.76",
          "name": "web-sys",
          "version": "0.3.76",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.76\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.76"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.9",
          "name": "winapi-util",
          "version": "0.1.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
          "name": "winapi-x86_64-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
          "name": "windows-sys",
          "version": "0.59.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
          "name": "windows-targets",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.6",
          "name": "windows_aarch64_gnullvm",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_gnullvm-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.6",
          "name": "windows_aarch64_msvc",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_aarch64_msvc-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
          "name": "windows_i686_gnu",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnu-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.6",
          "name": "windows_i686_gnullvm",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnullvm-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_gnullvm-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
          "name": "windows_i686_msvc",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_i686_msvc-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
          "name": "windows_x86_64_gnu",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnu-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.6",
          "name": "windows_x86_64_gnullvm",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_gnullvm-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
          "name": "windows_x86_64_msvc",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "exit_code": 0,
      "kind": "exec",
      "pid": 9268,
      "ppid": 10760,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:3aff0bc856f31bfd:e8de79f1eb1779bb",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
      "pid": 9268,
      "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:7e0f63e5ff214ab3:e8de79f1eb1779bb",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
      "pid": 9268,
      "sha256": "e64fa3fcaf1d5daf1907f7ad5f635c73081f2a499b21932a59efdac305d92c00",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:8020e6d8e2bae565:e8de79f1eb1779bb",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
      "pid": 9268,
      "sha256": "634a3a0773b3d31265e3d84380f06a40098c1bc7a23c6c9db7ead60d604ee899",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:1ceda9c220daf075:e8de79f1eb1779bb",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "kernel32.lib",
      "pid": 9268,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:1ceda9c220daf075:e8de79f1eb1779bb",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "kernel32.lib",
      "pid": 9268,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:1ceda9c220daf075:e8de79f1eb1779bb",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "kernel32.lib",
      "pid": 9268,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:1db9512c4d5c31e6:e8de79f1eb1779bb",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "ntdll.lib",
      "pid": 9268,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:861f0814f9c52599:e8de79f1eb1779bb",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "userenv.lib",
      "pid": 9268,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:50848825683fdca9:e8de79f1eb1779bb",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "ws2_32.lib",
      "pid": 9268,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "used:link:e4dabb9c925fb3b9:df7d4e53c08047f7:e8de79f1eb1779bb",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "path": "dbghelp.lib",
      "pid": 9268,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o"
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
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "cargo_pkg_name": "windows_x86_64_msvc",
      "cargo_pkg_version": "0.52.6",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 9268,
      "ppid": 10760,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\rustcpeUkEo\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.build_script_build.644141f1d2fde17e-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.2z3dvkqwjobuudf9zuxxe9jt6.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build_script_build-d70364700e1c05c8.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "directories": [
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000148       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000198       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001d0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000288       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002b8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000148       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000198       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-9268-1783954156770894200.map",
      "pid": 9268,
      "ppid": 10760,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-9268-1783954156770894200.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17072,
      "ppid": 6272,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "rustix",
        "version": "0.38.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "rustix",
        "version": "0.38.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "cargo_pkg_name": "rustix",
      "cargo_pkg_version": "0.38.44",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 17072,
      "ppid": 6272,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "_owner": {
        "crate": "rustix",
        "version": "0.38.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-4684-1783954155375\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f\\rustcFtKgMY\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000001f8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000248       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000268       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000280       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000290       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000350       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000378       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000001f8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000001f8       \\177KERNEL32_NULL_THUNK_DATA 00000001400351f8     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000248       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000248       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140035248     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000268       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000268       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140035268     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000280       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000280       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140035280     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000290       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000290       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140035290     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:000002a0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400352a0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000338       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140035338     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000350       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000350       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140035350     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000378       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\0002:00000378       \\177ntdll_NULL_THUNK_DATA  0000000140035378     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-17072-1783954156837597100.map",
      "pid": 17072,
      "ppid": 6272,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\.tmp\\native-trace-link-link-17072-1783954156837597100.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "rustix",
        "version": "0.38.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44#rustix@0.38.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "windows_x86_64_msvc",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "event_id": "bsrun:74c91b68f6495963:d5cd19ac9cf9f506:ba1ac6a86aa25d04",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44/target/debug/build/windows_x86_64_msvc-d70364700e1c05c8\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-3mdw8r9b/src/rustix-0.38.44/target/debug/build/windows_x86_64_msvc-d70364700e1c05c8/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
      "success": true,
      "target": null,
      "version": "0.52.6",
      "_owner": {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
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
      "raw_event_count": 2771,
      "parsed_event_count": 2771,
      "parse_error_count": 0,
      "command_line_event_count": 2771,
      "build_script_root_event_count": 54,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 192,
      "dropped_event_count": 1402
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11104,
      "ppid": 10292,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:49:16.938118+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8\\build-script-build.exe",
      "root_cargo_pid": 2908,
      "build_script_root_pid": 11104,
      "build_script_related": true,
      "build_script_target_dir": "windows_x86_64_msvc-d70364700e1c05c8"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 5024,
      "ppid": 10404,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
      "time": "2026-07-13T14:49:15.594039+00:00",
      "end_time": "2026-07-13T14:49:15.612106+00:00",
      "start_unix_nanos": 1783954155594039000,
      "end_unix_nanos": 1783954155612106300,
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
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 3216,
      "ppid": 10404,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
      "time": "2026-07-13T14:49:15.618282+00:00",
      "end_time": "2026-07-13T14:49:15.636690+00:00",
      "start_unix_nanos": 1783954155618282400,
      "end_unix_nanos": 1783954155636689900,
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
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 11144,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
      "time": "2026-07-13T14:49:16.513548+00:00",
      "end_time": "2026-07-13T14:49:16.530687+00:00",
      "start_unix_nanos": 1783954156513548200,
      "end_unix_nanos": 1783954156530686900,
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
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 5064,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
      "time": "2026-07-13T14:49:16.536899+00:00",
      "end_time": "2026-07-13T14:49:16.556631+00:00",
      "start_unix_nanos": 1783954156536899400,
      "end_unix_nanos": 1783954156556630600,
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
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 14360,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
      "time": "2026-07-13T14:49:16.585212+00:00",
      "end_time": "2026-07-13T14:49:16.604410+00:00",
      "start_unix_nanos": 1783954156585211700,
      "end_unix_nanos": 1783954156604409800,
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
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 1920,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\build.rs",
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
        "metadata=c40b9585e3e79a94",
        "-C",
        "extra-filename=-d70364700e1c05c8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=c40b9585e3e79a94 -C extra-filename=-d70364700e1c05c8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\build.rs",
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
        "metadata=c40b9585e3e79a94",
        "-C",
        "extra-filename=-d70364700e1c05c8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:16.633493+00:00",
      "end_time": "2026-07-13T14:49:16.867832+00:00",
      "start_unix_nanos": 1783954156633493500,
      "end_unix_nanos": 1783954156867832100,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\windows_x86_64_msvc-d70364700e1c05c8"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 16456,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "bitflags",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0\\src\\lib.rs",
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
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std\"))",
        "-C",
        "metadata=75eee6cc8dbe924b",
        "-C",
        "extra-filename=-4db8ea0490b59b49",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name bitflags --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"bytemuck\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"example_generated\\\", \\\"rustc-dep-of-std\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=75eee6cc8dbe924b -C extra-filename=-4db8ea0490b59b49 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "bitflags",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.6.0\\src\\lib.rs",
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
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"arbitrary\", \"bytemuck\", \"compiler_builtins\", \"core\", \"example_generated\", \"rustc-dep-of-std\", \"serde\", \"std\"))",
        "-C",
        "metadata=75eee6cc8dbe924b",
        "-C",
        "extra-filename=-4db8ea0490b59b49",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:16.636323+00:00",
      "end_time": "2026-07-13T14:49:16.821174+00:00",
      "start_unix_nanos": 1783954156636322900,
      "end_unix_nanos": 1783954156821174400,
      "crate_name": "bitflags",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 12964,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
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
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(alloc_c_string)",
        "--check-cfg",
        "cfg(alloc_ffi)",
        "--check-cfg",
        "cfg(apple)",
        "--check-cfg",
        "cfg(asm_experimental_arch)",
        "--check-cfg",
        "cfg(bsd)",
        "--check-cfg",
        "cfg(core_c_str)",
        "--check-cfg",
        "cfg(core_ffi_c)",
        "--check-cfg",
        "cfg(core_intrinsics)",
        "--check-cfg",
        "cfg(criterion)",
        "--check-cfg",
        "cfg(document_experimental_runtime_api)",
        "--check-cfg",
        "cfg(fix_y2038)",
        "--check-cfg",
        "cfg(freebsdlike)",
        "--check-cfg",
        "cfg(libc)",
        "--check-cfg",
        "cfg(linux_kernel)",
        "--check-cfg",
        "cfg(linux_like)",
        "--check-cfg",
        "cfg(linux_raw)",
        "--check-cfg",
        "cfg(netbsdlike)",
        "--check-cfg",
        "cfg(rustc_attrs)",
        "--check-cfg",
        "cfg(solarish)",
        "--check-cfg",
        "cfg(staged_api)",
        "--check-cfg",
        "cfg(static_assertions)",
        "--check-cfg",
        "cfg(thumb_mode)",
        "--check-cfg",
        "cfg(wasi)",
        "--check-cfg",
        "cfg(wasi_ext)",
        "--check-cfg",
        "cfg(target_arch, values(\"xtensa\"))",
        "--cfg",
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"libc-extra-traits\"",
        "--cfg",
        "feature=\"std\"",
        "--cfg",
        "feature=\"use-libc-auxv\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"all-apis\", \"alloc\", \"cc\", \"compiler_builtins\", \"core\", \"default\", \"event\", \"fs\", \"io_uring\", \"itoa\", \"libc\", \"libc-extra-traits\", \"libc_errno\", \"linux_4_11\", \"linux_latest\", \"mm\", \"mount\", \"net\", \"once_cell\", \"param\", \"pipe\", \"process\", \"procfs\", \"pty\", \"rand\", \"runtime\", \"rustc-dep-of-std\", \"rustc-std-workspace-alloc\", \"shm\", \"std\", \"stdio\", \"system\", \"termios\", \"thread\", \"time\", \"try_close\", \"use-explicitly-provided-auxv\", \"use-libc\", \"use-libc-auxv\"))",
        "-C",
        "metadata=ae0438f501f3af71",
        "-C",
        "extra-filename=-cd5fd26b3ac4112f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg cfg(apple) --check-cfg cfg(asm_experimental_arch) --check-cfg cfg(bsd) --check-cfg cfg(core_c_str) --check-cfg cfg(core_ffi_c) --check-cfg cfg(core_intrinsics) --check-cfg cfg(criterion) --check-cfg cfg(document_experimental_runtime_api) --check-cfg cfg(fix_y2038) --check-cfg cfg(freebsdlike) --check-cfg cfg(libc) --check-cfg cfg(linux_kernel) --check-cfg cfg(linux_like) --check-cfg cfg(linux_raw) --check-cfg cfg(netbsdlike) --check-cfg cfg(rustc_attrs) --check-cfg cfg(solarish) --check-cfg cfg(staged_api) --check-cfg cfg(static_assertions) --check-cfg cfg(thumb_mode) --check-cfg cfg(wasi) --check-cfg cfg(wasi_ext) --check-cfg \"cfg(target_arch, values(\\\"xtensa\\\"))\" --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"libc-extra-traits\\\"\" --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"use-libc-auxv\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"all-apis\\\", \\\"alloc\\\", \\\"cc\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"event\\\", \\\"fs\\\", \\\"io_uring\\\", \\\"itoa\\\", \\\"libc\\\", \\\"libc-extra-traits\\\", \\\"libc_errno\\\", \\\"linux_4_11\\\", \\\"linux_latest\\\", \\\"mm\\\", \\\"mount\\\", \\\"net\\\", \\\"once_cell\\\", \\\"param\\\", \\\"pipe\\\", \\\"process\\\", \\\"procfs\\\", \\\"pty\\\", \\\"rand\\\", \\\"runtime\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-alloc\\\", \\\"shm\\\", \\\"std\\\", \\\"stdio\\\", \\\"system\\\", \\\"termios\\\", \\\"thread\\\", \\\"time\\\", \\\"try_close\\\", \\\"use-explicitly-provided-auxv\\\", \\\"use-libc\\\", \\\"use-libc-auxv\\\"))\" -C metadata=ae0438f501f3af71 -C extra-filename=-cd5fd26b3ac4112f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
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
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(alloc_c_string)",
        "--check-cfg",
        "cfg(alloc_ffi)",
        "--check-cfg",
        "cfg(apple)",
        "--check-cfg",
        "cfg(asm_experimental_arch)",
        "--check-cfg",
        "cfg(bsd)",
        "--check-cfg",
        "cfg(core_c_str)",
        "--check-cfg",
        "cfg(core_ffi_c)",
        "--check-cfg",
        "cfg(core_intrinsics)",
        "--check-cfg",
        "cfg(criterion)",
        "--check-cfg",
        "cfg(document_experimental_runtime_api)",
        "--check-cfg",
        "cfg(fix_y2038)",
        "--check-cfg",
        "cfg(freebsdlike)",
        "--check-cfg",
        "cfg(libc)",
        "--check-cfg",
        "cfg(linux_kernel)",
        "--check-cfg",
        "cfg(linux_like)",
        "--check-cfg",
        "cfg(linux_raw)",
        "--check-cfg",
        "cfg(netbsdlike)",
        "--check-cfg",
        "cfg(rustc_attrs)",
        "--check-cfg",
        "cfg(solarish)",
        "--check-cfg",
        "cfg(staged_api)",
        "--check-cfg",
        "cfg(static_assertions)",
        "--check-cfg",
        "cfg(thumb_mode)",
        "--check-cfg",
        "cfg(wasi)",
        "--check-cfg",
        "cfg(wasi_ext)",
        "--check-cfg",
        "cfg(target_arch, values(\"xtensa\"))",
        "--cfg",
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"libc-extra-traits\"",
        "--cfg",
        "feature=\"std\"",
        "--cfg",
        "feature=\"use-libc-auxv\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"all-apis\", \"alloc\", \"cc\", \"compiler_builtins\", \"core\", \"default\", \"event\", \"fs\", \"io_uring\", \"itoa\", \"libc\", \"libc-extra-traits\", \"libc_errno\", \"linux_4_11\", \"linux_latest\", \"mm\", \"mount\", \"net\", \"once_cell\", \"param\", \"pipe\", \"process\", \"procfs\", \"pty\", \"rand\", \"runtime\", \"rustc-dep-of-std\", \"rustc-std-workspace-alloc\", \"shm\", \"std\", \"stdio\", \"system\", \"termios\", \"thread\", \"time\", \"try_close\", \"use-explicitly-provided-auxv\", \"use-libc\", \"use-libc-auxv\"))",
        "-C",
        "metadata=ae0438f501f3af71",
        "-C",
        "extra-filename=-cd5fd26b3ac4112f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:16.639356+00:00",
      "end_time": "2026-07-13T14:49:17.271338+00:00",
      "start_unix_nanos": 1783954156639356300,
      "end_unix_nanos": 1783954157271337600,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\build\\rustix-cd5fd26b3ac4112f"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 15308,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_x86_64_msvc",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\src\\lib.rs",
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
        "metadata=2c7388cfc29d58e3",
        "-C",
        "extra-filename=-c5c5726af64828cf",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_x86_64_msvc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=2c7388cfc29d58e3 -C extra-filename=-c5c5726af64828cf --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_x86_64_msvc",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\src\\lib.rs",
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
        "metadata=2c7388cfc29d58e3",
        "-C",
        "extra-filename=-c5c5726af64828cf",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:16.958290+00:00",
      "end_time": "2026-07-13T14:49:17.024756+00:00",
      "start_unix_nanos": 1783954156958289900,
      "end_unix_nanos": 1783954157024756200,
      "crate_name": "windows_x86_64_msvc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 15232,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_targets",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--warn=rust_2018_idioms",
        "--warn=unexpected_cfgs",
        "--warn=missing_docs",
        "--check-cfg",
        "cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=6bcdc394d921aa7b",
        "-C",
        "extra-filename=-b170585257b0d7b4",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--extern",
        "windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_x86_64_msvc-c5c5726af64828cf.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_targets --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=unexpected_cfgs --warn=missing_docs --check-cfg \"cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=6bcdc394d921aa7b -C extra-filename=-b170585257b0d7b4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --extern windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_x86_64_msvc-c5c5726af64828cf.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_targets",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-targets-0.52.6\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--warn=rust_2018_idioms",
        "--warn=unexpected_cfgs",
        "--warn=missing_docs",
        "--check-cfg",
        "cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=6bcdc394d921aa7b",
        "-C",
        "extra-filename=-b170585257b0d7b4",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--extern",
        "windows_x86_64_msvc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_x86_64_msvc-c5c5726af64828cf.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:17.006344+00:00",
      "end_time": "2026-07-13T14:49:17.056560+00:00",
      "start_unix_nanos": 1783954157006343800,
      "end_unix_nanos": 1783954157056560300,
      "crate_name": "windows_targets",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 9624,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_sys",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--warn=rust_2018_idioms",
        "--warn=unexpected_cfgs",
        "--warn=missing_docs",
        "--check-cfg",
        "cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)",
        "--cfg",
        "feature=\"Win32\"",
        "--cfg",
        "feature=\"Win32_Foundation\"",
        "--cfg",
        "feature=\"Win32_NetworkManagement\"",
        "--cfg",
        "feature=\"Win32_NetworkManagement_IpHelper\"",
        "--cfg",
        "feature=\"Win32_Networking\"",
        "--cfg",
        "feature=\"Win32_Networking_WinSock\"",
        "--cfg",
        "feature=\"Win32_System\"",
        "--cfg",
        "feature=\"Win32_System_Diagnostics\"",
        "--cfg",
        "feature=\"Win32_System_Diagnostics_Debug\"",
        "--cfg",
        "feature=\"Win32_System_Threading\"",
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"Wdk\", \"Wdk_Devices\", \"Wdk_Devices_Bluetooth\", \"Wdk_Devices_HumanInterfaceDevice\", \"Wdk_Foundation\", \"Wdk_Graphics\", \"Wdk_Graphics_Direct3D\", \"Wdk_NetworkManagement\", \"Wdk_NetworkManagement_Ndis\", \"Wdk_NetworkManagement_WindowsFilteringPlatform\", \"Wdk_Storage\", \"Wdk_Storage_FileSystem\", \"Wdk_Storage_FileSystem_Minifilters\", \"Wdk_System\", \"Wdk_System_IO\", \"Wdk_System_Memory\", \"Wdk_System_OfflineRegistry\", \"Wdk_System_Registry\", \"Wdk_System_SystemInformation\", \"Wdk_System_SystemServices\", \"Wdk_System_Threading\", \"Win32\", \"Win32_Data\", \"Win32_Data_HtmlHelp\", \"Win32_Data_RightsManagement\", \"Win32_Devices\", \"Win32_Devices_AllJoyn\", \"Win32_Devices_BiometricFramework\", \"Win32_Devices_Bluetooth\", \"Win32_Devices_Communication\", \"Win32_Devices_DeviceAndDriverInstallation\", \"Win32_Devices_DeviceQuery\", \"Win32_Devices_Display\", \"Win32_Devices_Enumeration\", \"Win32_Devices_Enumeration_Pnp\", \"Win32_Devices_Fax\", \"Win32_Devices_HumanInterfaceDevice\", \"Win32_Devices_PortableDevices\", \"Win32_Devices_Properties\", \"Win32_Devices_Pwm\", \"Win32_Devices_Sensors\", \"Win32_Devices_SerialCommunication\", \"Win32_Devices_Tapi\", \"Win32_Devices_Usb\", \"Win32_Devices_WebServicesOnDevices\", \"Win32_Foundation\", \"Win32_Gaming\", \"Win32_Globalization\", \"Win32_Graphics\", \"Win32_Graphics_Dwm\", \"Win32_Graphics_Gdi\", \"Win32_Graphics_GdiPlus\", \"Win32_Graphics_Hlsl\", \"Win32_Graphics_OpenGL\", \"Win32_Graphics_Printing\", \"Win32_Graphics_Printing_PrintTicket\", \"Win32_Management\", \"Win32_Management_MobileDeviceManagementRegistration\", \"Win32_Media\", \"Win32_Media_Audio\", \"Win32_Media_DxMediaObjects\", \"Win32_Media_KernelStreaming\", \"Win32_Media_Multimedia\", \"Win32_Media_Streaming\", \"Win32_Media_WindowsMediaFormat\", \"Win32_NetworkManagement\", \"Win32_NetworkManagement_Dhcp\", \"Win32_NetworkManagement_Dns\", \"Win32_NetworkManagement_InternetConnectionWizard\", \"Win32_NetworkManagement_IpHelper\", \"Win32_NetworkManagement_Multicast\", \"Win32_NetworkManagement_Ndis\", \"Win32_NetworkManagement_NetBios\", \"Win32_NetworkManagement_NetManagement\", \"Win32_NetworkManagement_NetShell\", \"Win32_NetworkManagement_NetworkDiagnosticsFramework\", \"Win32_NetworkManagement_P2P\", \"Win32_NetworkManagement_QoS\", \"Win32_NetworkManagement_Rras\", \"Win32_NetworkManagement_Snmp\", \"Win32_NetworkManagement_WNet\", \"Win32_NetworkManagement_WebDav\", \"Win32_NetworkManagement_WiFi\", \"Win32_NetworkManagement_WindowsConnectionManager\", \"Win32_NetworkManagement_WindowsFilteringPlatform\", \"Win32_NetworkManagement_WindowsFirewall\", \"Win32_NetworkManagement_WindowsNetworkVirtualization\", \"Win32_Networking\", \"Win32_Networking_ActiveDirectory\", \"Win32_Networking_Clustering\", \"Win32_Networking_HttpServer\", \"Win32_Networking_Ldap\", \"Win32_Networking_WebSocket\", \"Win32_Networking_WinHttp\", \"Win32_Networking_WinInet\", \"Win32_Networking_WinSock\", \"Win32_Networking_WindowsWebServices\", \"Win32_Security\", \"Win32_Security_AppLocker\", \"Win32_Security_Authentication\", \"Win32_Security_Authentication_Identity\", \"Win32_Security_Authorization\", \"Win32_Security_Credentials\", \"Win32_Security_Cryptography\", \"Win32_Security_Cryptography_Catalog\", \"Win32_Security_Cryptography_Certificates\", \"Win32_Security_Cryptography_Sip\", \"Win32_Security_Cryptography_UI\", \"Win32_Security_DiagnosticDataQuery\", \"Win32_Security_DirectoryServices\", \"Win32_Security_EnterpriseData\", \"Win32_Security_ExtensibleAuthenticationProtocol\", \"Win32_Security_Isolation\", \"Win32_Security_LicenseProtection\", \"Win32_Security_NetworkAccessProtection\", \"Win32_Security_WinTrust\", \"Win32_Security_WinWlx\", \"Win32_Storage\", \"Win32_Storage_Cabinets\", \"Win32_Storage_CloudFilters\", \"Win32_Storage_Compression\", \"Win32_Storage_DistributedFileSystem\", \"Win32_Storage_FileHistory\", \"Win32_Storage_FileSystem\", \"Win32_Storage_Imapi\", \"Win32_Storage_IndexServer\", \"Win32_Storage_InstallableFileSystems\", \"Win32_Storage_IscsiDisc\", \"Win32_Storage_Jet\", \"Win32_Storage_Nvme\", \"Win32_Storage_OfflineFiles\", \"Win32_Storage_OperationRecorder\", \"Win32_Storage_Packaging\", \"Win32_Storage_Packaging_Appx\", \"Win32_Storage_ProjectedFileSystem\", \"Win32_Storage_StructuredStorage\", \"Win32_Storage_Vhd\", \"Win32_Storage_Xps\", \"Win32_System\", \"Win32_System_AddressBook\", \"Win32_System_Antimalware\", \"Win32_System_ApplicationInstallationAndServicing\", \"Win32_System_ApplicationVerifier\", \"Win32_System_ClrHosting\", \"Win32_System_Com\", \"Win32_System_Com_Marshal\", \"Win32_System_Com_StructuredStorage\", \"Win32_System_Com_Urlmon\", \"Win32_System_ComponentServices\", \"Win32_System_Console\", \"Win32_System_CorrelationVector\", \"Win32_System_DataExchange\", \"Win32_System_DeploymentServices\", \"Win32_System_DeveloperLicensing\", \"Win32_System_Diagnostics\", \"Win32_System_Diagnostics_Ceip\", \"Win32_System_Diagnostics_Debug\", \"Win32_System_Diagnostics_Debug_Extensions\", \"Win32_System_Diagnostics_Etw\", \"Win32_System_Diagnostics_ProcessSnapshotting\", \"Win32_System_Diagnostics_ToolHelp\", \"Win32_System_Diagnostics_TraceLogging\", \"Win32_System_DistributedTransactionCoordinator\", \"Win32_System_Environment\", \"Win32_System_ErrorReporting\", \"Win32_System_EventCollector\", \"Win32_System_EventLog\", \"Win32_System_EventNotificationService\", \"Win32_System_GroupPolicy\", \"Win32_System_HostCompute\", \"Win32_System_HostComputeNetwork\", \"Win32_System_HostComputeSystem\", \"Win32_System_Hypervisor\", \"Win32_System_IO\", \"Win32_System_Iis\", \"Win32_System_Ioctl\", \"Win32_System_JobObjects\", \"Win32_System_Js\", \"Win32_System_Kernel\", \"Win32_System_LibraryLoader\", \"Win32_System_Mailslots\", \"Win32_System_Mapi\", \"Win32_System_Memory\", \"Win32_System_Memory_NonVolatile\", \"Win32_System_MessageQueuing\", \"Win32_System_MixedReality\", \"Win32_System_Ole\", \"Win32_System_PasswordManagement\", \"Win32_System_Performance\", \"Win32_System_Performance_HardwareCounterProfiling\", \"Win32_System_Pipes\", \"Win32_System_Power\", \"Win32_System_ProcessStatus\", \"Win32_System_Recovery\", \"Win32_System_Registry\", \"Win32_System_RemoteDesktop\", \"Win32_System_RemoteManagement\", \"Win32_System_RestartManager\", \"Win32_System_Restore\", \"Win32_System_Rpc\", \"Win32_System_Search\", \"Win32_System_Search_Common\", \"Win32_System_SecurityCenter\", \"Win32_System_Services\", \"Win32_System_SetupAndMigration\", \"Win32_System_Shutdown\", \"Win32_System_StationsAndDesktops\", \"Win32_System_SubsystemForLinux\", \"Win32_System_SystemInformation\", \"Win32_System_SystemServices\", \"Win32_System_Threading\", \"Win32_System_Time\", \"Win32_System_TpmBaseServices\", \"Win32_System_UserAccessLogging\", \"Win32_System_Variant\", \"Win32_System_VirtualDosMachines\", \"Win32_System_WindowsProgramming\", \"Win32_System_Wmi\", \"Win32_UI\", \"Win32_UI_Accessibility\", \"Win32_UI_ColorSystem\", \"Win32_UI_Controls\", \"Win32_UI_Controls_Dialogs\", \"Win32_UI_HiDpi\", \"Win32_UI_Input\", \"Win32_UI_Input_Ime\", \"Win32_UI_Input_KeyboardAndMouse\", \"Win32_UI_Input_Pointer\", \"Win32_UI_Input_Touch\", \"Win32_UI_Input_XboxController\", \"Win32_UI_InteractionContext\", \"Win32_UI_Magnification\", \"Win32_UI_Shell\", \"Win32_UI_Shell_Common\", \"Win32_UI_Shell_PropertiesSystem\", \"Win32_UI_TabletPC\", \"Win32_UI_TextServices\", \"Win32_UI_WindowsAndMessaging\", \"Win32_Web\", \"Win32_Web_InternetExplorer\", \"default\", \"docs\"))",
        "-C",
        "metadata=badd2551c5aed9ed",
        "-C",
        "extra-filename=-318e9bc24ee987c1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--extern",
        "windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_targets-b170585257b0d7b4.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_sys --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=rust_2018_idioms --warn=unexpected_cfgs --warn=missing_docs --check-cfg \"cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)\" --cfg \"feature=\\\"Win32\\\"\" --cfg \"feature=\\\"Win32_Foundation\\\"\" --cfg \"feature=\\\"Win32_NetworkManagement\\\"\" --cfg \"feature=\\\"Win32_NetworkManagement_IpHelper\\\"\" --cfg \"feature=\\\"Win32_Networking\\\"\" --cfg \"feature=\\\"Win32_Networking_WinSock\\\"\" --cfg \"feature=\\\"Win32_System\\\"\" --cfg \"feature=\\\"Win32_System_Diagnostics\\\"\" --cfg \"feature=\\\"Win32_System_Diagnostics_Debug\\\"\" --cfg \"feature=\\\"Win32_System_Threading\\\"\" --cfg \"feature=\\\"default\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"Wdk\\\", \\\"Wdk_Devices\\\", \\\"Wdk_Devices_Bluetooth\\\", \\\"Wdk_Devices_HumanInterfaceDevice\\\", \\\"Wdk_Foundation\\\", \\\"Wdk_Graphics\\\", \\\"Wdk_Graphics_Direct3D\\\", \\\"Wdk_NetworkManagement\\\", \\\"Wdk_NetworkManagement_Ndis\\\", \\\"Wdk_NetworkManagement_WindowsFilteringPlatform\\\", \\\"Wdk_Storage\\\", \\\"Wdk_Storage_FileSystem\\\", \\\"Wdk_Storage_FileSystem_Minifilters\\\", \\\"Wdk_System\\\", \\\"Wdk_System_IO\\\", \\\"Wdk_System_Memory\\\", \\\"Wdk_System_OfflineRegistry\\\", \\\"Wdk_System_Registry\\\", \\\"Wdk_System_SystemInformation\\\", \\\"Wdk_System_SystemServices\\\", \\\"Wdk_System_Threading\\\", \\\"Win32\\\", \\\"Win32_Data\\\", \\\"Win32_Data_HtmlHelp\\\", \\\"Win32_Data_RightsManagement\\\", \\\"Win32_Devices\\\", \\\"Win32_Devices_AllJoyn\\\", \\\"Win32_Devices_BiometricFramework\\\", \\\"Win32_Devices_Bluetooth\\\", \\\"Win32_Devices_Communication\\\", \\\"Win32_Devices_DeviceAndDriverInstallation\\\", \\\"Win32_Devices_DeviceQuery\\\", \\\"Win32_Devices_Display\\\", \\\"Win32_Devices_Enumeration\\\", \\\"Win32_Devices_Enumeration_Pnp\\\", \\\"Win32_Devices_Fax\\\", \\\"Win32_Devices_HumanInterfaceDevice\\\", \\\"Win32_Devices_PortableDevices\\\", \\\"Win32_Devices_Properties\\\", \\\"Win32_Devices_Pwm\\\", \\\"Win32_Devices_Sensors\\\", \\\"Win32_Devices_SerialCommunication\\\", \\\"Win32_Devices_Tapi\\\", \\\"Win32_Devices_Usb\\\", \\\"Win32_Devices_WebServicesOnDevices\\\", \\\"Win32_Foundation\\\", \\\"Win32_Gaming\\\", \\\"Win32_Globalization\\\", \\\"Win32_Graphics\\\", \\\"Win32_Graphics_Dwm\\\", \\\"Win32_Graphics_Gdi\\\", \\\"Win32_Graphics_GdiPlus\\\", \\\"Win32_Graphics_Hlsl\\\", \\\"Win32_Graphics_OpenGL\\\", \\\"Win32_Graphics_Printing\\\", \\\"Win32_Graphics_Printing_PrintTicket\\\", \\\"Win32_Management\\\", \\\"Win32_Management_MobileDeviceManagementRegistration\\\", \\\"Win32_Media\\\", \\\"Win32_Media_Audio\\\", \\\"Win32_Media_DxMediaObjects\\\", \\\"Win32_Media_KernelStreaming\\\", \\\"Win32_Media_Multimedia\\\", \\\"Win32_Media_Streaming\\\", \\\"Win32_Media_WindowsMediaFormat\\\", \\\"Win32_NetworkManagement\\\", \\\"Win32_NetworkManagement_Dhcp\\\", \\\"Win32_NetworkManagement_Dns\\\", \\\"Win32_NetworkManagement_InternetConnectionWizard\\\", \\\"Win32_NetworkManagement_IpHelper\\\", \\\"Win32_NetworkManagement_Multicast\\\", \\\"Win32_NetworkManagement_Ndis\\\", \\\"Win32_NetworkManagement_NetBios\\\", \\\"Win32_NetworkManagement_NetManagement\\\", \\\"Win32_NetworkManagement_NetShell\\\", \\\"Win32_NetworkManagement_NetworkDiagnosticsFramework\\\", \\\"Win32_NetworkManagement_P2P\\\", \\\"Win32_NetworkManagement_QoS\\\", \\\"Win32_NetworkManagement_Rras\\\", \\\"Win32_NetworkManagement_Snmp\\\", \\\"Win32_NetworkManagement_WNet\\\", \\\"Win32_NetworkManagement_WebDav\\\", \\\"Win32_NetworkManagement_WiFi\\\", \\\"Win32_NetworkManagement_WindowsConnectionManager\\\", \\\"Win32_NetworkManagement_WindowsFilteringPlatform\\\", \\\"Win32_NetworkManagement_WindowsFirewall\\\", \\\"Win32_NetworkManagement_WindowsNetworkVirtualization\\\", \\\"Win32_Networking\\\", \\\"Win32_Networking_ActiveDirectory\\\", \\\"Win32_Networking_Clustering\\\", \\\"Win32_Networking_HttpServer\\\", \\\"Win32_Networking_Ldap\\\", \\\"Win32_Networking_WebSocket\\\", \\\"Win32_Networking_WinHttp\\\", \\\"Win32_Networking_WinInet\\\", \\\"Win32_Networking_WinSock\\\", \\\"Win32_Networking_WindowsWebServices\\\", \\\"Win32_Security\\\", \\\"Win32_Security_AppLocker\\\", \\\"Win32_Security_Authentication\\\", \\\"Win32_Security_Authentication_Identity\\\", \\\"Win32_Security_Authorization\\\", \\\"Win32_Security_Credentials\\\", \\\"Win32_Security_Cryptography\\\", \\\"Win32_Security_Cryptography_Catalog\\\", \\\"Win32_Security_Cryptography_Certificates\\\", \\\"Win32_Security_Cryptography_Sip\\\", \\\"Win32_Security_Cryptography_UI\\\", \\\"Win32_Security_DiagnosticDataQuery\\\", \\\"Win32_Security_DirectoryServices\\\", \\\"Win32_Security_EnterpriseData\\\", \\\"Win32_Security_ExtensibleAuthenticationProtocol\\\", \\\"Win32_Security_Isolation\\\", \\\"Win32_Security_LicenseProtection\\\", \\\"Win32_Security_NetworkAccessProtection\\\", \\\"Win32_Security_WinTrust\\\", \\\"Win32_Security_WinWlx\\\", \\\"Win32_Storage\\\", \\\"Win32_Storage_Cabinets\\\", \\\"Win32_Storage_CloudFilters\\\", \\\"Win32_Storage_Compression\\\", \\\"Win32_Storage_DistributedFileSystem\\\", \\\"Win32_Storage_FileHistory\\\", \\\"Win32_Storage_FileSystem\\\", \\\"Win32_Storage_Imapi\\\", \\\"Win32_Storage_IndexServer\\\", \\\"Win32_Storage_InstallableFileSystems\\\", \\\"Win32_Storage_IscsiDisc\\\", \\\"Win32_Storage_Jet\\\", \\\"Win32_Storage_Nvme\\\", \\\"Win32_Storage_OfflineFiles\\\", \\\"Win32_Storage_OperationRecorder\\\", \\\"Win32_Storage_Packaging\\\", \\\"Win32_Storage_Packaging_Appx\\\", \\\"Win32_Storage_ProjectedFileSystem\\\", \\\"Win32_Storage_StructuredStorage\\\", \\\"Win32_Storage_Vhd\\\", \\\"Win32_Storage_Xps\\\", \\\"Win32_System\\\", \\\"Win32_System_AddressBook\\\", \\\"Win32_System_Antimalware\\\", \\\"Win32_System_ApplicationInstallationAndServicing\\\", \\\"Win32_System_ApplicationVerifier\\\", \\\"Win32_System_ClrHosting\\\", \\\"Win32_System_Com\\\", \\\"Win32_System_Com_Marshal\\\", \\\"Win32_System_Com_StructuredStorage\\\", \\\"Win32_System_Com_Urlmon\\\", \\\"Win32_System_ComponentServices\\\", \\\"Win32_System_Console\\\", \\\"Win32_System_CorrelationVector\\\", \\\"Win32_System_DataExchange\\\", \\\"Win32_System_DeploymentServices\\\", \\\"Win32_System_DeveloperLicensing\\\", \\\"Win32_System_Diagnostics\\\", \\\"Win32_System_Diagnostics_Ceip\\\", \\\"Win32_System_Diagnostics_Debug\\\", \\\"Win32_System_Diagnostics_Debug_Extensions\\\", \\\"Win32_System_Diagnostics_Etw\\\", \\\"Win32_System_Diagnostics_ProcessSnapshotting\\\", \\\"Win32_System_Diagnostics_ToolHelp\\\", \\\"Win32_System_Diagnostics_TraceLogging\\\", \\\"Win32_System_DistributedTransactionCoordinator\\\", \\\"Win32_System_Environment\\\", \\\"Win32_System_ErrorReporting\\\", \\\"Win32_System_EventCollector\\\", \\\"Win32_System_EventLog\\\", \\\"Win32_System_EventNotificationService\\\", \\\"Win32_System_GroupPolicy\\\", \\\"Win32_System_HostCompute\\\", \\\"Win32_System_HostComputeNetwork\\\", \\\"Win32_System_HostComputeSystem\\\", \\\"Win32_System_Hypervisor\\\", \\\"Win32_System_IO\\\", \\\"Win32_System_Iis\\\", \\\"Win32_System_Ioctl\\\", \\\"Win32_System_JobObjects\\\", \\\"Win32_System_Js\\\", \\\"Win32_System_Kernel\\\", \\\"Win32_System_LibraryLoader\\\", \\\"Win32_System_Mailslots\\\", \\\"Win32_System_Mapi\\\", \\\"Win32_System_Memory\\\", \\\"Win32_System_Memory_NonVolatile\\\", \\\"Win32_System_MessageQueuing\\\", \\\"Win32_System_MixedReality\\\", \\\"Win32_System_Ole\\\", \\\"Win32_System_PasswordManagement\\\", \\\"Win32_System_Performance\\\", \\\"Win32_System_Performance_HardwareCounterProfiling\\\", \\\"Win32_System_Pipes\\\", \\\"Win32_System_Power\\\", \\\"Win32_System_ProcessStatus\\\", \\\"Win32_System_Recovery\\\", \\\"Win32_System_Registry\\\", \\\"Win32_System_RemoteDesktop\\\", \\\"Win32_System_RemoteManagement\\\", \\\"Win32_System_RestartManager\\\", \\\"Win32_System_Restore\\\", \\\"Win32_System_Rpc\\\", \\\"Win32_System_Search\\\", \\\"Win32_System_Search_Common\\\", \\\"Win32_System_SecurityCenter\\\", \\\"Win32_System_Services\\\", \\\"Win32_System_SetupAndMigration\\\", \\\"Win32_System_Shutdown\\\", \\\"Win32_System_StationsAndDesktops\\\", \\\"Win32_System_SubsystemForLinux\\\", \\\"Win32_System_SystemInformation\\\", \\\"Win32_System_SystemServices\\\", \\\"Win32_System_Threading\\\", \\\"Win32_System_Time\\\", \\\"Win32_System_TpmBaseServices\\\", \\\"Win32_System_UserAccessLogging\\\", \\\"Win32_System_Variant\\\", \\\"Win32_System_VirtualDosMachines\\\", \\\"Win32_System_WindowsProgramming\\\", \\\"Win32_System_Wmi\\\", \\\"Win32_UI\\\", \\\"Win32_UI_Accessibility\\\", \\\"Win32_UI_ColorSystem\\\", \\\"Win32_UI_Controls\\\", \\\"Win32_UI_Controls_Dialogs\\\", \\\"Win32_UI_HiDpi\\\", \\\"Win32_UI_Input\\\", \\\"Win32_UI_Input_Ime\\\", \\\"Win32_UI_Input_KeyboardAndMouse\\\", \\\"Win32_UI_Input_Pointer\\\", \\\"Win32_UI_Input_Touch\\\", \\\"Win32_UI_Input_XboxController\\\", \\\"Win32_UI_InteractionContext\\\", \\\"Win32_UI_Magnification\\\", \\\"Win32_UI_Shell\\\", \\\"Win32_UI_Shell_Common\\\", \\\"Win32_UI_Shell_PropertiesSystem\\\", \\\"Win32_UI_TabletPC\\\", \\\"Win32_UI_TextServices\\\", \\\"Win32_UI_WindowsAndMessaging\\\", \\\"Win32_Web\\\", \\\"Win32_Web_InternetExplorer\\\", \\\"default\\\", \\\"docs\\\"))\" -C metadata=badd2551c5aed9ed -C extra-filename=-318e9bc24ee987c1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --extern windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_targets-b170585257b0d7b4.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_sys",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.59.0\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--warn=rust_2018_idioms",
        "--warn=unexpected_cfgs",
        "--warn=missing_docs",
        "--check-cfg",
        "cfg(windows_raw_dylib, windows_debugger_visualizer, windows_slim_errors)",
        "--cfg",
        "feature=\"Win32\"",
        "--cfg",
        "feature=\"Win32_Foundation\"",
        "--cfg",
        "feature=\"Win32_NetworkManagement\"",
        "--cfg",
        "feature=\"Win32_NetworkManagement_IpHelper\"",
        "--cfg",
        "feature=\"Win32_Networking\"",
        "--cfg",
        "feature=\"Win32_Networking_WinSock\"",
        "--cfg",
        "feature=\"Win32_System\"",
        "--cfg",
        "feature=\"Win32_System_Diagnostics\"",
        "--cfg",
        "feature=\"Win32_System_Diagnostics_Debug\"",
        "--cfg",
        "feature=\"Win32_System_Threading\"",
        "--cfg",
        "feature=\"default\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"Wdk\", \"Wdk_Devices\", \"Wdk_Devices_Bluetooth\", \"Wdk_Devices_HumanInterfaceDevice\", \"Wdk_Foundation\", \"Wdk_Graphics\", \"Wdk_Graphics_Direct3D\", \"Wdk_NetworkManagement\", \"Wdk_NetworkManagement_Ndis\", \"Wdk_NetworkManagement_WindowsFilteringPlatform\", \"Wdk_Storage\", \"Wdk_Storage_FileSystem\", \"Wdk_Storage_FileSystem_Minifilters\", \"Wdk_System\", \"Wdk_System_IO\", \"Wdk_System_Memory\", \"Wdk_System_OfflineRegistry\", \"Wdk_System_Registry\", \"Wdk_System_SystemInformation\", \"Wdk_System_SystemServices\", \"Wdk_System_Threading\", \"Win32\", \"Win32_Data\", \"Win32_Data_HtmlHelp\", \"Win32_Data_RightsManagement\", \"Win32_Devices\", \"Win32_Devices_AllJoyn\", \"Win32_Devices_BiometricFramework\", \"Win32_Devices_Bluetooth\", \"Win32_Devices_Communication\", \"Win32_Devices_DeviceAndDriverInstallation\", \"Win32_Devices_DeviceQuery\", \"Win32_Devices_Display\", \"Win32_Devices_Enumeration\", \"Win32_Devices_Enumeration_Pnp\", \"Win32_Devices_Fax\", \"Win32_Devices_HumanInterfaceDevice\", \"Win32_Devices_PortableDevices\", \"Win32_Devices_Properties\", \"Win32_Devices_Pwm\", \"Win32_Devices_Sensors\", \"Win32_Devices_SerialCommunication\", \"Win32_Devices_Tapi\", \"Win32_Devices_Usb\", \"Win32_Devices_WebServicesOnDevices\", \"Win32_Foundation\", \"Win32_Gaming\", \"Win32_Globalization\", \"Win32_Graphics\", \"Win32_Graphics_Dwm\", \"Win32_Graphics_Gdi\", \"Win32_Graphics_GdiPlus\", \"Win32_Graphics_Hlsl\", \"Win32_Graphics_OpenGL\", \"Win32_Graphics_Printing\", \"Win32_Graphics_Printing_PrintTicket\", \"Win32_Management\", \"Win32_Management_MobileDeviceManagementRegistration\", \"Win32_Media\", \"Win32_Media_Audio\", \"Win32_Media_DxMediaObjects\", \"Win32_Media_KernelStreaming\", \"Win32_Media_Multimedia\", \"Win32_Media_Streaming\", \"Win32_Media_WindowsMediaFormat\", \"Win32_NetworkManagement\", \"Win32_NetworkManagement_Dhcp\", \"Win32_NetworkManagement_Dns\", \"Win32_NetworkManagement_InternetConnectionWizard\", \"Win32_NetworkManagement_IpHelper\", \"Win32_NetworkManagement_Multicast\", \"Win32_NetworkManagement_Ndis\", \"Win32_NetworkManagement_NetBios\", \"Win32_NetworkManagement_NetManagement\", \"Win32_NetworkManagement_NetShell\", \"Win32_NetworkManagement_NetworkDiagnosticsFramework\", \"Win32_NetworkManagement_P2P\", \"Win32_NetworkManagement_QoS\", \"Win32_NetworkManagement_Rras\", \"Win32_NetworkManagement_Snmp\", \"Win32_NetworkManagement_WNet\", \"Win32_NetworkManagement_WebDav\", \"Win32_NetworkManagement_WiFi\", \"Win32_NetworkManagement_WindowsConnectionManager\", \"Win32_NetworkManagement_WindowsFilteringPlatform\", \"Win32_NetworkManagement_WindowsFirewall\", \"Win32_NetworkManagement_WindowsNetworkVirtualization\", \"Win32_Networking\", \"Win32_Networking_ActiveDirectory\", \"Win32_Networking_Clustering\", \"Win32_Networking_HttpServer\", \"Win32_Networking_Ldap\", \"Win32_Networking_WebSocket\", \"Win32_Networking_WinHttp\", \"Win32_Networking_WinInet\", \"Win32_Networking_WinSock\", \"Win32_Networking_WindowsWebServices\", \"Win32_Security\", \"Win32_Security_AppLocker\", \"Win32_Security_Authentication\", \"Win32_Security_Authentication_Identity\", \"Win32_Security_Authorization\", \"Win32_Security_Credentials\", \"Win32_Security_Cryptography\", \"Win32_Security_Cryptography_Catalog\", \"Win32_Security_Cryptography_Certificates\", \"Win32_Security_Cryptography_Sip\", \"Win32_Security_Cryptography_UI\", \"Win32_Security_DiagnosticDataQuery\", \"Win32_Security_DirectoryServices\", \"Win32_Security_EnterpriseData\", \"Win32_Security_ExtensibleAuthenticationProtocol\", \"Win32_Security_Isolation\", \"Win32_Security_LicenseProtection\", \"Win32_Security_NetworkAccessProtection\", \"Win32_Security_WinTrust\", \"Win32_Security_WinWlx\", \"Win32_Storage\", \"Win32_Storage_Cabinets\", \"Win32_Storage_CloudFilters\", \"Win32_Storage_Compression\", \"Win32_Storage_DistributedFileSystem\", \"Win32_Storage_FileHistory\", \"Win32_Storage_FileSystem\", \"Win32_Storage_Imapi\", \"Win32_Storage_IndexServer\", \"Win32_Storage_InstallableFileSystems\", \"Win32_Storage_IscsiDisc\", \"Win32_Storage_Jet\", \"Win32_Storage_Nvme\", \"Win32_Storage_OfflineFiles\", \"Win32_Storage_OperationRecorder\", \"Win32_Storage_Packaging\", \"Win32_Storage_Packaging_Appx\", \"Win32_Storage_ProjectedFileSystem\", \"Win32_Storage_StructuredStorage\", \"Win32_Storage_Vhd\", \"Win32_Storage_Xps\", \"Win32_System\", \"Win32_System_AddressBook\", \"Win32_System_Antimalware\", \"Win32_System_ApplicationInstallationAndServicing\", \"Win32_System_ApplicationVerifier\", \"Win32_System_ClrHosting\", \"Win32_System_Com\", \"Win32_System_Com_Marshal\", \"Win32_System_Com_StructuredStorage\", \"Win32_System_Com_Urlmon\", \"Win32_System_ComponentServices\", \"Win32_System_Console\", \"Win32_System_CorrelationVector\", \"Win32_System_DataExchange\", \"Win32_System_DeploymentServices\", \"Win32_System_DeveloperLicensing\", \"Win32_System_Diagnostics\", \"Win32_System_Diagnostics_Ceip\", \"Win32_System_Diagnostics_Debug\", \"Win32_System_Diagnostics_Debug_Extensions\", \"Win32_System_Diagnostics_Etw\", \"Win32_System_Diagnostics_ProcessSnapshotting\", \"Win32_System_Diagnostics_ToolHelp\", \"Win32_System_Diagnostics_TraceLogging\", \"Win32_System_DistributedTransactionCoordinator\", \"Win32_System_Environment\", \"Win32_System_ErrorReporting\", \"Win32_System_EventCollector\", \"Win32_System_EventLog\", \"Win32_System_EventNotificationService\", \"Win32_System_GroupPolicy\", \"Win32_System_HostCompute\", \"Win32_System_HostComputeNetwork\", \"Win32_System_HostComputeSystem\", \"Win32_System_Hypervisor\", \"Win32_System_IO\", \"Win32_System_Iis\", \"Win32_System_Ioctl\", \"Win32_System_JobObjects\", \"Win32_System_Js\", \"Win32_System_Kernel\", \"Win32_System_LibraryLoader\", \"Win32_System_Mailslots\", \"Win32_System_Mapi\", \"Win32_System_Memory\", \"Win32_System_Memory_NonVolatile\", \"Win32_System_MessageQueuing\", \"Win32_System_MixedReality\", \"Win32_System_Ole\", \"Win32_System_PasswordManagement\", \"Win32_System_Performance\", \"Win32_System_Performance_HardwareCounterProfiling\", \"Win32_System_Pipes\", \"Win32_System_Power\", \"Win32_System_ProcessStatus\", \"Win32_System_Recovery\", \"Win32_System_Registry\", \"Win32_System_RemoteDesktop\", \"Win32_System_RemoteManagement\", \"Win32_System_RestartManager\", \"Win32_System_Restore\", \"Win32_System_Rpc\", \"Win32_System_Search\", \"Win32_System_Search_Common\", \"Win32_System_SecurityCenter\", \"Win32_System_Services\", \"Win32_System_SetupAndMigration\", \"Win32_System_Shutdown\", \"Win32_System_StationsAndDesktops\", \"Win32_System_SubsystemForLinux\", \"Win32_System_SystemInformation\", \"Win32_System_SystemServices\", \"Win32_System_Threading\", \"Win32_System_Time\", \"Win32_System_TpmBaseServices\", \"Win32_System_UserAccessLogging\", \"Win32_System_Variant\", \"Win32_System_VirtualDosMachines\", \"Win32_System_WindowsProgramming\", \"Win32_System_Wmi\", \"Win32_UI\", \"Win32_UI_Accessibility\", \"Win32_UI_ColorSystem\", \"Win32_UI_Controls\", \"Win32_UI_Controls_Dialogs\", \"Win32_UI_HiDpi\", \"Win32_UI_Input\", \"Win32_UI_Input_Ime\", \"Win32_UI_Input_KeyboardAndMouse\", \"Win32_UI_Input_Pointer\", \"Win32_UI_Input_Touch\", \"Win32_UI_Input_XboxController\", \"Win32_UI_InteractionContext\", \"Win32_UI_Magnification\", \"Win32_UI_Shell\", \"Win32_UI_Shell_Common\", \"Win32_UI_Shell_PropertiesSystem\", \"Win32_UI_TabletPC\", \"Win32_UI_TextServices\", \"Win32_UI_WindowsAndMessaging\", \"Win32_Web\", \"Win32_Web_InternetExplorer\", \"default\", \"docs\"))",
        "-C",
        "metadata=badd2551c5aed9ed",
        "-C",
        "extra-filename=-318e9bc24ee987c1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--extern",
        "windows_targets=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_targets-b170585257b0d7b4.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:17.047169+00:00",
      "end_time": "2026-07-13T14:49:17.756696+00:00",
      "start_unix_nanos": 1783954157047169300,
      "end_unix_nanos": 1783954157756695600,
      "crate_name": "windows_sys",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 3216,
      "ppid": 8804,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-type=rlib",
        "--emit=metadata",
        "--target",
        "x86_64-pc-windows-msvc",
        "-o",
        "-",
        "-"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-type=rlib --emit=metadata --target x86_64-pc-windows-msvc -o - -",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-type=rlib",
        "--emit=metadata",
        "--target",
        "x86_64-pc-windows-msvc",
        "-o",
        "-",
        "-"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:17.369683+00:00",
      "end_time": "2026-07-13T14:49:17.406722+00:00",
      "start_unix_nanos": 1783954157369683100,
      "end_unix_nanos": 1783954157406721600,
      "crate_name": null,
      "crate_type": [
        "rlib"
      ],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 12656,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "errno",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10\\src\\lib.rs",
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
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=d9f10fd880b36604",
        "-C",
        "extra-filename=-405a592150f745eb",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--extern",
        "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name errno --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=d9f10fd880b36604 -C extra-filename=-405a592150f745eb --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --extern windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta --cap-lints allow -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "errno",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.10\\src\\lib.rs",
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
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=d9f10fd880b36604",
        "-C",
        "extra-filename=-405a592150f745eb",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--extern",
        "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta",
        "--cap-lints",
        "allow",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:17.702375+00:00",
      "end_time": "2026-07-13T14:49:17.841838+00:00",
      "start_unix_nanos": 1783954157702375500,
      "end_unix_nanos": 1783954157841838300,
      "crate_name": "errno",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "rustix:0.38.44:13136",
      "root_process_pid": 2908,
      "pid": 16364,
      "ppid": 10292,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "rustix",
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
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(alloc_c_string)",
        "--check-cfg",
        "cfg(alloc_ffi)",
        "--check-cfg",
        "cfg(apple)",
        "--check-cfg",
        "cfg(asm_experimental_arch)",
        "--check-cfg",
        "cfg(bsd)",
        "--check-cfg",
        "cfg(core_c_str)",
        "--check-cfg",
        "cfg(core_ffi_c)",
        "--check-cfg",
        "cfg(core_intrinsics)",
        "--check-cfg",
        "cfg(criterion)",
        "--check-cfg",
        "cfg(document_experimental_runtime_api)",
        "--check-cfg",
        "cfg(fix_y2038)",
        "--check-cfg",
        "cfg(freebsdlike)",
        "--check-cfg",
        "cfg(libc)",
        "--check-cfg",
        "cfg(linux_kernel)",
        "--check-cfg",
        "cfg(linux_like)",
        "--check-cfg",
        "cfg(linux_raw)",
        "--check-cfg",
        "cfg(netbsdlike)",
        "--check-cfg",
        "cfg(rustc_attrs)",
        "--check-cfg",
        "cfg(solarish)",
        "--check-cfg",
        "cfg(staged_api)",
        "--check-cfg",
        "cfg(static_assertions)",
        "--check-cfg",
        "cfg(thumb_mode)",
        "--check-cfg",
        "cfg(wasi)",
        "--check-cfg",
        "cfg(wasi_ext)",
        "--check-cfg",
        "cfg(target_arch, values(\"xtensa\"))",
        "--cfg",
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"libc-extra-traits\"",
        "--cfg",
        "feature=\"std\"",
        "--cfg",
        "feature=\"use-libc-auxv\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"all-apis\", \"alloc\", \"cc\", \"compiler_builtins\", \"core\", \"default\", \"event\", \"fs\", \"io_uring\", \"itoa\", \"libc\", \"libc-extra-traits\", \"libc_errno\", \"linux_4_11\", \"linux_latest\", \"mm\", \"mount\", \"net\", \"once_cell\", \"param\", \"pipe\", \"process\", \"procfs\", \"pty\", \"rand\", \"runtime\", \"rustc-dep-of-std\", \"rustc-std-workspace-alloc\", \"shm\", \"std\", \"stdio\", \"system\", \"termios\", \"thread\", \"time\", \"try_close\", \"use-explicitly-provided-auxv\", \"use-libc\", \"use-libc-auxv\"))",
        "-C",
        "metadata=764e1e143a9009b6",
        "-C",
        "extra-filename=-4bf43304fd3c21e8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--extern",
        "bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libbitflags-4db8ea0490b59b49.rmeta",
        "--extern",
        "libc_errno=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\liberrno-405a592150f745eb.rmeta",
        "--extern",
        "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
        "--cfg",
        "static_assertions",
        "--cfg",
        "libc"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name rustix --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg cfg(apple) --check-cfg cfg(asm_experimental_arch) --check-cfg cfg(bsd) --check-cfg cfg(core_c_str) --check-cfg cfg(core_ffi_c) --check-cfg cfg(core_intrinsics) --check-cfg cfg(criterion) --check-cfg cfg(document_experimental_runtime_api) --check-cfg cfg(fix_y2038) --check-cfg cfg(freebsdlike) --check-cfg cfg(libc) --check-cfg cfg(linux_kernel) --check-cfg cfg(linux_like) --check-cfg cfg(linux_raw) --check-cfg cfg(netbsdlike) --check-cfg cfg(rustc_attrs) --check-cfg cfg(solarish) --check-cfg cfg(staged_api) --check-cfg cfg(static_assertions) --check-cfg cfg(thumb_mode) --check-cfg cfg(wasi) --check-cfg cfg(wasi_ext) --check-cfg \"cfg(target_arch, values(\\\"xtensa\\\"))\" --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"libc-extra-traits\\\"\" --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"use-libc-auxv\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"all-apis\\\", \\\"alloc\\\", \\\"cc\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"event\\\", \\\"fs\\\", \\\"io_uring\\\", \\\"itoa\\\", \\\"libc\\\", \\\"libc-extra-traits\\\", \\\"libc_errno\\\", \\\"linux_4_11\\\", \\\"linux_latest\\\", \\\"mm\\\", \\\"mount\\\", \\\"net\\\", \\\"once_cell\\\", \\\"param\\\", \\\"pipe\\\", \\\"process\\\", \\\"procfs\\\", \\\"pty\\\", \\\"rand\\\", \\\"runtime\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-alloc\\\", \\\"shm\\\", \\\"std\\\", \\\"stdio\\\", \\\"system\\\", \\\"termios\\\", \\\"thread\\\", \\\"time\\\", \\\"try_close\\\", \\\"use-explicitly-provided-auxv\\\", \\\"use-libc\\\", \\\"use-libc-auxv\\\"))\" -C metadata=764e1e143a9009b6 -C extra-filename=-4bf43304fd3c21e8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps --extern bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libbitflags-4db8ea0490b59b49.rmeta --extern libc_errno=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\liberrno-405a592150f745eb.rmeta --extern windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta -L native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib --cfg static_assertions --cfg libc",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "rustix",
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
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(alloc_c_string)",
        "--check-cfg",
        "cfg(alloc_ffi)",
        "--check-cfg",
        "cfg(apple)",
        "--check-cfg",
        "cfg(asm_experimental_arch)",
        "--check-cfg",
        "cfg(bsd)",
        "--check-cfg",
        "cfg(core_c_str)",
        "--check-cfg",
        "cfg(core_ffi_c)",
        "--check-cfg",
        "cfg(core_intrinsics)",
        "--check-cfg",
        "cfg(criterion)",
        "--check-cfg",
        "cfg(document_experimental_runtime_api)",
        "--check-cfg",
        "cfg(fix_y2038)",
        "--check-cfg",
        "cfg(freebsdlike)",
        "--check-cfg",
        "cfg(libc)",
        "--check-cfg",
        "cfg(linux_kernel)",
        "--check-cfg",
        "cfg(linux_like)",
        "--check-cfg",
        "cfg(linux_raw)",
        "--check-cfg",
        "cfg(netbsdlike)",
        "--check-cfg",
        "cfg(rustc_attrs)",
        "--check-cfg",
        "cfg(solarish)",
        "--check-cfg",
        "cfg(staged_api)",
        "--check-cfg",
        "cfg(static_assertions)",
        "--check-cfg",
        "cfg(thumb_mode)",
        "--check-cfg",
        "cfg(wasi)",
        "--check-cfg",
        "cfg(wasi_ext)",
        "--check-cfg",
        "cfg(target_arch, values(\"xtensa\"))",
        "--cfg",
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"libc-extra-traits\"",
        "--cfg",
        "feature=\"std\"",
        "--cfg",
        "feature=\"use-libc-auxv\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"all-apis\", \"alloc\", \"cc\", \"compiler_builtins\", \"core\", \"default\", \"event\", \"fs\", \"io_uring\", \"itoa\", \"libc\", \"libc-extra-traits\", \"libc_errno\", \"linux_4_11\", \"linux_latest\", \"mm\", \"mount\", \"net\", \"once_cell\", \"param\", \"pipe\", \"process\", \"procfs\", \"pty\", \"rand\", \"runtime\", \"rustc-dep-of-std\", \"rustc-std-workspace-alloc\", \"shm\", \"std\", \"stdio\", \"system\", \"termios\", \"thread\", \"time\", \"try_close\", \"use-explicitly-provided-auxv\", \"use-libc\", \"use-libc-auxv\"))",
        "-C",
        "metadata=764e1e143a9009b6",
        "-C",
        "extra-filename=-4bf43304fd3c21e8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps",
        "--extern",
        "bitflags=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libbitflags-4db8ea0490b59b49.rmeta",
        "--extern",
        "libc_errno=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\liberrno-405a592150f745eb.rmeta",
        "--extern",
        "windows_sys=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps\\libwindows_sys-318e9bc24ee987c1.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows_x86_64_msvc-0.52.6\\lib",
        "--cfg",
        "static_assertions",
        "--cfg",
        "libc"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:49:17.768754+00:00",
      "end_time": "2026-07-13T14:49:18.071309+00:00",
      "start_unix_nanos": 1783954157768753500,
      "end_unix_nanos": 1783954158071309100,
      "crate_name": "rustix",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-3mdw8r9b\\src\\rustix-0.38.44\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 260,
    "crate": "rustix",
    "version": "0.38.44",
    "crate_id": "473904",
    "version_id": "1416989",
    "downloads": 113500445,
    "cumulative_downloads": 50896180221,
    "cumulative_share_of_global": 0.190289068167145,
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
