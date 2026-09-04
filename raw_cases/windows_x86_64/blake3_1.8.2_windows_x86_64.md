# `blake3` `1.8.2`

Platform: Windows x86_64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/target/debug/build/blake3-334cee71006a0189/out/libblake3_sse2_sse41_avx2_assembly.a`

Owner: `blake3` `1.8.2`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/c/blake3_avx2_x86-64_windows_msvc.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/c/blake3_sse2_x86-64_windows_msvc.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/c/blake3_sse41_x86-64_windows_msvc.asm`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse2_x86-64_windows_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
  "src": "c/blake3_sse2_x86-64_windows_msvc.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse41_x86-64_windows_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
  "src": "c/blake3_sse41_x86-64_windows_msvc.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_avx2_x86-64_windows_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
  "src": "c/blake3_avx2_x86-64_windows_msvc.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayref@0.3.9",
      "name": "arrayref",
      "version": "0.3.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayvec@0.7.6",
      "name": "arrayvec",
      "version": "0.7.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.9.0",
      "name": "bitflags",
      "version": "2.9.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.9.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.9.0"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
      "name": "blake3",
      "version": "1.8.2",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#block-buffer@0.10.4",
      "name": "block-buffer",
      "version": "0.10.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-buffer-0.10.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-buffer-0.10.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.19",
      "name": "cc",
      "version": "1.2.19",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#constant_time_eq@0.3.1",
      "name": "constant_time_eq",
      "version": "0.3.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crunchy@0.2.3",
      "name": "crunchy",
      "version": "0.2.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crunchy-0.2.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crunchy-0.2.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crypto-common@0.1.6",
      "name": "crypto-common",
      "version": "0.1.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crypto-common-0.1.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crypto-common-0.1.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#digest@0.10.7",
      "name": "digest",
      "version": "0.10.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\digest-0.10.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\digest-0.10.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.11",
      "name": "errno",
      "version": "0.3.11",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.11\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.3.0",
      "name": "fastrand",
      "version": "2.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#generic-array@0.14.7",
      "name": "generic-array",
      "version": "0.14.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\generic-array-0.14.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\generic-array-0.14.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.3.2",
      "name": "getrandom",
      "version": "0.3.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.3.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@2.6.0",
      "name": "half",
      "version": "2.6.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-2.6.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-2.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hex@0.4.3",
      "name": "hex",
      "version": "0.4.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hex-0.4.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hex-0.4.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hmac@0.12.1",
      "name": "hmac",
      "version": "0.12.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hmac-0.12.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hmac-0.12.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.15",
      "name": "itoa",
      "version": "1.0.15",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.15\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.172",
      "name": "libc",
      "version": "0.2.172",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.172\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.172"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.9.4",
      "name": "linux-raw-sys",
      "version": "0.9.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.9.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.9.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
      "name": "memchr",
      "version": "2.7.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.3",
      "name": "once_cell",
      "version": "1.21.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.21.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.21.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#page_size@0.6.0",
      "name": "page_size",
      "version": "0.6.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\page_size-0.6.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\page_size-0.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.21",
      "name": "ppv-lite86",
      "version": "0.2.21",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ppv-lite86-0.2.21\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ppv-lite86-0.2.21"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.95",
      "name": "proc-macro2",
      "version": "1.0.95",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.95\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.95"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.40",
      "name": "quote",
      "version": "1.0.40",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.40\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.40"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#r-efi@5.2.0",
      "name": "r-efi",
      "version": "5.2.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\r-efi-5.2.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\r-efi-5.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.9.1",
      "name": "rand",
      "version": "0.9.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand-0.9.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand-0.9.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.9.0",
      "name": "rand_chacha",
      "version": "0.9.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand_chacha-0.9.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand_chacha-0.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.9.3",
      "name": "rand_core",
      "version": "0.9.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand_core-0.9.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand_core-0.9.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@1.0.5",
      "name": "rustix",
      "version": "1.0.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-1.0.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-1.0.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.20",
      "name": "ryu",
      "version": "1.0.20",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.20\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.219",
      "name": "serde",
      "version": "1.0.219",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.219\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.219"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.219",
      "name": "serde_derive",
      "version": "1.0.219",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.219\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.219"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.140",
      "name": "serde_json",
      "version": "1.0.140",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.140\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.140"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
      "name": "shlex",
      "version": "1.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#subtle@2.6.1",
      "name": "subtle",
      "version": "2.6.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\subtle-2.6.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\subtle-2.6.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.100",
      "name": "syn",
      "version": "2.0.100",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.100\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.100"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tempfile@3.19.1",
      "name": "tempfile",
      "version": "3.19.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tempfile-3.19.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tempfile-3.19.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#typenum@1.18.0",
      "name": "typenum",
      "version": "1.18.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\typenum-1.18.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\typenum-1.18.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.18",
      "name": "unicode-ident",
      "version": "1.0.18",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.18\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
      "name": "version_check",
      "version": "0.9.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\version_check-0.9.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\version_check-0.9.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.14.2+wasi-0.2.4",
      "name": "wasi",
      "version": "0.14.2+wasi-0.2.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.14.2+wasi-0.2.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.14.2+wasi-0.2.4"
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
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wit-bindgen-rt@0.39.0",
      "name": "wit-bindgen-rt",
      "version": "0.39.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wit-bindgen-rt-0.39.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wit-bindgen-rt-0.39.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy@0.8.24",
      "name": "zerocopy",
      "version": "0.8.24",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-0.8.24\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-0.8.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy-derive@0.8.24",
      "name": "zerocopy-derive",
      "version": "0.8.24",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-derive-0.8.24\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-derive-0.8.24"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 9468,
  "ppid": 9496,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 9468,
  "ppid": 9496,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400c5020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400c5298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400c52b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400c5300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400c5320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400c5338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400c5348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400c5358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400c53f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400c5408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400c5418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400c5448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400c5460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-link-link-9468-1783954406906124400.map",
  "pid": 9468,
  "ppid": 9496,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-link-link-9468-1783954406906124400.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1212,
  "ppid": 17572,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:cl:7dbe6ed4dd2a2f8b:8332d6040290cf12:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c",
  "pid": 1212,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
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
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 1212,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15964,
  "ppid": 17572,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 15964,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 16764,
  "ppid": 17572,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:cl:7dbe6ed4dd2a2f8b:64ce40df26f6a2b1:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c",
  "pid": 16764,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
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
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 16764,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 12684,
  "ppid": 17572,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 12684,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "/arch:AVX512",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "exit_code": 0,
  "kind": "exec",
  "pid": 6720,
  "ppid": 17572,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "/arch:AVX512",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "event_id": "used:cl:a038f77be7e24393:6fae0e574b694dcd:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c",
  "pid": 6720,
  "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "/arch:AVX512",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
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
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "/arch:AVX512",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 6720,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17560,
  "ppid": 17572,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:cl:7dbe6ed4dd2a2f8b:185976d817eb5f81:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c",
  "pid": 17560,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
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
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 17560,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 12328,
  "ppid": 17572,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 12328,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse2_x86-64_windows_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 14608,
  "ppid": 17572,
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse2_x86-64_windows_msvc.asm"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:ml64:7dbe6ed4dd2a2f8b:efdafe39e47ee719:0135f3620c594628",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
  "path": "c/blake3_sse2_x86-64_windows_msvc.asm",
  "pid": 14608,
  "sha256": "27bf95d5611dca1530f85106748208a6d7a68f9a4f7f61670aa680bcc9a5e436",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse2_x86-64_windows_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
  "src": "c/blake3_sse2_x86-64_windows_msvc.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse2_x86-64_windows_msvc.asm"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 14608,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "ml64",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 32

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse41_x86-64_windows_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17492,
  "ppid": 17572,
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 33

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse41_x86-64_windows_msvc.asm"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:ml64:7dbe6ed4dd2a2f8b:6db08b70d5b7be02:7a2965ee1a024964",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
  "path": "c/blake3_sse41_x86-64_windows_msvc.asm",
  "pid": 17492,
  "sha256": "c3e218899b6b52e22c1d552392bf972e7ac513addc2c247635cf60325dc39724",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 34

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse41_x86-64_windows_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
  "src": "c/blake3_sse41_x86-64_windows_msvc.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 35

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_sse41_x86-64_windows_msvc.asm"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 17492,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "ml64",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_avx2_x86-64_windows_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17820,
  "ppid": 17572,
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 37

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_avx2_x86-64_windows_msvc.asm"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:ml64:7dbe6ed4dd2a2f8b:efbf8eef0d2cf031:fb855f27d9476655",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
  "path": "c/blake3_avx2_x86-64_windows_msvc.asm",
  "pid": 17820,
  "sha256": "2aad514ac8fb748accc8c0c0426606c91e6d404cff9c8499b2052e8108cbf67a",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 38

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_avx2_x86-64_windows_msvc.asm"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "compile",
  "language": "asm",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
  "src": "c/blake3_avx2_x86-64_windows_msvc.asm",
  "success": true,
  "tool": "ml64",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 39

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
    "-nologo",
    "-Zi",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
    "-c",
    "c/blake3_avx2_x86-64_windows_msvc.asm"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 17820,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "ml64",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 40

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 8916,
  "ppid": 17572,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 41

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:lib:7dbe6ed4dd2a2f8b:0135f3620c594628:7a2125144810b68d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
  "pid": 8916,
  "sha256": "62817aa9f8df08f1e32265006f81d3561cacc05337f8d85e84270281e1663202",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 42

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:lib:7dbe6ed4dd2a2f8b:7a2965ee1a024964:7a2125144810b68d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
  "pid": 8916,
  "sha256": "3d329259fe8fdd7297126cc7428ff9da356f0a743404213cc8868ad0de579bf3",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 43

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:lib:7dbe6ed4dd2a2f8b:fb855f27d9476655:7a2125144810b68d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
  "pid": 8916,
  "sha256": "2f930fd87a04e878168ac8ec815128f244ebc02320281f70742ee0ea66346872",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 44

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:lib:7dbe6ed4dd2a2f8b:0135f3620c594628:068a2270dda0f848",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
  "pid": 8916,
  "sha256": "62817aa9f8df08f1e32265006f81d3561cacc05337f8d85e84270281e1663202",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 45

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:lib:7dbe6ed4dd2a2f8b:7a2965ee1a024964:068a2270dda0f848",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
  "pid": 8916,
  "sha256": "3d329259fe8fdd7297126cc7428ff9da356f0a743404213cc8868ad0de579bf3",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 46

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "used:lib:7dbe6ed4dd2a2f8b:fb855f27d9476655:068a2270dda0f848",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
  "pid": 8916,
  "sha256": "2f930fd87a04e878168ac8ec815128f244ebc02320281f70742ee0ea66346872",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 47

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 48

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 49

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "cargo_pkg_name": "blake3",
  "cargo_pkg_version": "1.8.2",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "pid": 8916,
  "ppid": 17572,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 50

