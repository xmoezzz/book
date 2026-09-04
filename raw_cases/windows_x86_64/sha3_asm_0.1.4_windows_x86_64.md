# `sha3-asm` `0.1.4`

Platform: Windows x86_64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/libkeccak.a`

Owner: `sha3-asm` `0.1.4`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze",
    "-DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze",
    "-D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext",
    "-DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext",
    "-D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb",
    "-DSHA3_absorb=KECCAK_ASM_SHA3_absorb",
    "-D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext",
    "-DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
  "src": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
      "name": "cc",
      "version": "1.2.67",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
      "name": "cfg-if",
      "version": "1.0.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
      "name": "sha3-asm",
      "version": "0.1.4",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 18704,
  "ppid": 16524,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 18704,
  "ppid": 16524,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400d4020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400d4298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400d42b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400d4300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400d4320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400d4338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400d4348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400d4358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400d43f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400d4408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400d4418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400d4448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400d4460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-link-link-18704-1783954940385895800.map",
  "pid": 18704,
  "ppid": 16524,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-link-link-18704-1783954940385895800.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "perl",
    "cryptogams/x86_64/keccak1600-x86_64.pl",
    "masm",
    "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 4688,
  "ppid": 16208,
  "success": true,
  "tool": "perl",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "perl",
    "cryptogams/x86_64/keccak1600-x86_64.pl",
    "masm",
    "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
  ],
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "event_id": "used:perl:98cebc0f37704802:1fa7f5f13fc73252:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm",
  "pid": 4688,
  "sha256": "4d7fa2cd3e1132490675b387503bbe0ee9dd47c10d76b8633cabf58478470990",
  "success": true,
  "tool": "perl",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "perl",
    "cryptogams/x86_64/keccak1600-x86_64.pl",
    "masm",
    "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "inputs": [
    "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "perl",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "perl",
    "cryptogams/x86_64/keccak1600-x86_64.pl",
    "masm",
    "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
  "pid": 4688,
  "ppid": 16208,
  "profile": "debug",
  "real_tool": "C:\\Strawberry\\perl\\bin\\perl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "perl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 11580,
  "ppid": 16208,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
  ],
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "event_id": "used:cl:98cebc0f37704802:9b5eb95cf73c3c2a:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c",
  "pid": 11580,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
  "pid": 11580,
  "ppid": 16208,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 7476,
  "ppid": 16208,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
  "pid": 7476,
  "ppid": 16208,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze",
    "-DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze",
    "-D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext",
    "-DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext",
    "-D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb",
    "-DSHA3_absorb=KECCAK_ASM_SHA3_absorb",
    "-D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext",
    "-DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 11080,
  "ppid": 16208,
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze",
    "-DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze",
    "-D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext",
    "-DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext",
    "-D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb",
    "-DSHA3_absorb=KECCAK_ASM_SHA3_absorb",
    "-D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext",
    "-DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm"
  ],
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "event_id": "used:ml64:98cebc0f37704802:5b837add280f5f62:c3709c1e56f97bcb",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm",
  "pid": 11080,
  "sha256": "4d7fa2cd3e1132490675b387503bbe0ee9dd47c10d76b8633cabf58478470990",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze",
    "-DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze",
    "-D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext",
    "-DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext",
    "-D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb",
    "-DSHA3_absorb=KECCAK_ASM_SHA3_absorb",
    "-D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext",
    "-DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
  "src": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze",
    "-DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze",
    "-D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext",
    "-DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext",
    "-D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb",
    "-DSHA3_absorb=KECCAK_ASM_SHA3_absorb",
    "-D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext",
    "-DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
  "pid": 11080,
  "ppid": 16208,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "ml64",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 16508,
  "ppid": 16208,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "event_id": "used:lib:98cebc0f37704802:c3709c1e56f97bcb:8fa157081a83bc07",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
  "pid": 16508,
  "sha256": "30e58c1928d87228d113eb15394024a640e7f77d1f8d611beec3b1c00c57f1a2",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "event_id": "used:lib:98cebc0f37704802:c3709c1e56f97bcb:b0c9498e7d5e9b51",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
  "pid": 16508,
  "sha256": "30e58c1928d87228d113eb15394024a640e7f77d1f8d611beec3b1c00c57f1a2",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "cargo_pkg_name": "sha3-asm",
  "cargo_pkg_version": "0.1.4",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
  "pid": 16508,
  "ppid": 16208,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "crate": "sha3-asm",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "event_id": "bsrun:f5e7f3f8a8b78938:ed64e13ff5d8ecce:50f8ea1623c8eff3",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "0.1.4",
  "_owner": {
    "crate": "sha3-asm",
    "version": "0.1.4",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
    "source": "cwd_prefix"
  }
}
```

