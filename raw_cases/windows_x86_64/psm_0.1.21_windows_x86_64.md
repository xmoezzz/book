# `psm` `0.1.21`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000310       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000328       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003f8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000438       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000450       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 000000014009b020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000288       \\177KERNEL32_NULL_THUNK_DATA 000000014009b288     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002a0       \\177OLEAUT32_NULL_THUNK_DATA 000000014009b2a0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002f0       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014009b2f0     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000310       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000310       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014009b310     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000328       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000328       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014009b328     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000338       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014009b338     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000348       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014009b348     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003e0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014009b3e0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003f8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003f8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014009b3f8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000408       \\177bcryptprimitives_NULL_THUNK_DATA 000000014009b408     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000438       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000438       \\177ntdll_NULL_THUNK_DATA  000000014009b438     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000450       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000450       \\177ole32_NULL_THUNK_DATA  000000014009b450     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-link-link-14936-1783954453146969900.map",
  "pid": 14936,
  "ppid": 11720,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-link-link-14936-1783954453146969900.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21/target/debug/build/psm-429e36e7913a39a1/out/libpsm_s.a`

Owner: `psm` `0.1.21`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21/src/arch/x86_64_msvc.asm`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
    "-nologo",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
    "-c",
    "src/arch/x86_64_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
  "src": "src/arch/x86_64_msvc.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

### Native link records

_None._

### Resolved link records

_None._

### Resolved native inputs

_None._

## Complete analysis record stream

These are the recovered/enriched/generated records actually supplied to native-flow reconstruction.

### Analysis records

#### Record 1

```json
{
  "event": "native_trace_root_context",
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.73",
      "name": "cc",
      "version": "1.0.73",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
      "name": "psm",
      "version": "0.1.21",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "kind": "exec",
  "pid": 14936,
  "ppid": 11720,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "cargo_pkg_name": "psm",
  "cargo_pkg_version": "0.1.21",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 14936,
  "ppid": 11720,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000288       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000310       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000328       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003e0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003f8       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000438       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000450       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 000000014009b020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000288       \\177KERNEL32_NULL_THUNK_DATA 000000014009b288     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002a0       \\177OLEAUT32_NULL_THUNK_DATA 000000014009b2a0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002f0       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014009b2f0     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000310       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000310       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014009b310     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000328       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000328       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014009b328     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000338       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014009b338     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000348       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014009b348     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003e0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014009b3e0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003f8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003f8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014009b3f8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000408       \\177bcryptprimitives_NULL_THUNK_DATA 000000014009b408     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000438       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000438       \\177ntdll_NULL_THUNK_DATA  000000014009b438     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000450       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000450       \\177ole32_NULL_THUNK_DATA  000000014009b450     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-link-link-14936-1783954453146969900.map",
  "pid": 14936,
  "ppid": 11720,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-link-link-14936-1783954453146969900.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
    "-nologo",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
    "-c",
    "src/arch/x86_64_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "kind": "exec",
  "pid": 11968,
  "ppid": 9076,
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
    "-nologo",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
    "-c",
    "src/arch/x86_64_msvc.asm"
  ],
  "cargo_pkg_name": "psm",
  "cargo_pkg_version": "0.1.21",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "event_id": "used:ml64:4e881e5c637fc1a7:e8b38fe4f68cb781:1120f930cfa7e1c6",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
  "path": "src/arch/x86_64_msvc.asm",
  "pid": 11968,
  "sha256": "85683bc65a03371ea7d8d79dcbe487f690cc2460c359817fc63c30d575ad8957",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
    "-nologo",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
    "-c",
    "src/arch/x86_64_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
  "src": "src/arch/x86_64_msvc.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
    "-nologo",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
    "-c",
    "src/arch/x86_64_msvc.asm"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "cargo_pkg_name": "psm",
  "cargo_pkg_version": "0.1.21",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
  "pid": 11968,
  "ppid": 9076,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "ml64",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "kind": "exec",
  "pid": 16320,
  "ppid": 9076,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "cargo_pkg_name": "psm",
  "cargo_pkg_version": "0.1.21",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "event_id": "used:lib:4e881e5c637fc1a7:1120f930cfa7e1c6:c55f89ff7ac05856",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
  "pid": 16320,
  "sha256": "b38f8af586e61fb216c2c67da3b34ff06df36529f4e7550c1e47a34be5446e66",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "cargo_pkg_name": "psm",
  "cargo_pkg_version": "0.1.21",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "event_id": "used:lib:4e881e5c637fc1a7:1120f930cfa7e1c6:8e6abd62bbc9bdba",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
  "pid": 16320,
  "sha256": "b38f8af586e61fb216c2c67da3b34ff06df36529f4e7550c1e47a34be5446e66",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "cargo_pkg_name": "psm",
  "cargo_pkg_version": "0.1.21",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
  "pid": 16320,
  "ppid": 9076,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "crate": "psm",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "event_id": "bsrun:fab2715cc165d9f2:99c60998dd239397:177a0d57f98f995e",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "0.1.21",
  "_owner": {
    "crate": "psm",
    "version": "0.1.21",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
    "source": "cwd_prefix"
  }
}
```