```json
{
  "crate": "blake3",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "event_id": "bsrun:b91ed8d348a61992:b0edf4c0a00e7f0d:a038f77be7e24393",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "1.8.2",
  "_owner": {
    "crate": "blake3",
    "version": "1.8.2",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
    "source": "cwd_prefix"
  }
}
```

#### Record 51

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
  "raw_event_count": 12203,
  "parsed_event_count": 12203,
  "parse_error_count": 0,
  "command_line_event_count": 12203,
  "build_script_root_event_count": 246,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 1145,
  "dropped_event_count": 6448
}
```

#### Record 52

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17572,
  "ppid": 17084,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:53:27.331621+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\build-script-build.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 53

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 1212,
  "ppid": 17572,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.399147+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 54

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 14660,
  "ppid": 1212,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.407118+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 55

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15964,
  "ppid": 17572,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.442020+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 56

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 5644,
  "ppid": 15964,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.447197+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 57

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16764,
  "ppid": 17572,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.491880+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 58

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 1048,
  "ppid": 16764,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.497443+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 59

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12684,
  "ppid": 17572,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.527870+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 60

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7364,
  "ppid": 12684,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.531871+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 61

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 6720,
  "ppid": 17572,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.570070+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 62

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 692,
  "ppid": 6720,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.575423+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 63

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16064,
  "ppid": 692,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
  ],
  "comm": "link.exe",
  "time": "2026-07-13T14:53:27.607143+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 64

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17560,
  "ppid": 17572,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.646210+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 65

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 18416,
  "ppid": 17560,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.669345+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 66

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12328,
  "ppid": 17572,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.695486+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 67

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17528,
  "ppid": 12328,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:27.699248+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 68

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 14608,
  "ppid": 17572,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe"
  ],
  "comm": "ml64.exe",
  "time": "2026-07-13T14:53:27.779200+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
  "root_cargo_pid": 17948,
  "build_script_root_pid": 17572,
  "build_script_related": true,
  "build_script_target_dir": "blake3-5b031c2601323f61"
}
```

#### Record 69

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 18328,
  "ppid": 9380,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
  "time": "2026-07-13T14:53:25.141102+00:00",
  "end_time": "2026-07-13T14:53:25.159355+00:00",
  "start_unix_nanos": 1783954405141101600,
  "end_unix_nanos": 1783954405159355400,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 70

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 17056,
  "ppid": 9380,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
  "time": "2026-07-13T14:53:25.165573+00:00",
  "end_time": "2026-07-13T14:53:25.185543+00:00",
  "start_unix_nanos": 1783954405165572900,
  "end_unix_nanos": 1783954405185543200,
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

#### Record 71

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 8140,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
  "time": "2026-07-13T14:53:25.717614+00:00",
  "end_time": "2026-07-13T14:53:25.736816+00:00",
  "start_unix_nanos": 1783954405717614200,
  "end_unix_nanos": 1783954405736815700,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 72

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 2852,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
  "time": "2026-07-13T14:53:25.743173+00:00",
  "end_time": "2026-07-13T14:53:25.764498+00:00",
  "start_unix_nanos": 1783954405743173200,
  "end_unix_nanos": 1783954405764498000,
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

#### Record 73

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 852,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
  "time": "2026-07-13T14:53:25.783504+00:00",
  "end_time": "2026-07-13T14:53:25.802769+00:00",
  "start_unix_nanos": 1783954405783503900,
  "end_unix_nanos": 1783954405802768700,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 74

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 17688,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "shlex",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=f9b15d7751a7b186",
    "-C",
    "extra-filename=-8a85cb2cd59e9679",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=f9b15d7751a7b186 -C extra-filename=-8a85cb2cd59e9679 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "shlex",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=f9b15d7751a7b186",
    "-C",
    "extra-filename=-8a85cb2cd59e9679",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:25.823881+00:00",
  "end_time": "2026-07-13T14:53:25.940900+00:00",
  "start_unix_nanos": 1783954405823881100,
  "end_unix_nanos": 1783954405940900100,
  "crate_name": "shlex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
}
```

#### Record 75

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 2352,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "arrayref",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9\\src\\lib.rs",
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
    "metadata=aeb3e2a397af42c1",
    "-C",
    "extra-filename=-ce1a5e6a0f1d627a",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name arrayref --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=aeb3e2a397af42c1 -C extra-filename=-ce1a5e6a0f1d627a --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "arrayref",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9\\src\\lib.rs",
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
    "metadata=aeb3e2a397af42c1",
    "-C",
    "extra-filename=-ce1a5e6a0f1d627a",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:25.826494+00:00",
  "end_time": "2026-07-13T14:53:25.875317+00:00",
  "start_unix_nanos": 1783954405826494500,
  "end_unix_nanos": 1783954405875316600,
  "crate_name": "arrayref",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
}
```