#### Record 27

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
  "raw_event_count": 37715,
  "parsed_event_count": 37715,
  "parse_error_count": 0,
  "command_line_event_count": 37715,
  "build_script_root_event_count": 710,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 6240,
  "dropped_event_count": 19570
}
```

#### Record 28

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16208,
  "ppid": 4988,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T15:02:20.890053+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\build-script-build.exe",
  "root_cargo_pid": 18424,
  "build_script_root_pid": 16208,
  "build_script_related": true,
  "build_script_target_dir": "sha3-asm-9935574e596261e8"
}
```

#### Record 29

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 4688,
  "ppid": 16208,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\perl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\perl.exe"
  ],
  "comm": "perl.exe",
  "time": "2026-07-13T15:02:20.974710+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\perl.exe",
  "root_cargo_pid": 18424,
  "build_script_root_pid": 16208,
  "build_script_related": true,
  "build_script_target_dir": "sha3-asm-9935574e596261e8"
}
```

#### Record 30

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12532,
  "ppid": 4688,
  "image": "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe"
  ],
  "comm": "perl.exe",
  "time": "2026-07-13T15:02:20.984536+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe",
  "root_cargo_pid": 18424,
  "build_script_root_pid": 16208,
  "build_script_related": true,
  "build_script_target_dir": "sha3-asm-9935574e596261e8"
}
```