#### Record 17

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
  "raw_event_count": 13957,
  "parsed_event_count": 13957,
  "parse_error_count": 0,
  "command_line_event_count": 13957,
  "build_script_root_event_count": 289,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 1274,
  "dropped_event_count": 7394
}
```

#### Record 18

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 9076,
  "ppid": 16796,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:54:13.431630+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\build-script-build.exe",
  "root_cargo_pid": 4648,
  "build_script_root_pid": 9076,
  "build_script_related": true,
  "build_script_target_dir": "psm-72eff60f4ce20b5d"
}
```

#### Record 19

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11968,
  "ppid": 9076,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe"
  ],
  "comm": "ml64.exe",
  "time": "2026-07-13T14:54:13.498432+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
  "root_cargo_pid": 4648,
  "build_script_root_pid": 9076,
  "build_script_related": true,
  "build_script_target_dir": "psm-72eff60f4ce20b5d"
}
```

#### Record 20

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13780,
  "ppid": 11968,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\ml64.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\ml64.exe"
  ],
  "comm": "ml64.exe",
  "time": "2026-07-13T14:54:13.506350+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\ml64.exe",
  "root_cargo_pid": 4648,
  "build_script_root_pid": 9076,
  "build_script_related": true,
  "build_script_target_dir": "psm-72eff60f4ce20b5d"
}
```

#### Record 21

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16320,
  "ppid": 9076,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\lib.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\lib.exe"
  ],
  "comm": "lib.exe",
  "time": "2026-07-13T14:54:13.579823+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\lib.exe",
  "root_cargo_pid": 4648,
  "build_script_root_pid": 9076,
  "build_script_related": true,
  "build_script_target_dir": "psm-72eff60f4ce20b5d"
}
```

#### Record 22

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16908,
  "ppid": 16320,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe"
  ],
  "comm": "lib.exe",
  "time": "2026-07-13T14:54:13.589199+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe",
  "root_cargo_pid": 4648,
  "build_script_root_pid": 9076,
  "build_script_related": true,
  "build_script_target_dir": "psm-72eff60f4ce20b5d"
}
```