#### Record 76

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 3884,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "arrayvec",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6\\src\\lib.rs",
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
    "cfg(feature, values(\"borsh\", \"default\", \"serde\", \"std\", \"zeroize\"))",
    "-C",
    "metadata=e63f6a84baa9e942",
    "-C",
    "extra-filename=-95f6e18791952542",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name arrayvec --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"borsh\\\", \\\"default\\\", \\\"serde\\\", \\\"std\\\", \\\"zeroize\\\"))\" -C metadata=e63f6a84baa9e942 -C extra-filename=-95f6e18791952542 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "arrayvec",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6\\src\\lib.rs",
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
    "cfg(feature, values(\"borsh\", \"default\", \"serde\", \"std\", \"zeroize\"))",
    "-C",
    "metadata=e63f6a84baa9e942",
    "-C",
    "extra-filename=-95f6e18791952542",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:25.828959+00:00",
  "end_time": "2026-07-13T14:53:25.954585+00:00",
  "start_unix_nanos": 1783954405828958400,
  "end_unix_nanos": 1783954405954584900,
  "crate_name": "arrayvec",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
}
```

#### Record 77

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 17752,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "constant_time_eq",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1\\src\\lib.rs",
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
    "cfg(feature, values(\"count_instructions_test\"))",
    "-C",
    "metadata=e2ef305a3f376ad9",
    "-C",
    "extra-filename=-093430c99d1d82af",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name constant_time_eq --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"count_instructions_test\\\"))\" -C metadata=e2ef305a3f376ad9 -C extra-filename=-093430c99d1d82af --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "constant_time_eq",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1\\src\\lib.rs",
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
    "cfg(feature, values(\"count_instructions_test\"))",
    "-C",
    "metadata=e2ef305a3f376ad9",
    "-C",
    "extra-filename=-093430c99d1d82af",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:25.831531+00:00",
  "end_time": "2026-07-13T14:53:25.894976+00:00",
  "start_unix_nanos": 1783954405831531400,
  "end_unix_nanos": 1783954405894976300,
  "crate_name": "constant_time_eq",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
}
```

#### Record 78

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 17860,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cfg_if",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\src\\lib.rs",
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
    "cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\"))",
    "-C",
    "metadata=16ea0145ee2e0ba5",
    "-C",
    "extra-filename=-843a51089fab6e89",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cfg_if --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"compiler_builtins\\\", \\\"core\\\", \\\"rustc-dep-of-std\\\"))\" -C metadata=16ea0145ee2e0ba5 -C extra-filename=-843a51089fab6e89 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cfg_if",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\src\\lib.rs",
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
    "cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\"))",
    "-C",
    "metadata=16ea0145ee2e0ba5",
    "-C",
    "extra-filename=-843a51089fab6e89",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:25.834338+00:00",
  "end_time": "2026-07-13T14:53:25.875316+00:00",
  "start_unix_nanos": 1783954405834338000,
  "end_unix_nanos": 1783954405875315700,
  "crate_name": "cfg_if",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
}
```

#### Record 79

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 18100,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19\\src\\lib.rs",
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
    "metadata=5305698c107b59d4",
    "-C",
    "extra-filename=-a6f4ca31e9501b82",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=5305698c107b59d4 -C extra-filename=-a6f4ca31e9501b82 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19\\src\\lib.rs",
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
    "metadata=5305698c107b59d4",
    "-C",
    "extra-filename=-a6f4ca31e9501b82",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:25.900783+00:00",
  "end_time": "2026-07-13T14:53:26.673419+00:00",
  "start_unix_nanos": 1783954405900782900,
  "end_unix_nanos": 1783954406673418800,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
}
```