#### Record 31

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13788,
  "ppid": 12532,
  "image": "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe"
  ],
  "comm": "perl.exe",
  "time": "2026-07-13T15:02:21.208872+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe",
  "root_cargo_pid": 18424,
  "build_script_root_pid": 16208,
  "build_script_related": true,
  "build_script_target_dir": "sha3-asm-9935574e596261e8"
}
```

#### Record 32

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11580,
  "ppid": 16208,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T15:02:21.350988+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\cl.exe",
  "root_cargo_pid": 18424,
  "build_script_root_pid": 16208,
  "build_script_related": true,
  "build_script_target_dir": "sha3-asm-9935574e596261e8"
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
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 17852,
  "ppid": 19712,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
  "time": "2026-07-13T15:02:17.253399+00:00",
  "end_time": "2026-07-13T15:02:17.274644+00:00",
  "start_unix_nanos": 1783954937253399400,
  "end_unix_nanos": 1783954937274643600,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
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
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 2652,
  "ppid": 19712,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
  "time": "2026-07-13T15:02:17.283182+00:00",
  "end_time": "2026-07-13T15:02:17.310953+00:00",
  "start_unix_nanos": 1783954937283182200,
  "end_unix_nanos": 1783954937310952900,
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

#### Record 35

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 19820,
  "ppid": 19712,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
  "time": "2026-07-13T15:02:18.238385+00:00",
  "end_time": "2026-07-13T15:02:18.268013+00:00",
  "start_unix_nanos": 1783954938238385500,
  "end_unix_nanos": 1783954938268013500,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
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
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 20544,
  "ppid": 4988,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
  "time": "2026-07-13T15:02:18.322975+00:00",
  "end_time": "2026-07-13T15:02:18.342179+00:00",
  "start_unix_nanos": 1783954938322974900,
  "end_unix_nanos": 1783954938342179200,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
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
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 15640,
  "ppid": 4988,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
  "time": "2026-07-13T15:02:18.349883+00:00",
  "end_time": "2026-07-13T15:02:18.373002+00:00",
  "start_unix_nanos": 1783954938349883100,
  "end_unix_nanos": 1783954938373002100,
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

#### Record 38

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 16984,
  "ppid": 4988,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
  "time": "2026-07-13T15:02:18.390062+00:00",
  "end_time": "2026-07-13T15:02:18.418713+00:00",
  "start_unix_nanos": 1783954938390062300,
  "end_unix_nanos": 1783954938418713300,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
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
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 7760,
  "ppid": 4988,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "find_msvc_tools",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=a199b1cb5e329831",
    "-C",
    "extra-filename=-824f9ded730dd358",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "find_msvc_tools",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=a199b1cb5e329831",
    "-C",
    "extra-filename=-824f9ded730dd358",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:02:18.449712+00:00",
  "end_time": "2026-07-13T15:02:19.161948+00:00",
  "start_unix_nanos": 1783954938449712200,
  "end_unix_nanos": 1783954939161948000,
  "crate_name": "find_msvc_tools",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
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
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 7708,
  "ppid": 4988,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "shlex",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(manual_codegen_check)",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=181708ecadab3b47",
    "-C",
    "extra-filename=-f9df91f0b2c0ecd4",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "shlex",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(manual_codegen_check)",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=181708ecadab3b47",
    "-C",
    "extra-filename=-f9df91f0b2c0ecd4",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:02:18.451522+00:00",
  "end_time": "2026-07-13T15:02:18.765726+00:00",
  "start_unix_nanos": 1783954938451522200,
  "end_unix_nanos": 1783954938765726100,
  "crate_name": "shlex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
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
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 17776,
  "ppid": 4988,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cfg_if",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4\\src\\lib.rs",
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
    "cfg(feature, values(\"core\", \"rustc-dep-of-std\"))",
    "-C",
    "metadata=16c6d22a93f489b9",
    "-C",
    "extra-filename=-50da2642d7d10359",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cfg_if --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"core\\\", \\\"rustc-dep-of-std\\\"))\" -C metadata=16c6d22a93f489b9 -C extra-filename=-50da2642d7d10359 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cfg_if",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4\\src\\lib.rs",
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
    "cfg(feature, values(\"core\", \"rustc-dep-of-std\"))",
    "-C",
    "metadata=16c6d22a93f489b9",
    "-C",
    "extra-filename=-50da2642d7d10359",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:02:18.466380+00:00",
  "end_time": "2026-07-13T15:02:18.620923+00:00",
  "start_unix_nanos": 1783954938466379600,
  "end_unix_nanos": 1783954938620923300,
  "crate_name": "cfg_if",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
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
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 17368,
  "ppid": 4988,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=98547e1a4afb2a03",
    "-C",
    "extra-filename=-24e0405f325d0f68",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=98547e1a4afb2a03",
    "-C",
    "extra-filename=-24e0405f325d0f68",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:02:18.972375+00:00",
  "end_time": "2026-07-13T15:02:20.017841+00:00",
  "start_unix_nanos": 1783954938972374800,
  "end_unix_nanos": 1783954940017840600,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
}
```

