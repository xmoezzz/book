# `proxy-wasm` `0.2.3`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "proxy-wasm",
    "version": "0.2.3",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 000000014001c148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001c198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001c1b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001c1d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001c1e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001c1f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001c288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001c2a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  000000014001c2b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-link-link-19188-1783962214584243100.map",
  "pid": 19188,
  "ppid": 7444,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-link-link-19188-1783962214584243100.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "proxy-wasm",
    "version": "0.2.3",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#allocator-api2@0.2.21",
      "name": "allocator-api2",
      "version": "0.2.21",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
      "name": "equivalent",
      "version": "1.0.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#foldhash@0.1.5",
      "name": "foldhash",
      "version": "0.1.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.15.3",
      "name": "hashbrown",
      "version": "0.15.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.27",
      "name": "log",
      "version": "0.4.27",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
      "name": "proxy-wasm",
      "version": "0.2.3",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "exit_code": 0,
  "kind": "exec",
  "pid": 19188,
  "ppid": 7444,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "proxy-wasm",
    "version": "0.2.3",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "proxy-wasm",
    "version": "0.2.3",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "cargo_pkg_name": "proxy-wasm",
  "cargo_pkg_version": "0.2.3",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 19188,
  "ppid": 7444,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "_owner": {
    "crate": "proxy-wasm",
    "version": "0.2.3",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 000000014001c148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001c198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001c1b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001c1d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001c1e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001c1f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001c288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001c2a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  000000014001c2b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-link-link-19188-1783962214584243100.map",
  "pid": 19188,
  "ppid": 7444,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-link-link-19188-1783962214584243100.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "proxy-wasm",
    "version": "0.2.3",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
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
  "raw_event_count": 52410,
  "parsed_event_count": 52296,
  "parse_error_count": 0,
  "command_line_event_count": 52296,
  "build_script_root_event_count": 782,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 11329,
  "dropped_event_count": 27090
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7552,
  "ppid": 14884,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T17:03:35.076325+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\build-script-build.exe",
  "root_cargo_pid": 3732,
  "build_script_root_pid": 7552,
  "build_script_related": true,
  "build_script_target_dir": "proxy-wasm-87f660aca12eb9c8"
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 14988,
  "ppid": 11392,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
  "time": "2026-07-13T17:03:34.043282+00:00",
  "end_time": "2026-07-13T17:03:34.065935+00:00",
  "start_unix_nanos": 1783962214043281500,
  "end_unix_nanos": 1783962214065935000,
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 13172,
  "ppid": 11392,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
  "time": "2026-07-13T17:03:34.073101+00:00",
  "end_time": "2026-07-13T17:03:34.093674+00:00",
  "start_unix_nanos": 1783962214073100600,
  "end_unix_nanos": 1783962214093673800,
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 1212,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
  "time": "2026-07-13T17:03:34.178439+00:00",
  "end_time": "2026-07-13T17:03:34.202184+00:00",
  "start_unix_nanos": 1783962214178438900,
  "end_unix_nanos": 1783962214202184000,
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 10540,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
  "time": "2026-07-13T17:03:34.209535+00:00",
  "end_time": "2026-07-13T17:03:34.233744+00:00",
  "start_unix_nanos": 1783962214209535100,
  "end_unix_nanos": 1783962214233743600,
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 10720,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
  "time": "2026-07-13T17:03:34.312578+00:00",
  "end_time": "2026-07-13T17:03:34.339296+00:00",
  "start_unix_nanos": 1783962214312578100,
  "end_unix_nanos": 1783962214339296200,
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 4092,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "allocator_api2",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21\\src\\lib.rs",
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
    "cfg(no_global_oom_handling)",
    "--cfg",
    "feature=\"alloc\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"fresh-rust\", \"nightly\", \"serde\", \"std\"))",
    "-C",
    "metadata=21b2c5a34acff3ad",
    "-C",
    "extra-filename=-2a8f64255b7efe9c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name allocator_api2 --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(no_global_oom_handling) --cfg \"feature=\\\"alloc\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"fresh-rust\\\", \\\"nightly\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=21b2c5a34acff3ad -C extra-filename=-2a8f64255b7efe9c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "allocator_api2",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21\\src\\lib.rs",
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
    "cfg(no_global_oom_handling)",
    "--cfg",
    "feature=\"alloc\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"fresh-rust\", \"nightly\", \"serde\", \"std\"))",
    "-C",
    "metadata=21b2c5a34acff3ad",
    "-C",
    "extra-filename=-2a8f64255b7efe9c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:34.356764+00:00",
  "end_time": "2026-07-13T17:03:34.781439+00:00",
  "start_unix_nanos": 1783962214356764400,
  "end_unix_nanos": 1783962214781438500,
  "crate_name": "allocator_api2",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 20696,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "equivalent",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\src\\lib.rs",
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
    "metadata=3fb0bd604e6f7716",
    "-C",
    "extra-filename=-b19a42cd8c2442b0",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name equivalent --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=3fb0bd604e6f7716 -C extra-filename=-b19a42cd8c2442b0 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "equivalent",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\src\\lib.rs",
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
    "metadata=3fb0bd604e6f7716",
    "-C",
    "extra-filename=-b19a42cd8c2442b0",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:34.359229+00:00",
  "end_time": "2026-07-13T17:03:34.421303+00:00",
  "start_unix_nanos": 1783962214359229200,
  "end_unix_nanos": 1783962214421302500,
  "crate_name": "equivalent",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 596,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "foldhash",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5\\src\\lib.rs",
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
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=a60459b1438dba0f",
    "-C",
    "extra-filename=-e0e750b5d57e29ec",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name foldhash --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=a60459b1438dba0f -C extra-filename=-e0e750b5d57e29ec --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "foldhash",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5\\src\\lib.rs",
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
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=a60459b1438dba0f",
    "-C",
    "extra-filename=-e0e750b5d57e29ec",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:34.361864+00:00",
  "end_time": "2026-07-13T17:03:34.527068+00:00",
  "start_unix_nanos": 1783962214361864100,
  "end_unix_nanos": 1783962214527067800,
  "crate_name": "foldhash",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 11028,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
    "metadata=ba992d5acd1915c9",
    "-C",
    "extra-filename=-87f660aca12eb9c8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=ba992d5acd1915c9 -C extra-filename=-87f660aca12eb9c8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
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
    "metadata=ba992d5acd1915c9",
    "-C",
    "extra-filename=-87f660aca12eb9c8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:34.364472+00:00",
  "end_time": "2026-07-13T17:03:34.996326+00:00",
  "start_unix_nanos": 1783962214364471800,
  "end_unix_nanos": 1783962214996326500,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8"
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 19516,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "log",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27\\src\\lib.rs",
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
    "cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_error\", \"max_level_info\", \"max_level_off\", \"max_level_trace\", \"max_level_warn\", \"release_max_level_debug\", \"release_max_level_error\", \"release_max_level_info\", \"release_max_level_off\", \"release_max_level_trace\", \"release_max_level_warn\", \"serde\", \"std\", \"sval\", \"sval_ref\", \"value-bag\"))",
    "-C",
    "metadata=2537051d17599cdb",
    "-C",
    "extra-filename=-c247e66842f1b865",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name log --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"kv\\\", \\\"kv_serde\\\", \\\"kv_std\\\", \\\"kv_sval\\\", \\\"kv_unstable\\\", \\\"kv_unstable_serde\\\", \\\"kv_unstable_std\\\", \\\"kv_unstable_sval\\\", \\\"max_level_debug\\\", \\\"max_level_error\\\", \\\"max_level_info\\\", \\\"max_level_off\\\", \\\"max_level_trace\\\", \\\"max_level_warn\\\", \\\"release_max_level_debug\\\", \\\"release_max_level_error\\\", \\\"release_max_level_info\\\", \\\"release_max_level_off\\\", \\\"release_max_level_trace\\\", \\\"release_max_level_warn\\\", \\\"serde\\\", \\\"std\\\", \\\"sval\\\", \\\"sval_ref\\\", \\\"value-bag\\\"))\" -C metadata=2537051d17599cdb -C extra-filename=-c247e66842f1b865 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "log",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27\\src\\lib.rs",
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
    "cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_error\", \"max_level_info\", \"max_level_off\", \"max_level_trace\", \"max_level_warn\", \"release_max_level_debug\", \"release_max_level_error\", \"release_max_level_info\", \"release_max_level_off\", \"release_max_level_trace\", \"release_max_level_warn\", \"serde\", \"std\", \"sval\", \"sval_ref\", \"value-bag\"))",
    "-C",
    "metadata=2537051d17599cdb",
    "-C",
    "extra-filename=-c247e66842f1b865",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:34.367466+00:00",
  "end_time": "2026-07-13T17:03:34.514344+00:00",
  "start_unix_nanos": 1783962214367465900,
  "end_unix_nanos": 1783962214514343500,
  "crate_name": "log",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 4224,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "hashbrown",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3\\src\\lib.rs",
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
    "feature=\"allocator-api2\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"default-hasher\"",
    "--cfg",
    "feature=\"equivalent\"",
    "--cfg",
    "feature=\"inline-more\"",
    "--cfg",
    "feature=\"raw-entry\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"allocator-api2\", \"compiler_builtins\", \"core\", \"default\", \"default-hasher\", \"equivalent\", \"inline-more\", \"nightly\", \"raw-entry\", \"rayon\", \"rustc-dep-of-std\", \"rustc-internal-api\", \"serde\"))",
    "-C",
    "metadata=f922be269ffb0ca2",
    "-C",
    "extra-filename=-87144cce35d37a78",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--extern",
    "allocator_api2=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liballocator_api2-2a8f64255b7efe9c.rmeta",
    "--extern",
    "equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libequivalent-b19a42cd8c2442b0.rmeta",
    "--extern",
    "foldhash=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libfoldhash-e0e750b5d57e29ec.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name hashbrown --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"allocator-api2\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"default-hasher\\\"\" --cfg \"feature=\\\"equivalent\\\"\" --cfg \"feature=\\\"inline-more\\\"\" --cfg \"feature=\\\"raw-entry\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"allocator-api2\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"default-hasher\\\", \\\"equivalent\\\", \\\"inline-more\\\", \\\"nightly\\\", \\\"raw-entry\\\", \\\"rayon\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-internal-api\\\", \\\"serde\\\"))\" -C metadata=f922be269ffb0ca2 -C extra-filename=-87144cce35d37a78 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --extern allocator_api2=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liballocator_api2-2a8f64255b7efe9c.rmeta --extern equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libequivalent-b19a42cd8c2442b0.rmeta --extern foldhash=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libfoldhash-e0e750b5d57e29ec.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "hashbrown",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3\\src\\lib.rs",
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
    "feature=\"allocator-api2\"",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"default-hasher\"",
    "--cfg",
    "feature=\"equivalent\"",
    "--cfg",
    "feature=\"inline-more\"",
    "--cfg",
    "feature=\"raw-entry\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"allocator-api2\", \"compiler_builtins\", \"core\", \"default\", \"default-hasher\", \"equivalent\", \"inline-more\", \"nightly\", \"raw-entry\", \"rayon\", \"rustc-dep-of-std\", \"rustc-internal-api\", \"serde\"))",
    "-C",
    "metadata=f922be269ffb0ca2",
    "-C",
    "extra-filename=-87144cce35d37a78",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--extern",
    "allocator_api2=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liballocator_api2-2a8f64255b7efe9c.rmeta",
    "--extern",
    "equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libequivalent-b19a42cd8c2442b0.rmeta",
    "--extern",
    "foldhash=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libfoldhash-e0e750b5d57e29ec.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:34.747428+00:00",
  "end_time": "2026-07-13T17:03:35.195297+00:00",
  "start_unix_nanos": 1783962214747428300,
  "end_unix_nanos": 1783962215195297000,
  "crate_name": "hashbrown",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
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
  "run_id": "proxy-wasm:0.2.3:17260",
  "root_process_pid": 3732,
  "pid": 9228,
  "ppid": 14884,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "proxy_wasm",
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
    "metadata=592468110d7e5876",
    "-C",
    "extra-filename=-5da93ba2803ffc11",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--extern",
    "hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libhashbrown-87144cce35d37a78.rmeta",
    "--extern",
    "log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liblog-c247e66842f1b865.rmeta",
    "--check-cfg",
    "cfg(nightly)",
    "--check-cfg",
    "cfg(wasi_exec_model_reactor)"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name proxy_wasm --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=592468110d7e5876 -C extra-filename=-5da93ba2803ffc11 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --extern hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libhashbrown-87144cce35d37a78.rmeta --extern log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liblog-c247e66842f1b865.rmeta --check-cfg cfg(nightly) --check-cfg cfg(wasi_exec_model_reactor)",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "proxy_wasm",
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
    "metadata=592468110d7e5876",
    "-C",
    "extra-filename=-5da93ba2803ffc11",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
    "--extern",
    "hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libhashbrown-87144cce35d37a78.rmeta",
    "--extern",
    "log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liblog-c247e66842f1b865.rmeta",
    "--check-cfg",
    "cfg(nightly)",
    "--check-cfg",
    "cfg(wasi_exec_model_reactor)"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:35.147793+00:00",
  "end_time": "2026-07-13T17:03:36.178854+00:00",
  "start_unix_nanos": 1783962215147792700,
  "end_unix_nanos": 1783962216178854500,
  "crate_name": "proxy_wasm",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T17:03:37.218118+00:00",
  "crate": "proxy-wasm",
  "version": "0.2.3",
  "duration_seconds": 25.93120969994925,
  "trace_record_count": 7,
  "trace_owner_summary": {
    "owner_package_count": 6,
    "owner_packages": [
      {
        "crate": "allocator-api2",
        "version": "0.2.21",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#allocator-api2@0.2.21",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/allocator-api2-0.2.21",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/allocator-api2-0.2.21/Cargo.toml"
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
        "version": "0.15.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.15.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.3/Cargo.toml"
      },
      {
        "crate": "foldhash",
        "version": "0.1.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#foldhash@0.1.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foldhash-0.1.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foldhash-0.1.5/Cargo.toml"
      },
      {
        "crate": "proxy-wasm",
        "version": "0.2.3",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.27",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.27",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.27",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.27/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "proxy-wasm",
        "version": "0.2.3",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#allocator-api2@0.2.21",
          "name": "allocator-api2",
          "version": "0.2.21",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
          "name": "equivalent",
          "version": "1.0.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#foldhash@0.1.5",
          "name": "foldhash",
          "version": "0.1.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.15.3",
          "name": "hashbrown",
          "version": "0.15.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.27",
          "name": "log",
          "version": "0.4.27",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
          "name": "proxy-wasm",
          "version": "0.2.3",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "exit_code": 0,
      "kind": "exec",
      "pid": 19188,
      "ppid": 7444,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "proxy-wasm",
        "version": "0.2.3",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "proxy-wasm",
        "version": "0.2.3",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "cargo_pkg_name": "proxy-wasm",
      "cargo_pkg_version": "0.2.3",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 19188,
      "ppid": 7444,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "_owner": {
        "crate": "proxy-wasm",
        "version": "0.2.3",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-13452-1783962213800\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\rustcPME9BB\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000148       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000198       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001d0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002b8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000148       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 000000014001c148     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000198       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014001c198     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014001c1b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014001c1d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014001c1e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014001c1f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014001c288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014001c2a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  000000014001c2b8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-link-link-19188-1783962214584243100.map",
      "pid": 19188,
      "ppid": 7444,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\.tmp\\native-trace-link-link-19188-1783962214584243100.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "proxy-wasm",
        "version": "0.2.3",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3#proxy-wasm@0.2.3",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-1y4ysd7d/src/proxy-wasm-0.2.3",
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
      "raw_event_count": 52410,
      "parsed_event_count": 52296,
      "parse_error_count": 0,
      "command_line_event_count": 52296,
      "build_script_root_event_count": 782,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 11329,
      "dropped_event_count": 27090
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7552,
      "ppid": 14884,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T17:03:35.076325+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8\\build-script-build.exe",
      "root_cargo_pid": 3732,
      "build_script_root_pid": 7552,
      "build_script_related": true,
      "build_script_target_dir": "proxy-wasm-87f660aca12eb9c8"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 14988,
      "ppid": 11392,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
      "time": "2026-07-13T17:03:34.043282+00:00",
      "end_time": "2026-07-13T17:03:34.065935+00:00",
      "start_unix_nanos": 1783962214043281500,
      "end_unix_nanos": 1783962214065935000,
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
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 13172,
      "ppid": 11392,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
      "time": "2026-07-13T17:03:34.073101+00:00",
      "end_time": "2026-07-13T17:03:34.093674+00:00",
      "start_unix_nanos": 1783962214073100600,
      "end_unix_nanos": 1783962214093673800,
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
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 1212,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
      "time": "2026-07-13T17:03:34.178439+00:00",
      "end_time": "2026-07-13T17:03:34.202184+00:00",
      "start_unix_nanos": 1783962214178438900,
      "end_unix_nanos": 1783962214202184000,
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
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 10540,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
      "time": "2026-07-13T17:03:34.209535+00:00",
      "end_time": "2026-07-13T17:03:34.233744+00:00",
      "start_unix_nanos": 1783962214209535100,
      "end_unix_nanos": 1783962214233743600,
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
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 10720,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
      "time": "2026-07-13T17:03:34.312578+00:00",
      "end_time": "2026-07-13T17:03:34.339296+00:00",
      "start_unix_nanos": 1783962214312578100,
      "end_unix_nanos": 1783962214339296200,
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
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 4092,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "allocator_api2",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21\\src\\lib.rs",
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
        "cfg(no_global_oom_handling)",
        "--cfg",
        "feature=\"alloc\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"fresh-rust\", \"nightly\", \"serde\", \"std\"))",
        "-C",
        "metadata=21b2c5a34acff3ad",
        "-C",
        "extra-filename=-2a8f64255b7efe9c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name allocator_api2 --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(no_global_oom_handling) --cfg \"feature=\\\"alloc\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"fresh-rust\\\", \\\"nightly\\\", \\\"serde\\\", \\\"std\\\"))\" -C metadata=21b2c5a34acff3ad -C extra-filename=-2a8f64255b7efe9c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "allocator_api2",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\allocator-api2-0.2.21\\src\\lib.rs",
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
        "cfg(no_global_oom_handling)",
        "--cfg",
        "feature=\"alloc\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"fresh-rust\", \"nightly\", \"serde\", \"std\"))",
        "-C",
        "metadata=21b2c5a34acff3ad",
        "-C",
        "extra-filename=-2a8f64255b7efe9c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:34.356764+00:00",
      "end_time": "2026-07-13T17:03:34.781439+00:00",
      "start_unix_nanos": 1783962214356764400,
      "end_unix_nanos": 1783962214781438500,
      "crate_name": "allocator_api2",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 20696,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "equivalent",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\src\\lib.rs",
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
        "metadata=3fb0bd604e6f7716",
        "-C",
        "extra-filename=-b19a42cd8c2442b0",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name equivalent --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=3fb0bd604e6f7716 -C extra-filename=-b19a42cd8c2442b0 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "equivalent",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.2\\src\\lib.rs",
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
        "metadata=3fb0bd604e6f7716",
        "-C",
        "extra-filename=-b19a42cd8c2442b0",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:34.359229+00:00",
      "end_time": "2026-07-13T17:03:34.421303+00:00",
      "start_unix_nanos": 1783962214359229200,
      "end_unix_nanos": 1783962214421302500,
      "crate_name": "equivalent",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 596,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "foldhash",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5\\src\\lib.rs",
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
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=a60459b1438dba0f",
        "-C",
        "extra-filename=-e0e750b5d57e29ec",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name foldhash --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=a60459b1438dba0f -C extra-filename=-e0e750b5d57e29ec --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "foldhash",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\foldhash-0.1.5\\src\\lib.rs",
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
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=a60459b1438dba0f",
        "-C",
        "extra-filename=-e0e750b5d57e29ec",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:34.361864+00:00",
      "end_time": "2026-07-13T17:03:34.527068+00:00",
      "start_unix_nanos": 1783962214361864100,
      "end_unix_nanos": 1783962214527067800,
      "crate_name": "foldhash",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 11028,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
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
        "metadata=ba992d5acd1915c9",
        "-C",
        "extra-filename=-87f660aca12eb9c8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=ba992d5acd1915c9 -C extra-filename=-87f660aca12eb9c8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
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
        "metadata=ba992d5acd1915c9",
        "-C",
        "extra-filename=-87f660aca12eb9c8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:34.364472+00:00",
      "end_time": "2026-07-13T17:03:34.996326+00:00",
      "start_unix_nanos": 1783962214364471800,
      "end_unix_nanos": 1783962214996326500,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\build\\proxy-wasm-87f660aca12eb9c8"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 19516,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "log",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27\\src\\lib.rs",
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
        "cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_error\", \"max_level_info\", \"max_level_off\", \"max_level_trace\", \"max_level_warn\", \"release_max_level_debug\", \"release_max_level_error\", \"release_max_level_info\", \"release_max_level_off\", \"release_max_level_trace\", \"release_max_level_warn\", \"serde\", \"std\", \"sval\", \"sval_ref\", \"value-bag\"))",
        "-C",
        "metadata=2537051d17599cdb",
        "-C",
        "extra-filename=-c247e66842f1b865",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name log --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"kv\\\", \\\"kv_serde\\\", \\\"kv_std\\\", \\\"kv_sval\\\", \\\"kv_unstable\\\", \\\"kv_unstable_serde\\\", \\\"kv_unstable_std\\\", \\\"kv_unstable_sval\\\", \\\"max_level_debug\\\", \\\"max_level_error\\\", \\\"max_level_info\\\", \\\"max_level_off\\\", \\\"max_level_trace\\\", \\\"max_level_warn\\\", \\\"release_max_level_debug\\\", \\\"release_max_level_error\\\", \\\"release_max_level_info\\\", \\\"release_max_level_off\\\", \\\"release_max_level_trace\\\", \\\"release_max_level_warn\\\", \\\"serde\\\", \\\"std\\\", \\\"sval\\\", \\\"sval_ref\\\", \\\"value-bag\\\"))\" -C metadata=2537051d17599cdb -C extra-filename=-c247e66842f1b865 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "log",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\log-0.4.27\\src\\lib.rs",
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
        "cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_sval\", \"max_level_debug\", \"max_level_error\", \"max_level_info\", \"max_level_off\", \"max_level_trace\", \"max_level_warn\", \"release_max_level_debug\", \"release_max_level_error\", \"release_max_level_info\", \"release_max_level_off\", \"release_max_level_trace\", \"release_max_level_warn\", \"serde\", \"std\", \"sval\", \"sval_ref\", \"value-bag\"))",
        "-C",
        "metadata=2537051d17599cdb",
        "-C",
        "extra-filename=-c247e66842f1b865",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:34.367466+00:00",
      "end_time": "2026-07-13T17:03:34.514344+00:00",
      "start_unix_nanos": 1783962214367465900,
      "end_unix_nanos": 1783962214514343500,
      "crate_name": "log",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 4224,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "hashbrown",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3\\src\\lib.rs",
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
        "feature=\"allocator-api2\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"default-hasher\"",
        "--cfg",
        "feature=\"equivalent\"",
        "--cfg",
        "feature=\"inline-more\"",
        "--cfg",
        "feature=\"raw-entry\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"allocator-api2\", \"compiler_builtins\", \"core\", \"default\", \"default-hasher\", \"equivalent\", \"inline-more\", \"nightly\", \"raw-entry\", \"rayon\", \"rustc-dep-of-std\", \"rustc-internal-api\", \"serde\"))",
        "-C",
        "metadata=f922be269ffb0ca2",
        "-C",
        "extra-filename=-87144cce35d37a78",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--extern",
        "allocator_api2=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liballocator_api2-2a8f64255b7efe9c.rmeta",
        "--extern",
        "equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libequivalent-b19a42cd8c2442b0.rmeta",
        "--extern",
        "foldhash=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libfoldhash-e0e750b5d57e29ec.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name hashbrown --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"allocator-api2\\\"\" --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"default-hasher\\\"\" --cfg \"feature=\\\"equivalent\\\"\" --cfg \"feature=\\\"inline-more\\\"\" --cfg \"feature=\\\"raw-entry\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"allocator-api2\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"default-hasher\\\", \\\"equivalent\\\", \\\"inline-more\\\", \\\"nightly\\\", \\\"raw-entry\\\", \\\"rayon\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-internal-api\\\", \\\"serde\\\"))\" -C metadata=f922be269ffb0ca2 -C extra-filename=-87144cce35d37a78 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --extern allocator_api2=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liballocator_api2-2a8f64255b7efe9c.rmeta --extern equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libequivalent-b19a42cd8c2442b0.rmeta --extern foldhash=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libfoldhash-e0e750b5d57e29ec.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "hashbrown",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.3\\src\\lib.rs",
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
        "feature=\"allocator-api2\"",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"default-hasher\"",
        "--cfg",
        "feature=\"equivalent\"",
        "--cfg",
        "feature=\"inline-more\"",
        "--cfg",
        "feature=\"raw-entry\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"allocator-api2\", \"compiler_builtins\", \"core\", \"default\", \"default-hasher\", \"equivalent\", \"inline-more\", \"nightly\", \"raw-entry\", \"rayon\", \"rustc-dep-of-std\", \"rustc-internal-api\", \"serde\"))",
        "-C",
        "metadata=f922be269ffb0ca2",
        "-C",
        "extra-filename=-87144cce35d37a78",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--extern",
        "allocator_api2=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liballocator_api2-2a8f64255b7efe9c.rmeta",
        "--extern",
        "equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libequivalent-b19a42cd8c2442b0.rmeta",
        "--extern",
        "foldhash=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libfoldhash-e0e750b5d57e29ec.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:34.747428+00:00",
      "end_time": "2026-07-13T17:03:35.195297+00:00",
      "start_unix_nanos": 1783962214747428300,
      "end_unix_nanos": 1783962215195297000,
      "crate_name": "hashbrown",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "proxy-wasm:0.2.3:17260",
      "root_process_pid": 3732,
      "pid": 9228,
      "ppid": 14884,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "proxy_wasm",
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
        "metadata=592468110d7e5876",
        "-C",
        "extra-filename=-5da93ba2803ffc11",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--extern",
        "hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libhashbrown-87144cce35d37a78.rmeta",
        "--extern",
        "log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liblog-c247e66842f1b865.rmeta",
        "--check-cfg",
        "cfg(nightly)",
        "--check-cfg",
        "cfg(wasi_exec_model_reactor)"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name proxy_wasm --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=592468110d7e5876 -C extra-filename=-5da93ba2803ffc11 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps --extern hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libhashbrown-87144cce35d37a78.rmeta --extern log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liblog-c247e66842f1b865.rmeta --check-cfg cfg(nightly) --check-cfg cfg(wasi_exec_model_reactor)",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "proxy_wasm",
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
        "metadata=592468110d7e5876",
        "-C",
        "extra-filename=-5da93ba2803ffc11",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps",
        "--extern",
        "hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\libhashbrown-87144cce35d37a78.rmeta",
        "--extern",
        "log=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps\\liblog-c247e66842f1b865.rmeta",
        "--check-cfg",
        "cfg(nightly)",
        "--check-cfg",
        "cfg(wasi_exec_model_reactor)"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:35.147793+00:00",
      "end_time": "2026-07-13T17:03:36.178854+00:00",
      "start_unix_nanos": 1783962215147792700,
      "end_unix_nanos": 1783962216178854500,
      "crate_name": "proxy_wasm",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-1y4ysd7d\\src\\proxy-wasm-0.2.3\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 3498,
    "crate": "proxy-wasm",
    "version": "0.2.3",
    "crate_id": "208085",
    "version_id": "1590759",
    "downloads": 2822063,
    "cumulative_downloads": 108486418094,
    "cumulative_share_of_global": 0.40560567253298196,
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