#### Record 80

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 11588,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"digest\", \"mmap\", \"neon\", \"no_avx2\", \"no_avx512\", \"no_neon\", \"no_sse2\", \"no_sse41\", \"prefer_intrinsics\", \"pure\", \"rayon\", \"serde\", \"std\", \"traits-preview\", \"wasm32_simd\", \"zeroize\"))",
    "-C",
    "metadata=f57211dad343dcf4",
    "-C",
    "extra-filename=-5b031c2601323f61",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcc-a6f4ca31e9501b82.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"digest\\\", \\\"mmap\\\", \\\"neon\\\", \\\"no_avx2\\\", \\\"no_avx512\\\", \\\"no_neon\\\", \\\"no_sse2\\\", \\\"no_sse41\\\", \\\"prefer_intrinsics\\\", \\\"pure\\\", \\\"rayon\\\", \\\"serde\\\", \\\"std\\\", \\\"traits-preview\\\", \\\"wasm32_simd\\\", \\\"zeroize\\\"))\" -C metadata=f57211dad343dcf4 -C extra-filename=-5b031c2601323f61 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcc-a6f4ca31e9501b82.rlib",
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
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"digest\", \"mmap\", \"neon\", \"no_avx2\", \"no_avx512\", \"no_neon\", \"no_sse2\", \"no_sse41\", \"prefer_intrinsics\", \"pure\", \"rayon\", \"serde\", \"std\", \"traits-preview\", \"wasm32_simd\", \"zeroize\"))",
    "-C",
    "metadata=f57211dad343dcf4",
    "-C",
    "extra-filename=-5b031c2601323f61",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcc-a6f4ca31e9501b82.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:26.690099+00:00",
  "end_time": "2026-07-13T14:53:27.186131+00:00",
  "start_unix_nanos": 1783954406690098900,
  "end_unix_nanos": 1783954407186130700,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61"
}
```

#### Record 81

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "blake3:1.8.2:11328",
  "root_process_pid": 17948,
  "pid": 3324,
  "ppid": 17084,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "blake3",
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
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"digest\", \"mmap\", \"neon\", \"no_avx2\", \"no_avx512\", \"no_neon\", \"no_sse2\", \"no_sse41\", \"prefer_intrinsics\", \"pure\", \"rayon\", \"serde\", \"std\", \"traits-preview\", \"wasm32_simd\", \"zeroize\"))",
    "-C",
    "metadata=37c7ed8eff779b60",
    "-C",
    "extra-filename=-b7b840fad2914a04",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--extern",
    "arrayref=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayref-ce1a5e6a0f1d627a.rmeta",
    "--extern",
    "arrayvec=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayvec-95f6e18791952542.rmeta",
    "--extern",
    "cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcfg_if-843a51089fab6e89.rmeta",
    "--extern",
    "constant_time_eq=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libconstant_time_eq-093430c99d1d82af.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
    "-l",
    "static=blake3_sse2_sse41_avx2_assembly",
    "--cfg",
    "blake3_sse2_ffi",
    "--cfg",
    "blake3_sse41_ffi",
    "--cfg",
    "blake3_avx2_ffi",
    "--check-cfg",
    "cfg(blake3_sse2_ffi, values(none()))",
    "--check-cfg",
    "cfg(blake3_sse2_rust, values(none()))",
    "--check-cfg",
    "cfg(blake3_sse41_ffi, values(none()))",
    "--check-cfg",
    "cfg(blake3_sse41_rust, values(none()))",
    "--check-cfg",
    "cfg(blake3_avx2_ffi, values(none()))",
    "--check-cfg",
    "cfg(blake3_avx2_rust, values(none()))",
    "--check-cfg",
    "cfg(blake3_avx512_ffi, values(none()))",
    "--check-cfg",
    "cfg(blake3_neon, values(none()))",
    "--check-cfg",
    "cfg(blake3_wasm32_simd, values(none()))"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name blake3 --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"digest\\\", \\\"mmap\\\", \\\"neon\\\", \\\"no_avx2\\\", \\\"no_avx512\\\", \\\"no_neon\\\", \\\"no_sse2\\\", \\\"no_sse41\\\", \\\"prefer_intrinsics\\\", \\\"pure\\\", \\\"rayon\\\", \\\"serde\\\", \\\"std\\\", \\\"traits-preview\\\", \\\"wasm32_simd\\\", \\\"zeroize\\\"))\" -C metadata=37c7ed8eff779b60 -C extra-filename=-b7b840fad2914a04 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --extern arrayref=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayref-ce1a5e6a0f1d627a.rmeta --extern arrayvec=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayvec-95f6e18791952542.rmeta --extern cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcfg_if-843a51089fab6e89.rmeta --extern constant_time_eq=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libconstant_time_eq-093430c99d1d82af.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out -l static=blake3_sse2_sse41_avx2_assembly --cfg blake3_sse2_ffi --cfg blake3_sse41_ffi --cfg blake3_avx2_ffi --check-cfg \"cfg(blake3_sse2_ffi, values(none()))\" --check-cfg \"cfg(blake3_sse2_rust, values(none()))\" --check-cfg \"cfg(blake3_sse41_ffi, values(none()))\" --check-cfg \"cfg(blake3_sse41_rust, values(none()))\" --check-cfg \"cfg(blake3_avx2_ffi, values(none()))\" --check-cfg \"cfg(blake3_avx2_rust, values(none()))\" --check-cfg \"cfg(blake3_avx512_ffi, values(none()))\" --check-cfg \"cfg(blake3_neon, values(none()))\" --check-cfg \"cfg(blake3_wasm32_simd, values(none()))\"",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "blake3",
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
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"digest\", \"mmap\", \"neon\", \"no_avx2\", \"no_avx512\", \"no_neon\", \"no_sse2\", \"no_sse41\", \"prefer_intrinsics\", \"pure\", \"rayon\", \"serde\", \"std\", \"traits-preview\", \"wasm32_simd\", \"zeroize\"))",
    "-C",
    "metadata=37c7ed8eff779b60",
    "-C",
    "extra-filename=-b7b840fad2914a04",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
    "--extern",
    "arrayref=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayref-ce1a5e6a0f1d627a.rmeta",
    "--extern",
    "arrayvec=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayvec-95f6e18791952542.rmeta",
    "--extern",
    "cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcfg_if-843a51089fab6e89.rmeta",
    "--extern",
    "constant_time_eq=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libconstant_time_eq-093430c99d1d82af.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
    "-l",
    "static=blake3_sse2_sse41_avx2_assembly",
    "--cfg",
    "blake3_sse2_ffi",
    "--cfg",
    "blake3_sse41_ffi",
    "--cfg",
    "blake3_avx2_ffi",
    "--check-cfg",
    "cfg(blake3_sse2_ffi, values(none()))",
    "--check-cfg",
    "cfg(blake3_sse2_rust, values(none()))",
    "--check-cfg",
    "cfg(blake3_sse41_ffi, values(none()))",
    "--check-cfg",
    "cfg(blake3_sse41_rust, values(none()))",
    "--check-cfg",
    "cfg(blake3_avx2_ffi, values(none()))",
    "--check-cfg",
    "cfg(blake3_avx2_rust, values(none()))",
    "--check-cfg",
    "cfg(blake3_avx512_ffi, values(none()))",
    "--check-cfg",
    "cfg(blake3_neon, values(none()))",
    "--check-cfg",
    "cfg(blake3_wasm32_simd, values(none()))"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:27.989233+00:00",
  "end_time": "2026-07-13T14:53:28.588093+00:00",
  "start_unix_nanos": 1783954407989232700,
  "end_unix_nanos": 1783954408588092800,
  "crate_name": "blake3",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:53:29.516724+00:00",
  "crate": "blake3",
  "version": "1.8.2",
  "duration_seconds": 27.235051999916323,
  "trace_record_count": 68,
  "trace_owner_summary": {
    "owner_package_count": 63,
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
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6/Cargo.toml"
      },
      {
        "crate": "constant_time_eq",
        "version": "0.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#constant_time_eq@0.3.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/constant_time_eq-0.3.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/constant_time_eq-0.3.1/Cargo.toml"
      },
      {
        "crate": "wasi",
        "version": "0.14.2+wasi-0.2.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.14.2+wasi-0.2.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.14.2+wasi-0.2.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.14.2+wasi-0.2.4/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6/Cargo.toml"
      },
      {
        "crate": "zerocopy-derive",
        "version": "0.8.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy-derive@0.8.24",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.8.24",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.8.24/Cargo.toml"
      },
      {
        "crate": "wit-bindgen-rt",
        "version": "0.39.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wit-bindgen-rt@0.39.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wit-bindgen-rt-0.39.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wit-bindgen-rt-0.39.0/Cargo.toml"
      },
      {
        "crate": "generic-array",
        "version": "0.14.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#generic-array@0.14.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/generic-array-0.14.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/generic-array-0.14.7/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.219",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.219",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.219",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.219/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.18",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/Cargo.toml"
      },
      {
        "crate": "block-buffer",
        "version": "0.10.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#block-buffer@0.10.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/block-buffer-0.10.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/block-buffer-0.10.4/Cargo.toml"
      },
      {
        "crate": "crypto-common",
        "version": "0.1.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crypto-common@0.1.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crypto-common-0.1.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crypto-common-0.1.6/Cargo.toml"
      },
      {
        "crate": "linux-raw-sys",
        "version": "0.9.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.9.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.9.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.9.4/Cargo.toml"
      },
      {
        "crate": "version_check",
        "version": "0.9.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.95",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.95",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.95",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.95/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.140",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.140",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.140/Cargo.toml"
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
        "crate": "ppv-lite86",
        "version": "0.2.21",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.21",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21/Cargo.toml"
      },
      {
        "crate": "rand_chacha",
        "version": "0.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.9.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.9.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.9.0/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.21.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.3/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.3.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.3.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.3.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.3.2/Cargo.toml"
      },
      {
        "crate": "page_size",
        "version": "0.6.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#page_size@0.6.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/page_size-0.6.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/page_size-0.6.0/Cargo.toml"
      },
      {
        "crate": "rand_core",
        "version": "0.9.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.9.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.9.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.9.3/Cargo.toml"
      },
      {
        "crate": "tempfile",
        "version": "3.19.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tempfile@3.19.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.19.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.19.1/Cargo.toml"
      },
      {
        "crate": "zerocopy",
        "version": "0.8.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy@0.8.24",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.24",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.24/Cargo.toml"
      },
      {
        "crate": "arrayref",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayref@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arrayref-0.3.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arrayref-0.3.9/Cargo.toml"
      },
      {
        "crate": "arrayvec",
        "version": "0.7.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayvec@0.7.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arrayvec-0.7.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/arrayvec-0.7.6/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "2.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.9.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.9.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.9.0/Cargo.toml"
      },
      {
        "crate": "ciborium",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.2/Cargo.toml"
      },
      {
        "crate": "fastrand",
        "version": "2.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0/Cargo.toml"
      },
      {
        "crate": "typenum",
        "version": "1.18.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#typenum@1.18.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typenum-1.18.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typenum-1.18.0/Cargo.toml"
      },
      {
        "crate": "crunchy",
        "version": "0.2.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crunchy@0.2.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crunchy-0.2.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crunchy-0.2.3/Cargo.toml"
      },
      {
        "crate": "digest",
        "version": "0.10.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#digest@0.10.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/digest-0.10.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/digest-0.10.7/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.219",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.219",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.219",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.219/Cargo.toml"
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
        "version": "0.3.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.11",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.11",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.11/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.172",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.172",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.172",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.172/Cargo.toml"
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
        "version": "1.0.40",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.40",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40/Cargo.toml"
      },
      {
        "crate": "rustix",
        "version": "1.0.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@1.0.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.0.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.0.5/Cargo.toml"
      },
      {
        "crate": "subtle",
        "version": "2.6.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#subtle@2.6.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/subtle-2.6.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/subtle-2.6.1/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "hmac",
        "version": "0.12.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hmac@0.12.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hmac-0.12.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hmac-0.12.1/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.15",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.15",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.15/Cargo.toml"
      },
      {
        "crate": "r-efi",
        "version": "5.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#r-efi@5.2.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-5.2.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-5.2.0/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "1.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.100",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.100",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.100",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.100/Cargo.toml"
      },
      {
        "crate": "half",
        "version": "2.6.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@2.6.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-2.6.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-2.6.0/Cargo.toml"
      },
      {
        "crate": "rand",
        "version": "0.9.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.9.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.9.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.9.1/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.20",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.20",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.20/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.19",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.19",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.19/Cargo.toml"
      },
      {
        "crate": "hex",
        "version": "0.4.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hex@0.4.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hex-0.4.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hex-0.4.3/Cargo.toml"
      },
      {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2/Cargo.toml"
      }
    ],
    "attributed_event_count": 49,
    "unattributed_event_count": 19,
    "owners": [
      {
        "crate": "blake3",
        "version": "1.8.2",
        "event_count": 49,
        "kind_counts": {
          "exec": 12,
          "link": 6,
          "exec_context": 12,
          "resolved_link": 1,
          "used_input": 13,
          "compile": 3,
          "archive": 1,
          "build_script_run": 1
        }
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayref@0.3.9",
          "name": "arrayref",
          "version": "0.3.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#arrayvec@0.7.6",
          "name": "arrayvec",
          "version": "0.7.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.9.0",
          "name": "bitflags",
          "version": "2.9.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.9.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-2.9.0"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
          "name": "blake3",
          "version": "1.8.2",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#block-buffer@0.10.4",
          "name": "block-buffer",
          "version": "0.10.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-buffer-0.10.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\block-buffer-0.10.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.19",
          "name": "cc",
          "version": "1.2.19",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#constant_time_eq@0.3.1",
          "name": "constant_time_eq",
          "version": "0.3.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crunchy@0.2.3",
          "name": "crunchy",
          "version": "0.2.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crunchy-0.2.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crunchy-0.2.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crypto-common@0.1.6",
          "name": "crypto-common",
          "version": "0.1.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crypto-common-0.1.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crypto-common-0.1.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#digest@0.10.7",
          "name": "digest",
          "version": "0.10.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\digest-0.10.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\digest-0.10.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.11",
          "name": "errno",
          "version": "0.3.11",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.11\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\errno-0.3.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.3.0",
          "name": "fastrand",
          "version": "2.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\fastrand-2.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#generic-array@0.14.7",
          "name": "generic-array",
          "version": "0.14.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\generic-array-0.14.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\generic-array-0.14.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.3.2",
          "name": "getrandom",
          "version": "0.3.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.3.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\getrandom-0.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@2.6.0",
          "name": "half",
          "version": "2.6.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-2.6.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-2.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hex@0.4.3",
          "name": "hex",
          "version": "0.4.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hex-0.4.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hex-0.4.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hmac@0.12.1",
          "name": "hmac",
          "version": "0.12.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hmac-0.12.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hmac-0.12.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.15",
          "name": "itoa",
          "version": "1.0.15",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.15\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.172",
          "name": "libc",
          "version": "0.2.172",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.172\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.172"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.9.4",
          "name": "linux-raw-sys",
          "version": "0.9.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.9.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\linux-raw-sys-0.9.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
          "name": "memchr",
          "version": "2.7.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.3",
          "name": "once_cell",
          "version": "1.21.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.21.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.21.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#page_size@0.6.0",
          "name": "page_size",
          "version": "0.6.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\page_size-0.6.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\page_size-0.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.21",
          "name": "ppv-lite86",
          "version": "0.2.21",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ppv-lite86-0.2.21\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ppv-lite86-0.2.21"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.95",
          "name": "proc-macro2",
          "version": "1.0.95",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.95\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.95"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.40",
          "name": "quote",
          "version": "1.0.40",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.40\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.40"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#r-efi@5.2.0",
          "name": "r-efi",
          "version": "5.2.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\r-efi-5.2.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\r-efi-5.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.9.1",
          "name": "rand",
          "version": "0.9.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand-0.9.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand-0.9.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.9.0",
          "name": "rand_chacha",
          "version": "0.9.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand_chacha-0.9.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand_chacha-0.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.9.3",
          "name": "rand_core",
          "version": "0.9.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand_core-0.9.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rand_core-0.9.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@1.0.5",
          "name": "rustix",
          "version": "1.0.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-1.0.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustix-1.0.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.20",
          "name": "ryu",
          "version": "1.0.20",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.20\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.219",
          "name": "serde",
          "version": "1.0.219",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.219\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.219"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.219",
          "name": "serde_derive",
          "version": "1.0.219",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.219\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.219"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.140",
          "name": "serde_json",
          "version": "1.0.140",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.140\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.140"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
          "name": "shlex",
          "version": "1.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#subtle@2.6.1",
          "name": "subtle",
          "version": "2.6.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\subtle-2.6.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\subtle-2.6.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.100",
          "name": "syn",
          "version": "2.0.100",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.100\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.100"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tempfile@3.19.1",
          "name": "tempfile",
          "version": "3.19.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tempfile-3.19.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tempfile-3.19.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#typenum@1.18.0",
          "name": "typenum",
          "version": "1.18.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\typenum-1.18.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\typenum-1.18.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.18",
          "name": "unicode-ident",
          "version": "1.0.18",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.18\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
          "name": "version_check",
          "version": "0.9.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\version_check-0.9.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\version_check-0.9.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.14.2+wasi-0.2.4",
          "name": "wasi",
          "version": "0.14.2+wasi-0.2.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.14.2+wasi-0.2.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasi-0.14.2+wasi-0.2.4"
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
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wit-bindgen-rt@0.39.0",
          "name": "wit-bindgen-rt",
          "version": "0.39.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wit-bindgen-rt-0.39.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wit-bindgen-rt-0.39.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy@0.8.24",
          "name": "zerocopy",
          "version": "0.8.24",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-0.8.24\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-0.8.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy-derive@0.8.24",
          "name": "zerocopy-derive",
          "version": "0.8.24",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-derive-0.8.24\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zerocopy-derive-0.8.24"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 9468,
      "ppid": 9496,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 9468,
      "ppid": 9496,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\rustcmbqJpY\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000300       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000320       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000003f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000418       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000448       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000460       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400c5020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400c5298     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400c52b0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000300       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400c5300     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000320       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400c5320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400c5338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400c5348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400c5358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000003f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400c53f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400c5408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000418       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400c5418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000448       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400c5448     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000460       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400c5460     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-link-link-9468-1783954406906124400.map",
      "pid": 9468,
      "ppid": 9496,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-link-link-9468-1783954406906124400.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1212,
      "ppid": 17572,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:cl:7dbe6ed4dd2a2f8b:8332d6040290cf12:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c",
      "pid": 1212,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
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
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5167856673149140598detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 1212,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15964,
      "ppid": 17572,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 15964,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 16764,
      "ppid": 17572,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:cl:7dbe6ed4dd2a2f8b:64ce40df26f6a2b1:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c",
      "pid": 16764,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
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
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\933919831823153169detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 16764,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 12684,
      "ppid": 17572,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 12684,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Brepro",
        "-W4",
        "/arch:AVX512",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "exit_code": 0,
      "kind": "exec",
      "pid": 6720,
      "ppid": 17572,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Brepro",
        "-W4",
        "/arch:AVX512",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "event_id": "used:cl:a038f77be7e24393:6fae0e574b694dcd:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c",
      "pid": 6720,
      "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Brepro",
        "-W4",
        "/arch:AVX512",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
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
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Brepro",
        "-W4",
        "/arch:AVX512",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\flag_check.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 6720,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17560,
      "ppid": 17572,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:cl:7dbe6ed4dd2a2f8b:185976d817eb5f81:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c",
      "pid": 17560,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
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
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\15051777523282667700detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 17560,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 12328,
      "ppid": 17572,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 12328,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_sse2_x86-64_windows_msvc.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 14608,
      "ppid": 17572,
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_sse2_x86-64_windows_msvc.asm"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:ml64:7dbe6ed4dd2a2f8b:efdafe39e47ee719:0135f3620c594628",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
      "path": "c/blake3_sse2_x86-64_windows_msvc.asm",
      "pid": 14608,
      "sha256": "27bf95d5611dca1530f85106748208a6d7a68f9a4f7f61670aa680bcc9a5e436",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_sse2_x86-64_windows_msvc.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "compile",
      "language": "asm",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
      "src": "c/blake3_sse2_x86-64_windows_msvc.asm",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_sse2_x86-64_windows_msvc.asm"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 14608,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "ml64",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_sse41_x86-64_windows_msvc.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17492,
      "ppid": 17572,
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_sse41_x86-64_windows_msvc.asm"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:ml64:7dbe6ed4dd2a2f8b:6db08b70d5b7be02:7a2965ee1a024964",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
      "path": "c/blake3_sse41_x86-64_windows_msvc.asm",
      "pid": 17492,
      "sha256": "c3e218899b6b52e22c1d552392bf972e7ac513addc2c247635cf60325dc39724",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_sse41_x86-64_windows_msvc.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "compile",
      "language": "asm",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
      "src": "c/blake3_sse41_x86-64_windows_msvc.asm",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_sse41_x86-64_windows_msvc.asm"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 17492,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "ml64",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_avx2_x86-64_windows_msvc.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17820,
      "ppid": 17572,
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_avx2_x86-64_windows_msvc.asm"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:ml64:7dbe6ed4dd2a2f8b:efbf8eef0d2cf031:fb855f27d9476655",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
      "path": "c/blake3_avx2_x86-64_windows_msvc.asm",
      "pid": 17820,
      "sha256": "2aad514ac8fb748accc8c0c0426606c91e6d404cff9c8499b2052e8108cbf67a",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_avx2_x86-64_windows_msvc.asm"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "compile",
      "language": "asm",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
      "src": "c/blake3_avx2_x86-64_windows_msvc.asm",
      "success": true,
      "tool": "ml64",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
        "-nologo",
        "-Zi",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
        "-c",
        "c/blake3_avx2_x86-64_windows_msvc.asm"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 17820,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\ml64.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "ml64",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 8916,
      "ppid": 17572,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:lib:7dbe6ed4dd2a2f8b:0135f3620c594628:7a2125144810b68d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
      "pid": 8916,
      "sha256": "62817aa9f8df08f1e32265006f81d3561cacc05337f8d85e84270281e1663202",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:lib:7dbe6ed4dd2a2f8b:7a2965ee1a024964:7a2125144810b68d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
      "pid": 8916,
      "sha256": "3d329259fe8fdd7297126cc7428ff9da356f0a743404213cc8868ad0de579bf3",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:lib:7dbe6ed4dd2a2f8b:fb855f27d9476655:7a2125144810b68d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
      "pid": 8916,
      "sha256": "2f930fd87a04e878168ac8ec815128f244ebc02320281f70742ee0ea66346872",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:lib:7dbe6ed4dd2a2f8b:0135f3620c594628:068a2270dda0f848",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
      "pid": 8916,
      "sha256": "62817aa9f8df08f1e32265006f81d3561cacc05337f8d85e84270281e1663202",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:lib:7dbe6ed4dd2a2f8b:7a2965ee1a024964:068a2270dda0f848",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
      "pid": 8916,
      "sha256": "3d329259fe8fdd7297126cc7428ff9da356f0a743404213cc8868ad0de579bf3",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "used:lib:7dbe6ed4dd2a2f8b:fb855f27d9476655:068a2270dda0f848",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o",
      "pid": 8916,
      "sha256": "2f930fd87a04e878168ac8ec815128f244ebc02320281f70742ee0ea66346872",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\libblake3_sse2_sse41_avx2_assembly.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse2_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_sse41_x86-64_windows_msvc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out\\5a6b5937ed079296-blake3_avx2_x86-64_windows_msvc.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "cargo_pkg_name": "blake3",
      "cargo_pkg_version": "1.8.2",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "pid": 8916,
      "ppid": 17572,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "blake3",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "event_id": "bsrun:b91ed8d348a61992:b0edf4c0a00e7f0d:a038f77be7e24393",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "1.8.2",
      "_owner": {
        "crate": "blake3",
        "version": "1.8.2",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2#blake3@1.8.2",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-ey86v0ro/src/blake3-1.8.2",
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
      "raw_event_count": 12203,
      "parsed_event_count": 12203,
      "parse_error_count": 0,
      "command_line_event_count": 12203,
      "build_script_root_event_count": 246,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 1145,
      "dropped_event_count": 6448
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17572,
      "ppid": 17084,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:53:27.331621+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61\\build-script-build.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 1212,
      "ppid": 17572,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.399147+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 14660,
      "ppid": 1212,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.407118+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15964,
      "ppid": 17572,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.442020+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 5644,
      "ppid": 15964,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.447197+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16764,
      "ppid": 17572,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.491880+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 1048,
      "ppid": 16764,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.497443+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12684,
      "ppid": 17572,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.527870+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7364,
      "ppid": 12684,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.531871+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 6720,
      "ppid": 17572,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.570070+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 692,
      "ppid": 6720,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.575423+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16064,
      "ppid": 692,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
      ],
      "comm": "link.exe",
      "time": "2026-07-13T14:53:27.607143+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17560,
      "ppid": 17572,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.646210+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 18416,
      "ppid": 17560,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.669345+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12328,
      "ppid": 17572,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.695486+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17528,
      "ppid": 12328,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:27.699248+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 14608,
      "ppid": 17572,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe"
      ],
      "comm": "ml64.exe",
      "time": "2026-07-13T14:53:27.779200+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\.tmp\\native-trace-16444-1783954404969\\shims\\ml64.exe",
      "root_cargo_pid": 17948,
      "build_script_root_pid": 17572,
      "build_script_related": true,
      "build_script_target_dir": "blake3-5b031c2601323f61"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 18328,
      "ppid": 9380,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
      "time": "2026-07-13T14:53:25.141102+00:00",
      "end_time": "2026-07-13T14:53:25.159355+00:00",
      "start_unix_nanos": 1783954405141101600,
      "end_unix_nanos": 1783954405159355400,
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
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 17056,
      "ppid": 9380,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
      "time": "2026-07-13T14:53:25.165573+00:00",
      "end_time": "2026-07-13T14:53:25.185543+00:00",
      "start_unix_nanos": 1783954405165572900,
      "end_unix_nanos": 1783954405185543200,
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
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 8140,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
      "time": "2026-07-13T14:53:25.717614+00:00",
      "end_time": "2026-07-13T14:53:25.736816+00:00",
      "start_unix_nanos": 1783954405717614200,
      "end_unix_nanos": 1783954405736815700,
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
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 2852,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
      "time": "2026-07-13T14:53:25.743173+00:00",
      "end_time": "2026-07-13T14:53:25.764498+00:00",
      "start_unix_nanos": 1783954405743173200,
      "end_unix_nanos": 1783954405764498000,
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
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 852,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
      "time": "2026-07-13T14:53:25.783504+00:00",
      "end_time": "2026-07-13T14:53:25.802769+00:00",
      "start_unix_nanos": 1783954405783503900,
      "end_unix_nanos": 1783954405802768700,
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
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 17688,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "shlex",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=f9b15d7751a7b186",
        "-C",
        "extra-filename=-8a85cb2cd59e9679",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=f9b15d7751a7b186 -C extra-filename=-8a85cb2cd59e9679 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "shlex",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=f9b15d7751a7b186",
        "-C",
        "extra-filename=-8a85cb2cd59e9679",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:25.823881+00:00",
      "end_time": "2026-07-13T14:53:25.940900+00:00",
      "start_unix_nanos": 1783954405823881100,
      "end_unix_nanos": 1783954405940900100,
      "crate_name": "shlex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 2352,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "arrayref",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9\\src\\lib.rs",
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
        "metadata=aeb3e2a397af42c1",
        "-C",
        "extra-filename=-ce1a5e6a0f1d627a",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name arrayref --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=aeb3e2a397af42c1 -C extra-filename=-ce1a5e6a0f1d627a --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "arrayref",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayref-0.3.9\\src\\lib.rs",
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
        "metadata=aeb3e2a397af42c1",
        "-C",
        "extra-filename=-ce1a5e6a0f1d627a",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:25.826494+00:00",
      "end_time": "2026-07-13T14:53:25.875317+00:00",
      "start_unix_nanos": 1783954405826494500,
      "end_unix_nanos": 1783954405875316600,
      "crate_name": "arrayref",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 3884,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "arrayvec",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6\\src\\lib.rs",
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
        "cfg(feature, values(\"borsh\", \"default\", \"serde\", \"std\", \"zeroize\"))",
        "-C",
        "metadata=e63f6a84baa9e942",
        "-C",
        "extra-filename=-95f6e18791952542",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name arrayvec --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"borsh\\\", \\\"default\\\", \\\"serde\\\", \\\"std\\\", \\\"zeroize\\\"))\" -C metadata=e63f6a84baa9e942 -C extra-filename=-95f6e18791952542 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "arrayvec",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\arrayvec-0.7.6\\src\\lib.rs",
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
        "cfg(feature, values(\"borsh\", \"default\", \"serde\", \"std\", \"zeroize\"))",
        "-C",
        "metadata=e63f6a84baa9e942",
        "-C",
        "extra-filename=-95f6e18791952542",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:25.828959+00:00",
      "end_time": "2026-07-13T14:53:25.954585+00:00",
      "start_unix_nanos": 1783954405828958400,
      "end_unix_nanos": 1783954405954584900,
      "crate_name": "arrayvec",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 17752,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "constant_time_eq",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1\\src\\lib.rs",
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
        "cfg(feature, values(\"count_instructions_test\"))",
        "-C",
        "metadata=e2ef305a3f376ad9",
        "-C",
        "extra-filename=-093430c99d1d82af",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name constant_time_eq --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"count_instructions_test\\\"))\" -C metadata=e2ef305a3f376ad9 -C extra-filename=-093430c99d1d82af --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "constant_time_eq",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\constant_time_eq-0.3.1\\src\\lib.rs",
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
        "cfg(feature, values(\"count_instructions_test\"))",
        "-C",
        "metadata=e2ef305a3f376ad9",
        "-C",
        "extra-filename=-093430c99d1d82af",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:25.831531+00:00",
      "end_time": "2026-07-13T14:53:25.894976+00:00",
      "start_unix_nanos": 1783954405831531400,
      "end_unix_nanos": 1783954405894976300,
      "crate_name": "constant_time_eq",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 17860,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cfg_if",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\src\\lib.rs",
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
        "cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\"))",
        "-C",
        "metadata=16ea0145ee2e0ba5",
        "-C",
        "extra-filename=-843a51089fab6e89",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cfg_if --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"compiler_builtins\\\", \\\"core\\\", \\\"rustc-dep-of-std\\\"))\" -C metadata=16ea0145ee2e0ba5 -C extra-filename=-843a51089fab6e89 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cfg_if",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cfg-if-1.0.0\\src\\lib.rs",
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
        "cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\"))",
        "-C",
        "metadata=16ea0145ee2e0ba5",
        "-C",
        "extra-filename=-843a51089fab6e89",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:25.834338+00:00",
      "end_time": "2026-07-13T14:53:25.875316+00:00",
      "start_unix_nanos": 1783954405834338000,
      "end_unix_nanos": 1783954405875315700,
      "crate_name": "cfg_if",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 18100,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19\\src\\lib.rs",
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
        "metadata=5305698c107b59d4",
        "-C",
        "extra-filename=-a6f4ca31e9501b82",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=5305698c107b59d4 -C extra-filename=-a6f4ca31e9501b82 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.19\\src\\lib.rs",
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
        "metadata=5305698c107b59d4",
        "-C",
        "extra-filename=-a6f4ca31e9501b82",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:25.900783+00:00",
      "end_time": "2026-07-13T14:53:26.673419+00:00",
      "start_unix_nanos": 1783954405900782900,
      "end_unix_nanos": 1783954406673418800,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 11588,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
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
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"digest\", \"mmap\", \"neon\", \"no_avx2\", \"no_avx512\", \"no_neon\", \"no_sse2\", \"no_sse41\", \"prefer_intrinsics\", \"pure\", \"rayon\", \"serde\", \"std\", \"traits-preview\", \"wasm32_simd\", \"zeroize\"))",
        "-C",
        "metadata=f57211dad343dcf4",
        "-C",
        "extra-filename=-5b031c2601323f61",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcc-a6f4ca31e9501b82.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"digest\\\", \\\"mmap\\\", \\\"neon\\\", \\\"no_avx2\\\", \\\"no_avx512\\\", \\\"no_neon\\\", \\\"no_sse2\\\", \\\"no_sse41\\\", \\\"prefer_intrinsics\\\", \\\"pure\\\", \\\"rayon\\\", \\\"serde\\\", \\\"std\\\", \\\"traits-preview\\\", \\\"wasm32_simd\\\", \\\"zeroize\\\"))\" -C metadata=f57211dad343dcf4 -C extra-filename=-5b031c2601323f61 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcc-a6f4ca31e9501b82.rlib",
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
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"digest\", \"mmap\", \"neon\", \"no_avx2\", \"no_avx512\", \"no_neon\", \"no_sse2\", \"no_sse41\", \"prefer_intrinsics\", \"pure\", \"rayon\", \"serde\", \"std\", \"traits-preview\", \"wasm32_simd\", \"zeroize\"))",
        "-C",
        "metadata=f57211dad343dcf4",
        "-C",
        "extra-filename=-5b031c2601323f61",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcc-a6f4ca31e9501b82.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:26.690099+00:00",
      "end_time": "2026-07-13T14:53:27.186131+00:00",
      "start_unix_nanos": 1783954406690098900,
      "end_unix_nanos": 1783954407186130700,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-5b031c2601323f61"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "blake3:1.8.2:11328",
      "root_process_pid": 17948,
      "pid": 3324,
      "ppid": 17084,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "blake3",
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
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"digest\", \"mmap\", \"neon\", \"no_avx2\", \"no_avx512\", \"no_neon\", \"no_sse2\", \"no_sse41\", \"prefer_intrinsics\", \"pure\", \"rayon\", \"serde\", \"std\", \"traits-preview\", \"wasm32_simd\", \"zeroize\"))",
        "-C",
        "metadata=37c7ed8eff779b60",
        "-C",
        "extra-filename=-b7b840fad2914a04",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--extern",
        "arrayref=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayref-ce1a5e6a0f1d627a.rmeta",
        "--extern",
        "arrayvec=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayvec-95f6e18791952542.rmeta",
        "--extern",
        "cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcfg_if-843a51089fab6e89.rmeta",
        "--extern",
        "constant_time_eq=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libconstant_time_eq-093430c99d1d82af.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
        "-l",
        "static=blake3_sse2_sse41_avx2_assembly",
        "--cfg",
        "blake3_sse2_ffi",
        "--cfg",
        "blake3_sse41_ffi",
        "--cfg",
        "blake3_avx2_ffi",
        "--check-cfg",
        "cfg(blake3_sse2_ffi, values(none()))",
        "--check-cfg",
        "cfg(blake3_sse2_rust, values(none()))",
        "--check-cfg",
        "cfg(blake3_sse41_ffi, values(none()))",
        "--check-cfg",
        "cfg(blake3_sse41_rust, values(none()))",
        "--check-cfg",
        "cfg(blake3_avx2_ffi, values(none()))",
        "--check-cfg",
        "cfg(blake3_avx2_rust, values(none()))",
        "--check-cfg",
        "cfg(blake3_avx512_ffi, values(none()))",
        "--check-cfg",
        "cfg(blake3_neon, values(none()))",
        "--check-cfg",
        "cfg(blake3_wasm32_simd, values(none()))"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name blake3 --edition=2021 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"digest\\\", \\\"mmap\\\", \\\"neon\\\", \\\"no_avx2\\\", \\\"no_avx512\\\", \\\"no_neon\\\", \\\"no_sse2\\\", \\\"no_sse41\\\", \\\"prefer_intrinsics\\\", \\\"pure\\\", \\\"rayon\\\", \\\"serde\\\", \\\"std\\\", \\\"traits-preview\\\", \\\"wasm32_simd\\\", \\\"zeroize\\\"))\" -C metadata=37c7ed8eff779b60 -C extra-filename=-b7b840fad2914a04 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps --extern arrayref=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayref-ce1a5e6a0f1d627a.rmeta --extern arrayvec=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayvec-95f6e18791952542.rmeta --extern cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcfg_if-843a51089fab6e89.rmeta --extern constant_time_eq=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libconstant_time_eq-093430c99d1d82af.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out -l static=blake3_sse2_sse41_avx2_assembly --cfg blake3_sse2_ffi --cfg blake3_sse41_ffi --cfg blake3_avx2_ffi --check-cfg \"cfg(blake3_sse2_ffi, values(none()))\" --check-cfg \"cfg(blake3_sse2_rust, values(none()))\" --check-cfg \"cfg(blake3_sse41_ffi, values(none()))\" --check-cfg \"cfg(blake3_sse41_rust, values(none()))\" --check-cfg \"cfg(blake3_avx2_ffi, values(none()))\" --check-cfg \"cfg(blake3_avx2_rust, values(none()))\" --check-cfg \"cfg(blake3_avx512_ffi, values(none()))\" --check-cfg \"cfg(blake3_neon, values(none()))\" --check-cfg \"cfg(blake3_wasm32_simd, values(none()))\"",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "blake3",
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
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"digest\", \"mmap\", \"neon\", \"no_avx2\", \"no_avx512\", \"no_neon\", \"no_sse2\", \"no_sse41\", \"prefer_intrinsics\", \"pure\", \"rayon\", \"serde\", \"std\", \"traits-preview\", \"wasm32_simd\", \"zeroize\"))",
        "-C",
        "metadata=37c7ed8eff779b60",
        "-C",
        "extra-filename=-b7b840fad2914a04",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps",
        "--extern",
        "arrayref=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayref-ce1a5e6a0f1d627a.rmeta",
        "--extern",
        "arrayvec=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libarrayvec-95f6e18791952542.rmeta",
        "--extern",
        "cfg_if=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libcfg_if-843a51089fab6e89.rmeta",
        "--extern",
        "constant_time_eq=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps\\libconstant_time_eq-093430c99d1d82af.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\build\\blake3-334cee71006a0189\\out",
        "-l",
        "static=blake3_sse2_sse41_avx2_assembly",
        "--cfg",
        "blake3_sse2_ffi",
        "--cfg",
        "blake3_sse41_ffi",
        "--cfg",
        "blake3_avx2_ffi",
        "--check-cfg",
        "cfg(blake3_sse2_ffi, values(none()))",
        "--check-cfg",
        "cfg(blake3_sse2_rust, values(none()))",
        "--check-cfg",
        "cfg(blake3_sse41_ffi, values(none()))",
        "--check-cfg",
        "cfg(blake3_sse41_rust, values(none()))",
        "--check-cfg",
        "cfg(blake3_avx2_ffi, values(none()))",
        "--check-cfg",
        "cfg(blake3_avx2_rust, values(none()))",
        "--check-cfg",
        "cfg(blake3_avx512_ffi, values(none()))",
        "--check-cfg",
        "cfg(blake3_neon, values(none()))",
        "--check-cfg",
        "cfg(blake3_wasm32_simd, values(none()))"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:27.989233+00:00",
      "end_time": "2026-07-13T14:53:28.588093+00:00",
      "start_unix_nanos": 1783954407989232700,
      "end_unix_nanos": 1783954408588092800,
      "crate_name": "blake3",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-ey86v0ro\\src\\blake3-1.8.2\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 787,
    "crate": "blake3",
    "version": "1.8.2",
    "crate_id": "165535",
    "version_id": "1532325",
    "downloads": 32531563,
    "cumulative_downloads": 83824380890,
    "cumulative_share_of_global": 0.3134000088019285,
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
