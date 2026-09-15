# `windows_x86_64_gnu` `0.52.6`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_gnu",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-link-link-9688-1783954072938903300.map",
  "pid": 9688,
  "ppid": 6268,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-link-link-9688-1783954072938903300.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "windows_x86_64_gnu",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
      "name": "windows_x86_64_gnu",
      "version": "0.52.6",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "exit_code": 0,
  "kind": "exec",
  "pid": 9688,
  "ppid": 6268,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_gnu",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "windows_x86_64_gnu",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "cargo_pkg_name": "windows_x86_64_gnu",
  "cargo_pkg_version": "0.52.6",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 9688,
  "ppid": 6268,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "_owner": {
    "crate": "windows_x86_64_gnu",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000148       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000198       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-link-link-9688-1783954072938903300.map",
  "pid": 9688,
  "ppid": 6268,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-link-link-9688-1783954072938903300.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "windows_x86_64_gnu",
    "version": "0.52.6",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
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
  "raw_event_count": 1124,
  "parsed_event_count": 1124,
  "parse_error_count": 0,
  "command_line_event_count": 1124,
  "build_script_root_event_count": 26,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 85,
  "dropped_event_count": 540
}
```

#### Record 7

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 2364,
  "ppid": 16436,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:47:53.189067+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\build-script-build.exe",
  "root_cargo_pid": 5380,
  "build_script_root_pid": 2364,
  "build_script_related": true,
  "build_script_target_dir": "windows_x86_64_gnu-372883bcbea48b87"
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
  "run_id": "windows_x86_64_gnu:0.52.6:11328",
  "root_process_pid": 5380,
  "pid": 16832,
  "ppid": 4392,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
  "time": "2026-07-13T14:47:50.460947+00:00",
  "end_time": "2026-07-13T14:47:50.480118+00:00",
  "start_unix_nanos": 1783954070460946800,
  "end_unix_nanos": 1783954070480117800,
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
  "run_id": "windows_x86_64_gnu:0.52.6:11328",
  "root_process_pid": 5380,
  "pid": 13804,
  "ppid": 4392,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
  "time": "2026-07-13T14:47:50.485962+00:00",
  "end_time": "2026-07-13T14:47:50.517506+00:00",
  "start_unix_nanos": 1783954070485962100,
  "end_unix_nanos": 1783954070517506400,
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
  "run_id": "windows_x86_64_gnu:0.52.6:11328",
  "root_process_pid": 5380,
  "pid": 5104,
  "ppid": 16436,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
  "time": "2026-07-13T14:47:52.623284+00:00",
  "end_time": "2026-07-13T14:47:52.648017+00:00",
  "start_unix_nanos": 1783954072623284000,
  "end_unix_nanos": 1783954072648017500,
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
  "run_id": "windows_x86_64_gnu:0.52.6:11328",
  "root_process_pid": 5380,
  "pid": 744,
  "ppid": 16436,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
  "time": "2026-07-13T14:47:52.656065+00:00",
  "end_time": "2026-07-13T14:47:52.681505+00:00",
  "start_unix_nanos": 1783954072656065200,
  "end_unix_nanos": 1783954072681505000,
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
  "run_id": "windows_x86_64_gnu:0.52.6:11328",
  "root_process_pid": 5380,
  "pid": 540,
  "ppid": 16436,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
  "time": "2026-07-13T14:47:52.703104+00:00",
  "end_time": "2026-07-13T14:47:52.723056+00:00",
  "start_unix_nanos": 1783954072703103500,
  "end_unix_nanos": 1783954072723056200,
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
  "run_id": "windows_x86_64_gnu:0.52.6:11328",
  "root_process_pid": 5380,
  "pid": 16288,
  "ppid": 16436,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
    "metadata=2728d53c66c3932c",
    "-C",
    "extra-filename=-372883bcbea48b87",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=2728d53c66c3932c -C extra-filename=-372883bcbea48b87 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
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
    "metadata=2728d53c66c3932c",
    "-C",
    "extra-filename=-372883bcbea48b87",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:47:52.742086+00:00",
  "end_time": "2026-07-13T14:47:53.120059+00:00",
  "start_unix_nanos": 1783954072742086500,
  "end_unix_nanos": 1783954073120059100,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87"
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
  "run_id": "windows_x86_64_gnu:0.52.6:11328",
  "root_process_pid": 5380,
  "pid": 11536,
  "ppid": 16436,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_x86_64_gnu",
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
    "metadata=e49fdbfd7a211cae",
    "-C",
    "extra-filename=-0518ac981748f00e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\lib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_x86_64_gnu --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=e49fdbfd7a211cae -C extra-filename=-0518ac981748f00e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\lib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "windows_x86_64_gnu",
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
    "metadata=e49fdbfd7a211cae",
    "-C",
    "extra-filename=-0518ac981748f00e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\lib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:47:53.211341+00:00",
  "end_time": "2026-07-13T14:47:53.271044+00:00",
  "start_unix_nanos": 1783954073211340700,
  "end_unix_nanos": 1783954073271044200,
  "crate_name": "windows_x86_64_gnu",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:47:55.786297+00:00",
  "crate": "windows_x86_64_gnu",
  "version": "0.52.6",
  "duration_seconds": 28.428738300106488,
  "trace_record_count": 7,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6/Cargo.toml"
      }
    ],
    "attributed_event_count": 4,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
          "name": "windows_x86_64_gnu",
          "version": "0.52.6",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "exit_code": 0,
      "kind": "exec",
      "pid": 9688,
      "ppid": 6268,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "cargo_pkg_name": "windows_x86_64_gnu",
      "cargo_pkg_version": "0.52.6",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 9688,
      "ppid": 6268,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "_owner": {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-13608-1783954070257\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\rustcsggR97\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000148       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000198       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001d0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002b8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000148       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140019148     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000198       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140019198     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400191b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400191d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400191e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400191f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140019288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400192a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400192b8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-link-link-9688-1783954072938903300.map",
      "pid": 9688,
      "ppid": 6268,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\.tmp\\native-trace-link-link-9688-1783954072938903300.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6#windows_x86_64_gnu@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9_daz4_f/src/windows_x86_64_gnu-0.52.6",
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
      "raw_event_count": 1124,
      "parsed_event_count": 1124,
      "parse_error_count": 0,
      "command_line_event_count": 1124,
      "build_script_root_event_count": 26,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 85,
      "dropped_event_count": 540
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 2364,
      "ppid": 16436,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:47:53.189067+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87\\build-script-build.exe",
      "root_cargo_pid": 5380,
      "build_script_root_pid": 2364,
      "build_script_related": true,
      "build_script_target_dir": "windows_x86_64_gnu-372883bcbea48b87"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "windows_x86_64_gnu:0.52.6:11328",
      "root_process_pid": 5380,
      "pid": 16832,
      "ppid": 4392,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
      "time": "2026-07-13T14:47:50.460947+00:00",
      "end_time": "2026-07-13T14:47:50.480118+00:00",
      "start_unix_nanos": 1783954070460946800,
      "end_unix_nanos": 1783954070480117800,
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
      "run_id": "windows_x86_64_gnu:0.52.6:11328",
      "root_process_pid": 5380,
      "pid": 13804,
      "ppid": 4392,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
      "time": "2026-07-13T14:47:50.485962+00:00",
      "end_time": "2026-07-13T14:47:50.517506+00:00",
      "start_unix_nanos": 1783954070485962100,
      "end_unix_nanos": 1783954070517506400,
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
      "run_id": "windows_x86_64_gnu:0.52.6:11328",
      "root_process_pid": 5380,
      "pid": 5104,
      "ppid": 16436,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
      "time": "2026-07-13T14:47:52.623284+00:00",
      "end_time": "2026-07-13T14:47:52.648017+00:00",
      "start_unix_nanos": 1783954072623284000,
      "end_unix_nanos": 1783954072648017500,
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
      "run_id": "windows_x86_64_gnu:0.52.6:11328",
      "root_process_pid": 5380,
      "pid": 744,
      "ppid": 16436,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
      "time": "2026-07-13T14:47:52.656065+00:00",
      "end_time": "2026-07-13T14:47:52.681505+00:00",
      "start_unix_nanos": 1783954072656065200,
      "end_unix_nanos": 1783954072681505000,
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
      "run_id": "windows_x86_64_gnu:0.52.6:11328",
      "root_process_pid": 5380,
      "pid": 540,
      "ppid": 16436,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
      "time": "2026-07-13T14:47:52.703104+00:00",
      "end_time": "2026-07-13T14:47:52.723056+00:00",
      "start_unix_nanos": 1783954072703103500,
      "end_unix_nanos": 1783954072723056200,
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
      "run_id": "windows_x86_64_gnu:0.52.6:11328",
      "root_process_pid": 5380,
      "pid": 16288,
      "ppid": 16436,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
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
        "metadata=2728d53c66c3932c",
        "-C",
        "extra-filename=-372883bcbea48b87",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=2728d53c66c3932c -C extra-filename=-372883bcbea48b87 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
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
        "metadata=2728d53c66c3932c",
        "-C",
        "extra-filename=-372883bcbea48b87",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:47:52.742086+00:00",
      "end_time": "2026-07-13T14:47:53.120059+00:00",
      "start_unix_nanos": 1783954072742086500,
      "end_unix_nanos": 1783954073120059100,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\build\\windows_x86_64_gnu-372883bcbea48b87"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "windows_x86_64_gnu:0.52.6:11328",
      "root_process_pid": 5380,
      "pid": 11536,
      "ppid": 16436,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_x86_64_gnu",
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
        "metadata=e49fdbfd7a211cae",
        "-C",
        "extra-filename=-0518ac981748f00e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\lib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name windows_x86_64_gnu --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=e49fdbfd7a211cae -C extra-filename=-0518ac981748f00e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\lib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "windows_x86_64_gnu",
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
        "metadata=e49fdbfd7a211cae",
        "-C",
        "extra-filename=-0518ac981748f00e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\lib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:47:53.211341+00:00",
      "end_time": "2026-07-13T14:47:53.271044+00:00",
      "start_unix_nanos": 1783954073211340700,
      "end_unix_nanos": 1783954073271044200,
      "crate_name": "windows_x86_64_gnu",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-9_daz4_f\\src\\windows_x86_64_gnu-0.52.6\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 121,
    "crate": "windows_x86_64_gnu",
    "version": "0.52.6",
    "crate_id": "473671",
    "version_id": "1191989",
    "downloads": 172593521,
    "cumulative_downloads": 31519363083,
    "cumulative_share_of_global": 0.11784362213907881,
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