#### Record 43

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 18576,
  "ppid": 4988,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
    "metadata=230ccf9129629ef5",
    "-C",
    "extra-filename=-9935574e596261e8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=230ccf9129629ef5 -C extra-filename=-9935574e596261e8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
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
    "metadata=230ccf9129629ef5",
    "-C",
    "extra-filename=-9935574e596261e8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:02:20.039493+00:00",
  "end_time": "2026-07-13T15:02:20.732300+00:00",
  "start_unix_nanos": 1783954940039492500,
  "end_unix_nanos": 1783954940732300400,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8"
}
```

#### Record 44

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "sha3-asm:0.1.4:2896",
  "root_process_pid": 18424,
  "pid": 4620,
  "ppid": 4988,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "sha3_asm",
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
    "metadata=f96032013dae0107",
    "-C",
    "extra-filename=-2ee9f6f1753daf9e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--extern",
    "cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcfg_if-50da2642d7d10359.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
    "-l",
    "static=keccak"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name sha3_asm --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=f96032013dae0107 -C extra-filename=-2ee9f6f1753daf9e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --extern cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcfg_if-50da2642d7d10359.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out -l static=keccak",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "sha3_asm",
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
    "metadata=f96032013dae0107",
    "-C",
    "extra-filename=-2ee9f6f1753daf9e",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
    "--extern",
    "cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcfg_if-50da2642d7d10359.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
    "-l",
    "static=keccak"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:02:21.678108+00:00",
  "end_time": "2026-07-13T15:02:21.755007+00:00",
  "start_unix_nanos": 1783954941678107400,
  "end_unix_nanos": 1783954941755006600,
  "crate_name": "sha3_asm",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T15:02:23.261711+00:00",
  "crate": "sha3-asm",
  "version": "0.1.4",
  "duration_seconds": 28.92605230002664,
  "trace_record_count": 32,
  "trace_owner_summary": {
    "owner_package_count": 5,
    "owner_packages": [
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml"
      },
      {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4/Cargo.toml"
      }
    ],
    "attributed_event_count": 25,
    "unattributed_event_count": 7,
    "owners": [
      {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "event_count": 25,
        "kind_counts": {
          "exec": 6,
          "link": 4,
          "exec_context": 6,
          "resolved_link": 1,
          "used_input": 5,
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
          "name": "cc",
          "version": "1.2.67",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
          "name": "cfg-if",
          "version": "1.0.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
          "name": "sha3-asm",
          "version": "0.1.4",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 18704,
      "ppid": 16524,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 18704,
      "ppid": 16524,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\rustctWyxmx\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000300       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000320       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000003f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000418       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000448       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000460       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400d4020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400d4298     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400d42b0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000300       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400d4300     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000320       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400d4320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400d4338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400d4348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400d4358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000003f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400d43f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400d4408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000418       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400d4418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000448       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400d4448     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000460       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400d4460     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-link-link-18704-1783954940385895800.map",
      "pid": 18704,
      "ppid": 16524,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-link-link-18704-1783954940385895800.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "perl",
        "cryptogams/x86_64/keccak1600-x86_64.pl",
        "masm",
        "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 4688,
      "ppid": 16208,
      "success": true,
      "tool": "perl",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "perl",
        "cryptogams/x86_64/keccak1600-x86_64.pl",
        "masm",
        "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
      ],
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "event_id": "used:perl:98cebc0f37704802:1fa7f5f13fc73252:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm",
      "pid": 4688,
      "sha256": "4d7fa2cd3e1132490675b387503bbe0ee9dd47c10d76b8633cabf58478470990",
      "success": true,
      "tool": "perl",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "perl",
        "cryptogams/x86_64/keccak1600-x86_64.pl",
        "masm",
        "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "inputs": [
        "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "perl",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "perl",
        "cryptogams/x86_64/keccak1600-x86_64.pl",
        "masm",
        "target/debug/build/sha3-asm-6a2ab6cd2950d00e/out/keccak1600-x86_64.asm"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
      "pid": 4688,
      "ppid": 16208,
      "profile": "debug",
      "real_tool": "C:\\Strawberry\\perl\\bin\\perl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "perl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 11580,
      "ppid": 16208,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
      ],
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "event_id": "used:cl:98cebc0f37704802:9b5eb95cf73c3c2a:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c",
      "pid": 11580,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\9106032913036688631detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
      "pid": 11580,
      "ppid": 16208,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 7476,
      "ppid": 16208,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
      "pid": 7476,
      "ppid": 16208,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze",
        "-DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze",
        "-D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext",
        "-DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext",
        "-D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb",
        "-DSHA3_absorb=KECCAK_ASM_SHA3_absorb",
        "-D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext",
        "-DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 11080,
      "ppid": 16208,
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze",
        "-DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze",
        "-D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext",
        "-DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext",
        "-D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb",
        "-DSHA3_absorb=KECCAK_ASM_SHA3_absorb",
        "-D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext",
        "-DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm"
      ],
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "event_id": "used:ml64:98cebc0f37704802:5b837add280f5f62:c3709c1e56f97bcb",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm",
      "pid": 11080,
      "sha256": "4d7fa2cd3e1132490675b387503bbe0ee9dd47c10d76b8633cabf58478470990",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze",
        "-DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze",
        "-D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext",
        "-DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext",
        "-D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb",
        "-DSHA3_absorb=KECCAK_ASM_SHA3_absorb",
        "-D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext",
        "-DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "kind": "compile",
      "language": "asm",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
      "src": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-D_SHA3_squeeze=_KECCAK_ASM_SHA3_squeeze",
        "-DSHA3_squeeze=KECCAK_ASM_SHA3_squeeze",
        "-D_SHA3_squeeze_cext=_KECCAK_ASM_SHA3_squeeze_cext",
        "-DSHA3_squeeze_cext=KECCAK_ASM_SHA3_squeeze_cext",
        "-D_SHA3_absorb=_KECCAK_ASM_SHA3_absorb",
        "-DSHA3_absorb=KECCAK_ASM_SHA3_absorb",
        "-D_SHA3_absorb_cext=_KECCAK_ASM_SHA3_absorb_cext",
        "-DSHA3_absorb_cext=KECCAK_ASM_SHA3_absorb_cext",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\keccak1600-x86_64.asm"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
      "pid": 11080,
      "ppid": 16208,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "ml64",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 16508,
      "ppid": 16208,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
      ],
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "event_id": "used:lib:98cebc0f37704802:c3709c1e56f97bcb:8fa157081a83bc07",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
      "pid": 16508,
      "sha256": "30e58c1928d87228d113eb15394024a640e7f77d1f8d611beec3b1c00c57f1a2",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
      ],
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "event_id": "used:lib:98cebc0f37704802:c3709c1e56f97bcb:b0c9498e7d5e9b51",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o",
      "pid": 16508,
      "sha256": "30e58c1928d87228d113eb15394024a640e7f77d1f8d611beec3b1c00c57f1a2",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\libkeccak.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out\\1bc19ca4e58ba05c-keccak1600-x86_64.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "cargo_pkg_name": "sha3-asm",
      "cargo_pkg_version": "0.1.4",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
      "pid": 16508,
      "ppid": 16208,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "sha3-asm",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "event_id": "bsrun:f5e7f3f8a8b78938:ed64e13ff5d8ecce:50f8ea1623c8eff3",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "0.1.4",
      "_owner": {
        "crate": "sha3-asm",
        "version": "0.1.4",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4#sha3-asm@0.1.4",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-uer0obgu/src/sha3-asm-0.1.4",
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
      "raw_event_count": 37715,
      "parsed_event_count": 37715,
      "parse_error_count": 0,
      "command_line_event_count": 37715,
      "build_script_root_event_count": 710,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 6240,
      "dropped_event_count": 19570
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16208,
      "ppid": 4988,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T15:02:20.890053+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8\\build-script-build.exe",
      "root_cargo_pid": 18424,
      "build_script_root_pid": 16208,
      "build_script_related": true,
      "build_script_target_dir": "sha3-asm-9935574e596261e8"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 4688,
      "ppid": 16208,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\perl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\perl.exe"
      ],
      "comm": "perl.exe",
      "time": "2026-07-13T15:02:20.974710+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\perl.exe",
      "root_cargo_pid": 18424,
      "build_script_root_pid": 16208,
      "build_script_related": true,
      "build_script_target_dir": "sha3-asm-9935574e596261e8"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12532,
      "ppid": 4688,
      "image": "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe"
      ],
      "comm": "perl.exe",
      "time": "2026-07-13T15:02:20.984536+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe",
      "root_cargo_pid": 18424,
      "build_script_root_pid": 16208,
      "build_script_related": true,
      "build_script_target_dir": "sha3-asm-9935574e596261e8"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13788,
      "ppid": 12532,
      "image": "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe"
      ],
      "comm": "perl.exe",
      "time": "2026-07-13T15:02:21.208872+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Strawberry\\perl\\bin\\perl.exe",
      "root_cargo_pid": 18424,
      "build_script_root_pid": 16208,
      "build_script_related": true,
      "build_script_target_dir": "sha3-asm-9935574e596261e8"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11580,
      "ppid": 16208,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T15:02:21.350988+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\.tmp\\native-trace-18356-1783954936947\\shims\\cl.exe",
      "root_cargo_pid": 18424,
      "build_script_root_pid": 16208,
      "build_script_related": true,
      "build_script_target_dir": "sha3-asm-9935574e596261e8"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 17852,
      "ppid": 19712,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
      "time": "2026-07-13T15:02:17.253399+00:00",
      "end_time": "2026-07-13T15:02:17.274644+00:00",
      "start_unix_nanos": 1783954937253399400,
      "end_unix_nanos": 1783954937274643600,
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
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 2652,
      "ppid": 19712,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
      "time": "2026-07-13T15:02:17.283182+00:00",
      "end_time": "2026-07-13T15:02:17.310953+00:00",
      "start_unix_nanos": 1783954937283182200,
      "end_unix_nanos": 1783954937310952900,
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
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 19820,
      "ppid": 19712,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
      "time": "2026-07-13T15:02:18.238385+00:00",
      "end_time": "2026-07-13T15:02:18.268013+00:00",
      "start_unix_nanos": 1783954938238385500,
      "end_unix_nanos": 1783954938268013500,
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
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 20544,
      "ppid": 4988,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
      "time": "2026-07-13T15:02:18.322975+00:00",
      "end_time": "2026-07-13T15:02:18.342179+00:00",
      "start_unix_nanos": 1783954938322974900,
      "end_unix_nanos": 1783954938342179200,
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
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 15640,
      "ppid": 4988,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
      "time": "2026-07-13T15:02:18.349883+00:00",
      "end_time": "2026-07-13T15:02:18.373002+00:00",
      "start_unix_nanos": 1783954938349883100,
      "end_unix_nanos": 1783954938373002100,
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
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 16984,
      "ppid": 4988,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
      "time": "2026-07-13T15:02:18.390062+00:00",
      "end_time": "2026-07-13T15:02:18.418713+00:00",
      "start_unix_nanos": 1783954938390062300,
      "end_unix_nanos": 1783954938418713300,
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
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 7760,
      "ppid": 4988,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "find_msvc_tools",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=a199b1cb5e329831",
        "-C",
        "extra-filename=-824f9ded730dd358",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "find_msvc_tools",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=a199b1cb5e329831",
        "-C",
        "extra-filename=-824f9ded730dd358",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:02:18.449712+00:00",
      "end_time": "2026-07-13T15:02:19.161948+00:00",
      "start_unix_nanos": 1783954938449712200,
      "end_unix_nanos": 1783954939161948000,
      "crate_name": "find_msvc_tools",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 7708,
      "ppid": 4988,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "shlex",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(manual_codegen_check)",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=181708ecadab3b47",
        "-C",
        "extra-filename=-f9df91f0b2c0ecd4",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "shlex",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(manual_codegen_check)",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=181708ecadab3b47",
        "-C",
        "extra-filename=-f9df91f0b2c0ecd4",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:02:18.451522+00:00",
      "end_time": "2026-07-13T15:02:18.765726+00:00",
      "start_unix_nanos": 1783954938451522200,
      "end_unix_nanos": 1783954938765726100,
      "crate_name": "shlex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 17776,
      "ppid": 4988,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cfg_if",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4\\src\\lib.rs",
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
        "cfg(feature, values(\"core\", \"rustc-dep-of-std\"))",
        "-C",
        "metadata=16c6d22a93f489b9",
        "-C",
        "extra-filename=-50da2642d7d10359",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cfg_if --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"core\\\", \\\"rustc-dep-of-std\\\"))\" -C metadata=16c6d22a93f489b9 -C extra-filename=-50da2642d7d10359 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cfg_if",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.4\\src\\lib.rs",
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
        "cfg(feature, values(\"core\", \"rustc-dep-of-std\"))",
        "-C",
        "metadata=16c6d22a93f489b9",
        "-C",
        "extra-filename=-50da2642d7d10359",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:02:18.466380+00:00",
      "end_time": "2026-07-13T15:02:18.620923+00:00",
      "start_unix_nanos": 1783954938466379600,
      "end_unix_nanos": 1783954938620923300,
      "crate_name": "cfg_if",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 17368,
      "ppid": 4988,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=98547e1a4afb2a03",
        "-C",
        "extra-filename=-24e0405f325d0f68",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=98547e1a4afb2a03",
        "-C",
        "extra-filename=-24e0405f325d0f68",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:02:18.972375+00:00",
      "end_time": "2026-07-13T15:02:20.017841+00:00",
      "start_unix_nanos": 1783954938972374800,
      "end_unix_nanos": 1783954940017840600,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 18576,
      "ppid": 4988,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
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
        "metadata=230ccf9129629ef5",
        "-C",
        "extra-filename=-9935574e596261e8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=230ccf9129629ef5 -C extra-filename=-9935574e596261e8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
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
        "metadata=230ccf9129629ef5",
        "-C",
        "extra-filename=-9935574e596261e8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:02:20.039493+00:00",
      "end_time": "2026-07-13T15:02:20.732300+00:00",
      "start_unix_nanos": 1783954940039492500,
      "end_unix_nanos": 1783954940732300400,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-9935574e596261e8"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "sha3-asm:0.1.4:2896",
      "root_process_pid": 18424,
      "pid": 4620,
      "ppid": 4988,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "sha3_asm",
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
        "metadata=f96032013dae0107",
        "-C",
        "extra-filename=-2ee9f6f1753daf9e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--extern",
        "cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcfg_if-50da2642d7d10359.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
        "-l",
        "static=keccak"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name sha3_asm --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=f96032013dae0107 -C extra-filename=-2ee9f6f1753daf9e --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps --extern cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcfg_if-50da2642d7d10359.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out -l static=keccak",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "sha3_asm",
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
        "metadata=f96032013dae0107",
        "-C",
        "extra-filename=-2ee9f6f1753daf9e",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps",
        "--extern",
        "cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps\\libcfg_if-50da2642d7d10359.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\build\\sha3-asm-6a2ab6cd2950d00e\\out",
        "-l",
        "static=keccak"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:02:21.678108+00:00",
      "end_time": "2026-07-13T15:02:21.755007+00:00",
      "start_unix_nanos": 1783954941678107400,
      "end_unix_nanos": 1783954941755006600,
      "crate_name": "sha3_asm",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-uer0obgu\\src\\sha3-asm-0.1.4\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 1743,
    "crate": "sha3-asm",
    "version": "0.1.4",
    "crate_id": "1081198",
    "version_id": "1266749",
    "downloads": 9098598,
    "cumulative_downloads": 99663388643,
    "cumulative_share_of_global": 0.37261840226334914,
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