#### Record 23

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 18152,
  "ppid": 16908,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
  ],
  "comm": "link.exe",
  "time": "2026-07-13T14:54:13.593848+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "root_cargo_pid": 4648,
  "build_script_root_pid": 9076,
  "build_script_related": true,
  "build_script_target_dir": "psm-72eff60f4ce20b5d"
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
  "run_id": "psm:0.1.21:11856",
  "root_process_pid": 4648,
  "pid": 6312,
  "ppid": 18140,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
  "time": "2026-07-13T14:54:11.908290+00:00",
  "end_time": "2026-07-13T14:54:11.926171+00:00",
  "start_unix_nanos": 1783954451908290100,
  "end_unix_nanos": 1783954451926170900,
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
  "run_id": "psm:0.1.21:11856",
  "root_process_pid": 4648,
  "pid": 12612,
  "ppid": 18140,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
  "time": "2026-07-13T14:54:11.932685+00:00",
  "end_time": "2026-07-13T14:54:11.953689+00:00",
  "start_unix_nanos": 1783954451932684600,
  "end_unix_nanos": 1783954451953689200,
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
  "run_id": "psm:0.1.21:11856",
  "root_process_pid": 4648,
  "pid": 17844,
  "ppid": 16796,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
  "time": "2026-07-13T14:54:12.416990+00:00",
  "end_time": "2026-07-13T14:54:12.433794+00:00",
  "start_unix_nanos": 1783954452416989800,
  "end_unix_nanos": 1783954452433794600,
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
  "run_id": "psm:0.1.21:11856",
  "root_process_pid": 4648,
  "pid": 1724,
  "ppid": 16796,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
  "time": "2026-07-13T14:54:12.440165+00:00",
  "end_time": "2026-07-13T14:54:12.459179+00:00",
  "start_unix_nanos": 1783954452440164500,
  "end_unix_nanos": 1783954452459179300,
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
  "run_id": "psm:0.1.21:11856",
  "root_process_pid": 4648,
  "pid": 4852,
  "ppid": 16796,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
  "time": "2026-07-13T14:54:12.467533+00:00",
  "end_time": "2026-07-13T14:54:12.483824+00:00",
  "start_unix_nanos": 1783954452467532900,
  "end_unix_nanos": 1783954452483823900,
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
  "run_id": "psm:0.1.21:11856",
  "root_process_pid": 4648,
  "pid": 13172,
  "ppid": 16796,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73\\src\\lib.rs",
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
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=6db6b3547ab2ae4c",
    "-C",
    "extra-filename=-122d9d9222db9589",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=6db6b3547ab2ae4c -C extra-filename=-122d9d9222db9589 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73\\src\\lib.rs",
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
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=6db6b3547ab2ae4c",
    "-C",
    "extra-filename=-122d9d9222db9589",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:12.496987+00:00",
  "end_time": "2026-07-13T14:54:12.980546+00:00",
  "start_unix_nanos": 1783954452496986900,
  "end_unix_nanos": 1783954452980545800,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps"
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
  "run_id": "psm:0.1.21:11856",
  "root_process_pid": 4648,
  "pid": 6460,
  "ppid": 16796,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
    "metadata=db69f2b40e54da67",
    "-C",
    "extra-filename=-72eff60f4ce20b5d",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps\\libcc-122d9d9222db9589.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=db69f2b40e54da67 -C extra-filename=-72eff60f4ce20b5d --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps\\libcc-122d9d9222db9589.rlib",
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
    "metadata=db69f2b40e54da67",
    "-C",
    "extra-filename=-72eff60f4ce20b5d",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps\\libcc-122d9d9222db9589.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:12.993851+00:00",
  "end_time": "2026-07-13T14:54:13.312239+00:00",
  "start_unix_nanos": 1783954452993851300,
  "end_unix_nanos": 1783954453312238800,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d"
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
  "run_id": "psm:0.1.21:11856",
  "root_process_pid": 4648,
  "pid": 10284,
  "ppid": 16796,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "psm",
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
    "metadata=e1a6db870ef85657",
    "-C",
    "extra-filename=-00c3c31db86f291c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
    "-l",
    "static=psm_s",
    "--cfg",
    "asm"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name psm --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=e1a6db870ef85657 -C extra-filename=-00c3c31db86f291c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out -l static=psm_s --cfg asm",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "psm",
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
    "metadata=e1a6db870ef85657",
    "-C",
    "extra-filename=-00c3c31db86f291c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
    "-l",
    "static=psm_s",
    "--cfg",
    "asm"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:54:13.624443+00:00",
  "end_time": "2026-07-13T14:54:13.703475+00:00",
  "start_unix_nanos": 1783954453624443000,
  "end_unix_nanos": 1783954453703475000,
  "crate_name": "psm",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:54:15.908125+00:00",
  "crate": "psm",
  "version": "0.1.21",
  "duration_seconds": 26.8578246999532,
  "trace_record_count": 23,
  "trace_owner_summary": {
    "owner_package_count": 2,
    "owner_packages": [
      {
        "crate": "cc",
        "version": "1.0.73",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.73",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.73",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.73/Cargo.toml"
      },
      {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21/Cargo.toml"
      }
    ],
    "attributed_event_count": 15,
    "unattributed_event_count": 8,
    "owners": [
      {
        "crate": "psm",
        "version": "0.1.21",
        "event_count": 15,
        "kind_counts": {
          "exec": 3,
          "link": 2,
          "exec_context": 3,
          "resolved_link": 1,
          "used_input": 3,
          "compile": 1,
          "archive": 1,
          "build_script_run": 1
        }
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.73",
          "name": "cc",
          "version": "1.0.73",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
          "name": "psm",
          "version": "0.1.21",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "kind": "exec",
      "pid": 14936,
      "ppid": 11720,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "cargo_pkg_name": "psm",
      "cargo_pkg_version": "0.1.21",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 14936,
      "ppid": 11720,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\rustchX2bh7\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000288       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000310       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000328       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003e0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003f8       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000438       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000450       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 000000014009b020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000288       \\177KERNEL32_NULL_THUNK_DATA 000000014009b288     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002a0       \\177OLEAUT32_NULL_THUNK_DATA 000000014009b2a0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000002f0       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014009b2f0     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000310       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000310       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014009b310     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000328       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000328       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014009b328     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000338       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014009b338     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000348       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014009b348     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003e0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014009b3e0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003f8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:000003f8       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014009b3f8     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000408       \\177bcryptprimitives_NULL_THUNK_DATA 000000014009b408     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000438       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000438       \\177ntdll_NULL_THUNK_DATA  000000014009b438     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000450       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\0002:00000450       \\177ole32_NULL_THUNK_DATA  000000014009b450     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-link-link-14936-1783954453146969900.map",
      "pid": 14936,
      "ppid": 11720,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-link-link-14936-1783954453146969900.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
        "-nologo",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
        "-c",
        "src/arch/x86_64_msvc.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "kind": "exec",
      "pid": 11968,
      "ppid": 9076,
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
        "-nologo",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
        "-c",
        "src/arch/x86_64_msvc.asm"
      ],
      "cargo_pkg_name": "psm",
      "cargo_pkg_version": "0.1.21",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "event_id": "used:ml64:4e881e5c637fc1a7:e8b38fe4f68cb781:1120f930cfa7e1c6",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
      "path": "src/arch/x86_64_msvc.asm",
      "pid": 11968,
      "sha256": "85683bc65a03371ea7d8d79dcbe487f690cc2460c359817fc63c30d575ad8957",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
        "-nologo",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
        "-c",
        "src/arch/x86_64_msvc.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "kind": "compile",
      "language": "asm",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
      "src": "src/arch/x86_64_msvc.asm",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
        "-nologo",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
        "-c",
        "src/arch/x86_64_msvc.asm"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "cargo_pkg_name": "psm",
      "cargo_pkg_version": "0.1.21",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
      "pid": 11968,
      "ppid": 9076,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "ml64",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "kind": "exec",
      "pid": 16320,
      "ppid": 9076,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
      ],
      "cargo_pkg_name": "psm",
      "cargo_pkg_version": "0.1.21",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "event_id": "used:lib:4e881e5c637fc1a7:1120f930cfa7e1c6:c55f89ff7ac05856",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
      "pid": 16320,
      "sha256": "b38f8af586e61fb216c2c67da3b34ff06df36529f4e7550c1e47a34be5446e66",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
      ],
      "cargo_pkg_name": "psm",
      "cargo_pkg_version": "0.1.21",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "event_id": "used:lib:4e881e5c637fc1a7:1120f930cfa7e1c6:8e6abd62bbc9bdba",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o",
      "pid": 16320,
      "sha256": "b38f8af586e61fb216c2c67da3b34ff06df36529f4e7550c1e47a34be5446e66",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\libpsm_s.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out\\src/arch/x86_64_msvc.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "cargo_pkg_name": "psm",
      "cargo_pkg_version": "0.1.21",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
      "pid": 16320,
      "ppid": 9076,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "psm",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "event_id": "bsrun:fab2715cc165d9f2:99c60998dd239397:177a0d57f98f995e",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "0.1.21",
      "_owner": {
        "crate": "psm",
        "version": "0.1.21",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21#psm@0.1.21",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-tnokxlli/src/psm-0.1.21",
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
      "raw_event_count": 13957,
      "parsed_event_count": 13957,
      "parse_error_count": 0,
      "command_line_event_count": 13957,
      "build_script_root_event_count": 289,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 1274,
      "dropped_event_count": 7394
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 9076,
      "ppid": 16796,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:54:13.431630+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d\\build-script-build.exe",
      "root_cargo_pid": 4648,
      "build_script_root_pid": 9076,
      "build_script_related": true,
      "build_script_target_dir": "psm-72eff60f4ce20b5d"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11968,
      "ppid": 9076,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe"
      ],
      "comm": "ml64.exe",
      "time": "2026-07-13T14:54:13.498432+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\ml64.exe",
      "root_cargo_pid": 4648,
      "build_script_root_pid": 9076,
      "build_script_related": true,
      "build_script_target_dir": "psm-72eff60f4ce20b5d"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13780,
      "ppid": 11968,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\ml64.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\ml64.exe"
      ],
      "comm": "ml64.exe",
      "time": "2026-07-13T14:54:13.506350+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\ml64.exe",
      "root_cargo_pid": 4648,
      "build_script_root_pid": 9076,
      "build_script_related": true,
      "build_script_target_dir": "psm-72eff60f4ce20b5d"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16320,
      "ppid": 9076,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\lib.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\lib.exe"
      ],
      "comm": "lib.exe",
      "time": "2026-07-13T14:54:13.579823+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\.tmp\\native-trace-15640-1783954451727\\shims\\lib.exe",
      "root_cargo_pid": 4648,
      "build_script_root_pid": 9076,
      "build_script_related": true,
      "build_script_target_dir": "psm-72eff60f4ce20b5d"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16908,
      "ppid": 16320,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe"
      ],
      "comm": "lib.exe",
      "time": "2026-07-13T14:54:13.589199+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\lib.exe",
      "root_cargo_pid": 4648,
      "build_script_root_pid": 9076,
      "build_script_related": true,
      "build_script_target_dir": "psm-72eff60f4ce20b5d"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 18152,
      "ppid": 16908,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
      ],
      "comm": "link.exe",
      "time": "2026-07-13T14:54:13.593848+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "root_cargo_pid": 4648,
      "build_script_root_pid": 9076,
      "build_script_related": true,
      "build_script_target_dir": "psm-72eff60f4ce20b5d"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "psm:0.1.21:11856",
      "root_process_pid": 4648,
      "pid": 6312,
      "ppid": 18140,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
      "time": "2026-07-13T14:54:11.908290+00:00",
      "end_time": "2026-07-13T14:54:11.926171+00:00",
      "start_unix_nanos": 1783954451908290100,
      "end_unix_nanos": 1783954451926170900,
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
      "run_id": "psm:0.1.21:11856",
      "root_process_pid": 4648,
      "pid": 12612,
      "ppid": 18140,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
      "time": "2026-07-13T14:54:11.932685+00:00",
      "end_time": "2026-07-13T14:54:11.953689+00:00",
      "start_unix_nanos": 1783954451932684600,
      "end_unix_nanos": 1783954451953689200,
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
      "run_id": "psm:0.1.21:11856",
      "root_process_pid": 4648,
      "pid": 17844,
      "ppid": 16796,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
      "time": "2026-07-13T14:54:12.416990+00:00",
      "end_time": "2026-07-13T14:54:12.433794+00:00",
      "start_unix_nanos": 1783954452416989800,
      "end_unix_nanos": 1783954452433794600,
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
      "run_id": "psm:0.1.21:11856",
      "root_process_pid": 4648,
      "pid": 1724,
      "ppid": 16796,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
      "time": "2026-07-13T14:54:12.440165+00:00",
      "end_time": "2026-07-13T14:54:12.459179+00:00",
      "start_unix_nanos": 1783954452440164500,
      "end_unix_nanos": 1783954452459179300,
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
      "run_id": "psm:0.1.21:11856",
      "root_process_pid": 4648,
      "pid": 4852,
      "ppid": 16796,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
      "time": "2026-07-13T14:54:12.467533+00:00",
      "end_time": "2026-07-13T14:54:12.483824+00:00",
      "start_unix_nanos": 1783954452467532900,
      "end_unix_nanos": 1783954452483823900,
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
      "run_id": "psm:0.1.21:11856",
      "root_process_pid": 4648,
      "pid": 13172,
      "ppid": 16796,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73\\src\\lib.rs",
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
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=6db6b3547ab2ae4c",
        "-C",
        "extra-filename=-122d9d9222db9589",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=6db6b3547ab2ae4c -C extra-filename=-122d9d9222db9589 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.0.73\\src\\lib.rs",
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
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=6db6b3547ab2ae4c",
        "-C",
        "extra-filename=-122d9d9222db9589",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:12.496987+00:00",
      "end_time": "2026-07-13T14:54:12.980546+00:00",
      "start_unix_nanos": 1783954452496986900,
      "end_unix_nanos": 1783954452980545800,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "psm:0.1.21:11856",
      "root_process_pid": 4648,
      "pid": 6460,
      "ppid": 16796,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
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
        "metadata=db69f2b40e54da67",
        "-C",
        "extra-filename=-72eff60f4ce20b5d",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps\\libcc-122d9d9222db9589.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=db69f2b40e54da67 -C extra-filename=-72eff60f4ce20b5d --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps\\libcc-122d9d9222db9589.rlib",
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
        "metadata=db69f2b40e54da67",
        "-C",
        "extra-filename=-72eff60f4ce20b5d",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps\\libcc-122d9d9222db9589.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:12.993851+00:00",
      "end_time": "2026-07-13T14:54:13.312239+00:00",
      "start_unix_nanos": 1783954452993851300,
      "end_unix_nanos": 1783954453312238800,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-72eff60f4ce20b5d"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "psm:0.1.21:11856",
      "root_process_pid": 4648,
      "pid": 10284,
      "ppid": 16796,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "psm",
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
        "metadata=e1a6db870ef85657",
        "-C",
        "extra-filename=-00c3c31db86f291c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
        "-l",
        "static=psm_s",
        "--cfg",
        "asm"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name psm --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=e1a6db870ef85657 -C extra-filename=-00c3c31db86f291c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out -l static=psm_s --cfg asm",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "psm",
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
        "metadata=e1a6db870ef85657",
        "-C",
        "extra-filename=-00c3c31db86f291c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\build\\psm-429e36e7913a39a1\\out",
        "-l",
        "static=psm_s",
        "--cfg",
        "asm"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:54:13.624443+00:00",
      "end_time": "2026-07-13T14:54:13.703475+00:00",
      "start_unix_nanos": 1783954453624443000,
      "end_unix_nanos": 1783954453703475000,
      "crate_name": "psm",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-tnokxlli\\src\\psm-0.1.21\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 940,
    "crate": "psm",
    "version": "0.1.21",
    "crate_id": "104434",
    "version_id": "628012",
    "downloads": 23452047,
    "cumulative_downloads": 88115276548,
    "cumulative_share_of_global": 0.3294426770889755,
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
