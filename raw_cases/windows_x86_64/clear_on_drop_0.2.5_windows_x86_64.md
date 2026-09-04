# `clear_on_drop` `0.2.5`

Platform: Windows x86_64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-45b8507410651c5a/out/libclear_on_drop.a`

Owner: `clear_on_drop` `0.2.5`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/src/hide.c`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
  "src": "src/hide.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
      "name": "aho-corasick",
      "version": "1.1.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
      "name": "atty",
      "version": "0.2.14",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atty-0.2.14\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atty-0.2.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
      "name": "autocfg",
      "version": "1.5.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.5.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
      "name": "bitflags",
      "version": "1.3.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.20.3",
      "name": "bumpalo",
      "version": "3.20.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.20.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.20.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
      "name": "cast",
      "version": "0.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cast-0.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cast-0.3.0"
    },
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@2.34.0",
      "name": "clap",
      "version": "2.34.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap-2.34.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap-2.34.0"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
      "name": "clear_on_drop",
      "version": "0.2.5",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.3.6",
      "name": "criterion",
      "version": "0.3.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-0.3.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-0.3.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.4.5",
      "name": "criterion-plot",
      "version": "0.4.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-plot-0.4.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-plot-0.4.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.7",
      "name": "crossbeam-deque",
      "version": "0.8.7",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-deque-0.8.7\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-deque-0.8.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.20",
      "name": "crossbeam-epoch",
      "version": "0.9.20",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-epoch-0.9.20\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-epoch-0.9.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
      "name": "crossbeam-utils",
      "version": "0.8.22",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.22\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.22"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv@1.4.0",
      "name": "csv",
      "version": "1.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\csv-1.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\csv-1.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv-core@0.1.13",
      "name": "csv-core",
      "version": "0.1.13",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\csv-core-0.1.13\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\csv-core-0.1.13"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
      "name": "either",
      "version": "1.16.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\either-1.16.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\either-1.16.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
      "name": "futures-core",
      "version": "0.3.32",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.32\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.32",
      "name": "futures-task",
      "version": "0.3.32",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.32\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.32",
      "name": "futures-util",
      "version": "0.3.32",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.32\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.3",
      "name": "half",
      "version": "1.8.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-1.8.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-1.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
      "name": "hermit-abi",
      "version": "0.1.19",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hermit-abi-0.1.19\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hermit-abi-0.1.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
      "name": "itertools",
      "version": "0.10.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itertools-0.10.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itertools-0.10.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
      "name": "itoa",
      "version": "1.0.18",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.18\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.103",
      "name": "js-sys",
      "version": "0.3.103",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.103\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.103"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
      "name": "lazy_static",
      "version": "1.5.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lazy_static-1.5.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lazy_static-1.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.8.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
      "name": "num-traits",
      "version": "0.2.19",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.19\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
      "name": "once_cell",
      "version": "1.21.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.21.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.21.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.5",
      "name": "oorandom",
      "version": "11.1.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\oorandom-11.1.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\oorandom-11.1.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
      "name": "pin-project-lite",
      "version": "0.2.17",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.17\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.17"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
      "name": "proc-macro2",
      "version": "1.0.106",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.106\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.106"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
      "name": "quote",
      "version": "1.0.46",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.46\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.46"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.12.0",
      "name": "rayon",
      "version": "1.12.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-1.12.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-1.12.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.13.0",
      "name": "rayon-core",
      "version": "1.13.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-core-1.13.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-core-1.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
      "name": "regex",
      "version": "1.13.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.13.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
      "name": "regex-automata",
      "version": "0.4.15",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.15\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
      "name": "regex-syntax",
      "version": "0.8.11",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.11\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
      "name": "rustversion",
      "version": "1.0.23",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.23\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
      "name": "ryu",
      "version": "1.0.23",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.23\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
      "name": "same-file",
      "version": "1.0.6",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
      "name": "serde",
      "version": "1.0.228",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.228\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_cbor@0.11.2",
      "name": "serde_cbor",
      "version": "0.11.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_cbor-0.11.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_cbor-0.11.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
      "name": "serde_core",
      "version": "1.0.228",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_core-1.0.228\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_core-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
      "name": "serde_derive",
      "version": "1.0.228",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.228\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
      "name": "serde_json",
      "version": "1.0.150",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.150\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.150"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.12",
      "name": "slab",
      "version": "0.4.12",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.12\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
      "name": "syn",
      "version": "2.0.118",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.118\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.11.0",
      "name": "textwrap",
      "version": "0.11.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\textwrap-0.11.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\textwrap-0.11.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
      "name": "tinytemplate",
      "version": "1.2.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tinytemplate-1.2.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tinytemplate-1.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
      "name": "unicode-ident",
      "version": "1.0.24",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.24\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
      "name": "unicode-width",
      "version": "0.1.14",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-width-0.1.14\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-width-0.1.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
      "name": "walkdir",
      "version": "2.5.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.5.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.126",
      "name": "wasm-bindgen",
      "version": "0.2.126",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.126\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.126",
      "name": "wasm-bindgen-macro",
      "version": "0.2.126",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.126\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.126",
      "name": "wasm-bindgen-macro-support",
      "version": "0.2.126",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.126\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.126",
      "name": "wasm-bindgen-shared",
      "version": "0.2.126",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.126\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.103",
      "name": "web-sys",
      "version": "0.3.103",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.103\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.103"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
      "name": "winapi-util",
      "version": "0.1.11",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.11\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
      "name": "winapi-x86_64-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
      "name": "windows-link",
      "version": "0.2.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-link-0.2.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-link-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
      "name": "windows-sys",
      "version": "0.61.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.61.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.61.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
      "name": "zmij",
      "version": "1.0.23",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zmij-1.0.23\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zmij-1.0.23"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 8516,
  "ppid": 9508,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:8ec30a5b040d00eb:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
  "pid": 8516,
  "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:1bff0ef5866ea252:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
  "pid": 8516,
  "sha256": "fea4410504655977d13d91d5831202161e0ab7be8938cfc4eb369e430a268bc7",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:68bb82e10735d05e:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
  "pid": 8516,
  "sha256": "935138cdb90f169f20d67de41ed8123206bdb77db40b7da2d56b11e855d03627",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:115e535edb76f010:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
  "pid": 8516,
  "sha256": "ec76565f36999b27616842fd44d56f23e319cd047d8d1e4cb9ac89a2152d90ec",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:286fbe0116c11822:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
  "pid": 8516,
  "sha256": "f9e8288cf51732df0883a37806af3f8dfcdec366297a172f65ff46be0980c6b0",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:809af221c2c412c5:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
  "pid": 8516,
  "sha256": "0c5ab7481ef258b10749d7c9981274642994bd5086019240d16c96feb3745899",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:fff51896254d3af4:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
  "pid": 8516,
  "sha256": "c996138dda0793fff865cfdffeee09da3fcc6ba7fbcdcbcad7e4565435545ca8",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:511b33ccb73d283f:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
  "pid": 8516,
  "sha256": "1a27d47b464cb08a898a6545585300260c0465c0c09a23f97012291df01a2f71",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:cad3155e319080ef:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
  "pid": 8516,
  "sha256": "52b37553a3645da30aa5516d4f44cb6d8bd3838b7f1df8f8ac2b1dc92fa3ea86",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:b5cfb3e94c457ceb:edad765a48f29353",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
  "pid": 8516,
  "sha256": "aec0d45486eddce8f4b7e27ad44d439dba056efb7d319d205b5a99484dd16495",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:1ceda9c220daf075:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "kernel32.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:85371f69e3a9e660:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "advapi32.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:d1e6be656f2676b2:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "ole32.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:2d852066e38e8bba:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "oleaut32.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:1ceda9c220daf075:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "kernel32.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:1ceda9c220daf075:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "kernel32.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:1ceda9c220daf075:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "kernel32.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:1db9512c4d5c31e6:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "ntdll.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:861f0814f9c52599:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "userenv.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:50848825683fdca9:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "ws2_32.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:link:5c05864675b24e15:df7d4e53c08047f7:edad765a48f29353",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "path": "dbghelp.lib",
  "pid": 8516,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [
    "kernel32.lib",
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib"
  ],
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 8516,
  "ppid": 9508,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
    "advapi32.lib",
    "ole32.lib",
    "oleaut32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400ce020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400ce298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400ce2b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400ce300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400ce320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400ce338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400ce348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400ce358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400ce3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400ce408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400ce418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400ce448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400ce460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-link-link-8516-1783962188931805500.map",
  "pid": 8516,
  "ppid": 9508,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-link-link-8516-1783962188931805500.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 2964,
  "ppid": 20860,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:cl:5c05864675b24e15:88e6f3f458c24cd9:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c",
  "pid": 2964,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
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
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
  "pid": 2964,
  "ppid": 20860,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 16776,
  "ppid": 20860,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 32

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
  "pid": 16776,
  "ppid": 20860,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 33

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 19948,
  "ppid": 20860,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 34

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:cl:5c05864675b24e15:830dde69ee9ce20d:3b9764e4a4c7a96d",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
  "path": "src/hide.c",
  "pid": 19948,
  "sha256": "ecbdd35277936d9d0e36161568ba2fb4f59e193ea964ec0f4f5e53b589620d42",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 35

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:cl:5c05864675b24e15:cc3e42b3f07c2d7f:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
  "pid": 19948,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:cl:5c05864675b24e15:830dde69ee9ce20d:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "src/hide.c",
  "pid": 19948,
  "sha256": "ecbdd35277936d9d0e36161568ba2fb4f59e193ea964ec0f4f5e53b589620d42",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 37

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
  "src": "src/hide.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 38

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
    "src/hide.c"
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
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 39

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
  "pid": 19948,
  "ppid": 20860,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 40

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 11972,
  "ppid": 20860,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 41

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:lib:5c05864675b24e15:3b9764e4a4c7a96d:d4a83a7940505051",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
  "pid": 11972,
  "sha256": "a172ea069fcc4a2783c967961695839d34cabb1509402bafc1aab4520341f013",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 42

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "used:lib:5c05864675b24e15:3b9764e4a4c7a96d:d5308a4d6b3021c9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
  "pid": 11972,
  "sha256": "a172ea069fcc4a2783c967961695839d34cabb1509402bafc1aab4520341f013",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 43

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 44

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 45

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
  "pid": 11972,
  "ppid": 20860,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 46

```json
{
  "crate": "clear_on_drop",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "bsrun:39a425c175c48698:dab5a47700b1d1a9:d077ada6f4c6c224",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 47

```json
{
  "crate": "clear_on_drop",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "event_id": "bsrun:39a425c175c48698:a0f76fe0cf2ee155:637f118ad0ecde28",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c/out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
  "success": true,
  "target": null,
  "version": "0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 48

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
  "raw_event_count": 52083,
  "parsed_event_count": 51969,
  "parse_error_count": 0,
  "command_line_event_count": 51969,
  "build_script_root_event_count": 778,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 11323,
  "dropped_event_count": 26906
}
```

#### Record 49

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 20860,
  "ppid": 18652,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T17:03:09.261663+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build-script-build.exe",
  "root_cargo_pid": 14452,
  "build_script_root_pid": 20860,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c/out"
}
```

#### Record 50

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 2964,
  "ppid": 20860,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:03:09.337103+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
  "root_cargo_pid": 14452,
  "build_script_root_pid": 20860,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c/out",
  "_direct_build_script_child": true,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 51

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 20932,
  "ppid": 2964,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:03:09.346748+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 14452,
  "build_script_root_pid": 20860,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c/out"
}
```

#### Record 52

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16776,
  "ppid": 20860,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:03:09.388008+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
  "root_cargo_pid": 14452,
  "build_script_root_pid": 20860,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c/out",
  "_direct_build_script_child": true,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 53

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 6768,
  "ppid": 16776,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:03:09.394232+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 14452,
  "build_script_root_pid": 20860,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c/out"
}
```

#### Record 54

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 19948,
  "ppid": 20860,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:03:09.437529+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
  "root_cargo_pid": 14452,
  "build_script_root_pid": 20860,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c/out",
  "_direct_build_script_child": true,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 55

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 8244,
  "ppid": 17940,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
  "time": "2026-07-13T17:03:06.769075+00:00",
  "end_time": "2026-07-13T17:03:06.788321+00:00",
  "start_unix_nanos": 1783962186769075500,
  "end_unix_nanos": 1783962186788320600,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 56

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 19020,
  "ppid": 17940,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
  "time": "2026-07-13T17:03:06.795823+00:00",
  "end_time": "2026-07-13T17:03:06.818564+00:00",
  "start_unix_nanos": 1783962186795823100,
  "end_unix_nanos": 1783962186818564400,
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

#### Record 57

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 15160,
  "ppid": 17940,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
  "time": "2026-07-13T17:03:07.119209+00:00",
  "end_time": "2026-07-13T17:03:07.138419+00:00",
  "start_unix_nanos": 1783962187119208900,
  "end_unix_nanos": 1783962187138419100,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 58

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 19772,
  "ppid": 18652,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
  "time": "2026-07-13T17:03:07.376549+00:00",
  "end_time": "2026-07-13T17:03:07.396585+00:00",
  "start_unix_nanos": 1783962187376548500,
  "end_unix_nanos": 1783962187396584400,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 59

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 12656,
  "ppid": 18652,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
  "time": "2026-07-13T17:03:07.403905+00:00",
  "end_time": "2026-07-13T17:03:07.435019+00:00",
  "start_unix_nanos": 1783962187403905100,
  "end_unix_nanos": 1783962187435019600,
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

#### Record 60

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 20160,
  "ppid": 18652,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
  "time": "2026-07-13T17:03:07.546561+00:00",
  "end_time": "2026-07-13T17:03:07.568606+00:00",
  "start_unix_nanos": 1783962187546561500,
  "end_unix_nanos": 1783962187568606100,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 61

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 14884,
  "ppid": 18652,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:07.590442+00:00",
  "end_time": "2026-07-13T17:03:07.736576+00:00",
  "start_unix_nanos": 1783962187590441600,
  "end_unix_nanos": 1783962187736576300,
  "crate_name": "shlex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps"
}
```

#### Record 62

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 8100,
  "ppid": 18652,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:07.593696+00:00",
  "end_time": "2026-07-13T17:03:08.108563+00:00",
  "start_unix_nanos": 1783962187593696200,
  "end_unix_nanos": 1783962188108562600,
  "crate_name": "find_msvc_tools",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps"
}
```

#### Record 63

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 15708,
  "ppid": 18652,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:07.917816+00:00",
  "end_time": "2026-07-13T17:03:08.736324+00:00",
  "start_unix_nanos": 1783962187917815900,
  "end_unix_nanos": 1783962188736323600,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps"
}
```

#### Record 64

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 5900,
  "ppid": 18652,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
    "cfg(feature, values(\"nightly\", \"no_cc\"))",
    "-C",
    "metadata=b8feda8a85a20e8d",
    "-C",
    "extra-filename=-f8a22ca61ed6a61c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"nightly\\\", \\\"no_cc\\\"))\" -C metadata=b8feda8a85a20e8d -C extra-filename=-f8a22ca61ed6a61c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
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
    "cfg(feature, values(\"nightly\", \"no_cc\"))",
    "-C",
    "metadata=b8feda8a85a20e8d",
    "-C",
    "extra-filename=-f8a22ca61ed6a61c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:08.753315+00:00",
  "end_time": "2026-07-13T17:03:09.108640+00:00",
  "start_unix_nanos": 1783962188753315400,
  "end_unix_nanos": 1783962189108640400,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c"
}
```

#### Record 65

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "clear_on_drop:0.2.5:17260",
  "root_process_pid": 14452,
  "pid": 18896,
  "ppid": 18652,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "clear_on_drop",
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
    "cfg(feature, values(\"nightly\", \"no_cc\"))",
    "-C",
    "metadata=a3392dd33cbdef48",
    "-C",
    "extra-filename=-500319c5cc70a38f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
    "-l",
    "static=clear_on_drop"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name clear_on_drop --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"nightly\\\", \\\"no_cc\\\"))\" -C metadata=a3392dd33cbdef48 -C extra-filename=-500319c5cc70a38f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out -l static=clear_on_drop",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "clear_on_drop",
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
    "cfg(feature, values(\"nightly\", \"no_cc\"))",
    "-C",
    "metadata=a3392dd33cbdef48",
    "-C",
    "extra-filename=-500319c5cc70a38f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
    "-l",
    "static=clear_on_drop"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:03:09.609050+00:00",
  "end_time": "2026-07-13T17:03:09.768638+00:00",
  "start_unix_nanos": 1783962189609050000,
  "end_unix_nanos": 1783962189768638100,
  "crate_name": "clear_on_drop",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T17:03:11.228269+00:00",
  "crate": "clear_on_drop",
  "version": "0.2.5",
  "duration_seconds": 27.04553800006397,
  "trace_record_count": 54,
  "trace_owner_summary": {
    "owner_package_count": 72,
    "owner_packages": [
      {
        "crate": "wasm-bindgen-macro-support",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126/Cargo.toml"
      },
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
        "crate": "wasm-bindgen-shared",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126/Cargo.toml"
      },
      {
        "crate": "pin-project-lite",
        "version": "0.2.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml"
      },
      {
        "crate": "crossbeam-epoch",
        "version": "0.9.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.20",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/Cargo.toml"
      },
      {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml"
      },
      {
        "crate": "plotters-backend",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7/Cargo.toml"
      },
      {
        "crate": "crossbeam-deque",
        "version": "0.8.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/Cargo.toml"
      },
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml"
      },
      {
        "crate": "criterion-plot",
        "version": "0.4.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.4.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml"
      },
      {
        "crate": "unicode-width",
        "version": "0.1.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.126",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126/Cargo.toml"
      },
      {
        "crate": "futures-core",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml"
      },
      {
        "crate": "futures-task",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.32",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32/Cargo.toml"
      },
      {
        "crate": "futures-util",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.32",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml"
      },
      {
        "crate": "plotters-svg",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7/Cargo.toml"
      },
      {
        "crate": "rustversion",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23/Cargo.toml"
      },
      {
        "crate": "serde_core",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.150",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml"
      },
      {
        "crate": "tinytemplate",
        "version": "1.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml"
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
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.61.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml"
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
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/Cargo.toml"
      },
      {
        "crate": "rayon-core",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.13.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0/Cargo.toml"
      },
      {
        "crate": "serde_cbor",
        "version": "0.11.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_cbor@0.11.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2/Cargo.toml"
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
        "version": "1.21.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml"
      },
      {
        "crate": "criterion",
        "version": "0.3.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.3.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6/Cargo.toml"
      },
      {
        "crate": "csv-core",
        "version": "0.1.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv-core@0.1.13",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13/Cargo.toml"
      },
      {
        "crate": "oorandom",
        "version": "11.1.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5/Cargo.toml"
      },
      {
        "crate": "same-file",
        "version": "1.0.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml"
      },
      {
        "crate": "textwrap",
        "version": "0.11.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.11.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0/Cargo.toml"
      },
      {
        "crate": "web-sys",
        "version": "0.3.103",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.103",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "1.3.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/Cargo.toml"
      },
      {
        "crate": "bumpalo",
        "version": "3.20.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.20.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3/Cargo.toml"
      },
      {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/Cargo.toml"
      },
      {
        "crate": "js-sys",
        "version": "0.3.103",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.103",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103/Cargo.toml"
      },
      {
        "crate": "plotters",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "either",
        "version": "1.16.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml"
      },
      {
        "crate": "walkdir",
        "version": "2.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml"
      },
      {
        "crate": "rayon",
        "version": "1.12.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.12.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml"
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
        "version": "2.34.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@2.34.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml"
      },
      {
        "crate": "slab",
        "version": "0.4.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.12",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml"
      },
      {
        "crate": "zmij",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml"
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
        "version": "1.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml"
      },
      {
        "crate": "csv",
        "version": "1.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv@1.4.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 46,
    "unattributed_event_count": 8,
    "owners": [
      {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "event_count": 46,
        "kind_counts": {
          "exec": 5,
          "used_input": 27,
          "link": 4,
          "exec_context": 5,
          "resolved_link": 1,
          "compile": 1,
          "archive": 1,
          "build_script_run": 2
        }
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
          "name": "aho-corasick",
          "version": "1.1.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
          "name": "atty",
          "version": "0.2.14",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atty-0.2.14\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\atty-0.2.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
          "name": "autocfg",
          "version": "1.5.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.5.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\autocfg-1.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
          "name": "bitflags",
          "version": "1.3.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bitflags-1.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.20.3",
          "name": "bumpalo",
          "version": "3.20.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.20.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\bumpalo-3.20.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
          "name": "cast",
          "version": "0.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cast-0.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cast-0.3.0"
        },
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@2.34.0",
          "name": "clap",
          "version": "2.34.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap-2.34.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\clap-2.34.0"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
          "name": "clear_on_drop",
          "version": "0.2.5",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.3.6",
          "name": "criterion",
          "version": "0.3.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-0.3.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-0.3.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.4.5",
          "name": "criterion-plot",
          "version": "0.4.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-plot-0.4.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\criterion-plot-0.4.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.7",
          "name": "crossbeam-deque",
          "version": "0.8.7",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-deque-0.8.7\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-deque-0.8.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.20",
          "name": "crossbeam-epoch",
          "version": "0.9.20",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-epoch-0.9.20\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-epoch-0.9.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
          "name": "crossbeam-utils",
          "version": "0.8.22",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.22\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\crossbeam-utils-0.8.22"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv@1.4.0",
          "name": "csv",
          "version": "1.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\csv-1.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\csv-1.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv-core@0.1.13",
          "name": "csv-core",
          "version": "0.1.13",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\csv-core-0.1.13\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\csv-core-0.1.13"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
          "name": "either",
          "version": "1.16.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\either-1.16.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\either-1.16.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
          "name": "futures-core",
          "version": "0.3.32",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.32\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-core-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.32",
          "name": "futures-task",
          "version": "0.3.32",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.32\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-task-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.32",
          "name": "futures-util",
          "version": "0.3.32",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.32\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\futures-util-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.3",
          "name": "half",
          "version": "1.8.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-1.8.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\half-1.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
          "name": "hermit-abi",
          "version": "0.1.19",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hermit-abi-0.1.19\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hermit-abi-0.1.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
          "name": "itertools",
          "version": "0.10.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itertools-0.10.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itertools-0.10.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
          "name": "itoa",
          "version": "1.0.18",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.18\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.103",
          "name": "js-sys",
          "version": "0.3.103",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.103\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\js-sys-0.3.103"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
          "name": "lazy_static",
          "version": "1.5.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lazy_static-1.5.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\lazy_static-1.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.8.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
          "name": "num-traits",
          "version": "0.2.19",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.19\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\num-traits-0.2.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
          "name": "once_cell",
          "version": "1.21.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.21.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\once_cell-1.21.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.5",
          "name": "oorandom",
          "version": "11.1.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\oorandom-11.1.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\oorandom-11.1.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
          "name": "pin-project-lite",
          "version": "0.2.17",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.17\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pin-project-lite-0.2.17"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
          "name": "proc-macro2",
          "version": "1.0.106",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.106\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.106"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
          "name": "quote",
          "version": "1.0.46",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.46\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.46"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.12.0",
          "name": "rayon",
          "version": "1.12.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-1.12.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-1.12.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.13.0",
          "name": "rayon-core",
          "version": "1.13.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-core-1.13.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rayon-core-1.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
          "name": "regex",
          "version": "1.13.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.13.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
          "name": "regex-automata",
          "version": "0.4.15",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.15\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
          "name": "regex-syntax",
          "version": "0.8.11",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.11\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
          "name": "rustversion",
          "version": "1.0.23",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.23\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\rustversion-1.0.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
          "name": "ryu",
          "version": "1.0.23",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.23\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
          "name": "same-file",
          "version": "1.0.6",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\same-file-1.0.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
          "name": "serde",
          "version": "1.0.228",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.228\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_cbor@0.11.2",
          "name": "serde_cbor",
          "version": "0.11.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_cbor-0.11.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_cbor-0.11.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
          "name": "serde_core",
          "version": "1.0.228",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_core-1.0.228\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_core-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
          "name": "serde_derive",
          "version": "1.0.228",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.228\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
          "name": "serde_json",
          "version": "1.0.150",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.150\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.150"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.12",
          "name": "slab",
          "version": "0.4.12",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.12\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\slab-0.4.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
          "name": "syn",
          "version": "2.0.118",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.118\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.11.0",
          "name": "textwrap",
          "version": "0.11.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\textwrap-0.11.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\textwrap-0.11.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
          "name": "tinytemplate",
          "version": "1.2.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tinytemplate-1.2.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tinytemplate-1.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
          "name": "unicode-ident",
          "version": "1.0.24",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.24\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
          "name": "unicode-width",
          "version": "0.1.14",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-width-0.1.14\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-width-0.1.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
          "name": "walkdir",
          "version": "2.5.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.5.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\walkdir-2.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.126",
          "name": "wasm-bindgen",
          "version": "0.2.126",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.126\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.126",
          "name": "wasm-bindgen-macro",
          "version": "0.2.126",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.126\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.126",
          "name": "wasm-bindgen-macro-support",
          "version": "0.2.126",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.126\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-macro-support-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.126",
          "name": "wasm-bindgen-shared",
          "version": "0.2.126",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.126\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\wasm-bindgen-shared-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.103",
          "name": "web-sys",
          "version": "0.3.103",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.103\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\web-sys-0.3.103"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
          "name": "winapi-util",
          "version": "0.1.11",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.11\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-util-0.1.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
          "name": "winapi-x86_64-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\winapi-x86_64-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
          "name": "windows-link",
          "version": "0.2.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-link-0.2.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-link-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
          "name": "windows-sys",
          "version": "0.61.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.61.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\windows-sys-0.61.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
          "name": "zmij",
          "version": "1.0.23",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zmij-1.0.23\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\zmij-1.0.23"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 8516,
      "ppid": 9508,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:8ec30a5b040d00eb:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
      "pid": 8516,
      "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:1bff0ef5866ea252:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
      "pid": 8516,
      "sha256": "fea4410504655977d13d91d5831202161e0ab7be8938cfc4eb369e430a268bc7",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:68bb82e10735d05e:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
      "pid": 8516,
      "sha256": "935138cdb90f169f20d67de41ed8123206bdb77db40b7da2d56b11e855d03627",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:115e535edb76f010:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
      "pid": 8516,
      "sha256": "ec76565f36999b27616842fd44d56f23e319cd047d8d1e4cb9ac89a2152d90ec",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:286fbe0116c11822:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
      "pid": 8516,
      "sha256": "f9e8288cf51732df0883a37806af3f8dfcdec366297a172f65ff46be0980c6b0",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:809af221c2c412c5:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
      "pid": 8516,
      "sha256": "0c5ab7481ef258b10749d7c9981274642994bd5086019240d16c96feb3745899",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:fff51896254d3af4:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
      "pid": 8516,
      "sha256": "c996138dda0793fff865cfdffeee09da3fcc6ba7fbcdcbcad7e4565435545ca8",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:511b33ccb73d283f:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
      "pid": 8516,
      "sha256": "1a27d47b464cb08a898a6545585300260c0465c0c09a23f97012291df01a2f71",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:cad3155e319080ef:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
      "pid": 8516,
      "sha256": "52b37553a3645da30aa5516d4f44cb6d8bd3838b7f1df8f8ac2b1dc92fa3ea86",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:b5cfb3e94c457ceb:edad765a48f29353",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
      "pid": 8516,
      "sha256": "aec0d45486eddce8f4b7e27ad44d439dba056efb7d319d205b5a99484dd16495",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:1ceda9c220daf075:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "kernel32.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:85371f69e3a9e660:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "advapi32.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:d1e6be656f2676b2:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "ole32.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:2d852066e38e8bba:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "oleaut32.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:1ceda9c220daf075:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "kernel32.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:1ceda9c220daf075:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "kernel32.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:1ceda9c220daf075:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "kernel32.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:1db9512c4d5c31e6:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "ntdll.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:861f0814f9c52599:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "userenv.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:50848825683fdca9:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "ws2_32.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:link:5c05864675b24e15:df7d4e53c08047f7:edad765a48f29353",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "path": "dbghelp.lib",
      "pid": 8516,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [
        "kernel32.lib",
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib"
      ],
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 8516,
      "ppid": 9508,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\rustcMVGQHn\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.1ncxf32drff71rj05bsst15uh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.2nt49501yr52qwfa4nd3wgnrh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.30uezphe5eefjekbh3c9skajb.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.4r5veg7lv7v7x680w6zl318t1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9hp4c4bf3zc4o2jd4ljoilf05.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.9xv0h0e3xniykkup9p45dgwkh.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.bsin734y7j8unlqcvbav5w315.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.dx976a0khitydsh1tr7s780t5.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.b13qt4359tlwnie73h1lwp1a1.0a8fwnu.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rlib",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rlib",
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
        "advapi32.lib",
        "ole32.lib",
        "oleaut32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build_script_build-f8a22ca61ed6a61c.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000300       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000320       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000003f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000418       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000448       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000460       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400ce020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400ce298     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400ce2b0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000300       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400ce300     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000320       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400ce320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400ce338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400ce348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400ce358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000003f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400ce3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400ce408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000418       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400ce418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000448       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400ce448     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000460       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400ce460     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-link-link-8516-1783962188931805500.map",
      "pid": 8516,
      "ppid": 9508,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-link-link-8516-1783962188931805500.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 2964,
      "ppid": 20860,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:cl:5c05864675b24e15:88e6f3f458c24cd9:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c",
      "pid": 2964,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
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
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\18076374218062889608detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
      "pid": 2964,
      "ppid": 20860,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 16776,
      "ppid": 20860,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
      "pid": 16776,
      "ppid": 20860,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 19948,
      "ppid": 20860,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:cl:5c05864675b24e15:830dde69ee9ce20d:3b9764e4a4c7a96d",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
      "path": "src/hide.c",
      "pid": 19948,
      "sha256": "ecbdd35277936d9d0e36161568ba2fb4f59e193ea964ec0f4f5e53b589620d42",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:cl:5c05864675b24e15:cc3e42b3f07c2d7f:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
      "pid": 19948,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:cl:5c05864675b24e15:830dde69ee9ce20d:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "src/hide.c",
      "pid": 19948,
      "sha256": "ecbdd35277936d9d0e36161568ba2fb4f59e193ea964ec0f4f5e53b589620d42",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
      "src": "src/hide.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
        "src/hide.c"
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
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
      "pid": 19948,
      "ppid": 20860,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 11972,
      "ppid": 20860,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:lib:5c05864675b24e15:3b9764e4a4c7a96d:d4a83a7940505051",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
      "pid": 11972,
      "sha256": "a172ea069fcc4a2783c967961695839d34cabb1509402bafc1aab4520341f013",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "used:lib:5c05864675b24e15:3b9764e4a4c7a96d:d5308a4d6b3021c9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o",
      "pid": 11972,
      "sha256": "a172ea069fcc4a2783c967961695839d34cabb1509402bafc1aab4520341f013",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\libclear_on_drop.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out\\ea708c7824d36062-hide.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
      "pid": 11972,
      "ppid": 20860,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "clear_on_drop",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "bsrun:39a425c175c48698:dab5a47700b1d1a9:d077ada6f4c6c224",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "clear_on_drop",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "event_id": "bsrun:39a425c175c48698:a0f76fe0cf2ee155:637f118ad0ecde28",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5/target/debug/build/clear_on_drop-f8a22ca61ed6a61c/out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
      "success": true,
      "target": null,
      "version": "0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-i4_f5ivg/src/clear_on_drop-0.2.5",
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
      "raw_event_count": 52083,
      "parsed_event_count": 51969,
      "parse_error_count": 0,
      "command_line_event_count": 51969,
      "build_script_root_event_count": 778,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 11323,
      "dropped_event_count": 26906
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 20860,
      "ppid": 18652,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T17:03:09.261663+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c\\build-script-build.exe",
      "root_cargo_pid": 14452,
      "build_script_root_pid": 20860,
      "build_script_related": true,
      "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 2964,
      "ppid": 20860,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:03:09.337103+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
      "root_cargo_pid": 14452,
      "build_script_root_pid": 20860,
      "build_script_related": true,
      "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 20932,
      "ppid": 2964,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:03:09.346748+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 14452,
      "build_script_root_pid": 20860,
      "build_script_related": true,
      "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16776,
      "ppid": 20860,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:03:09.388008+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
      "root_cargo_pid": 14452,
      "build_script_root_pid": 20860,
      "build_script_related": true,
      "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 6768,
      "ppid": 16776,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:03:09.394232+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 14452,
      "build_script_root_pid": 20860,
      "build_script_related": true,
      "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 19948,
      "ppid": 20860,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:03:09.437529+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\.tmp\\native-trace-20776-1783962186538\\shims\\cl.exe",
      "root_cargo_pid": 14452,
      "build_script_root_pid": 20860,
      "build_script_related": true,
      "build_script_target_dir": "clear_on_drop-f8a22ca61ed6a61c"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 8244,
      "ppid": 17940,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
      "time": "2026-07-13T17:03:06.769075+00:00",
      "end_time": "2026-07-13T17:03:06.788321+00:00",
      "start_unix_nanos": 1783962186769075500,
      "end_unix_nanos": 1783962186788320600,
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
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 19020,
      "ppid": 17940,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
      "time": "2026-07-13T17:03:06.795823+00:00",
      "end_time": "2026-07-13T17:03:06.818564+00:00",
      "start_unix_nanos": 1783962186795823100,
      "end_unix_nanos": 1783962186818564400,
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
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 15160,
      "ppid": 17940,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
      "time": "2026-07-13T17:03:07.119209+00:00",
      "end_time": "2026-07-13T17:03:07.138419+00:00",
      "start_unix_nanos": 1783962187119208900,
      "end_unix_nanos": 1783962187138419100,
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
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 19772,
      "ppid": 18652,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
      "time": "2026-07-13T17:03:07.376549+00:00",
      "end_time": "2026-07-13T17:03:07.396585+00:00",
      "start_unix_nanos": 1783962187376548500,
      "end_unix_nanos": 1783962187396584400,
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
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 12656,
      "ppid": 18652,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
      "time": "2026-07-13T17:03:07.403905+00:00",
      "end_time": "2026-07-13T17:03:07.435019+00:00",
      "start_unix_nanos": 1783962187403905100,
      "end_unix_nanos": 1783962187435019600,
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
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 20160,
      "ppid": 18652,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
      "time": "2026-07-13T17:03:07.546561+00:00",
      "end_time": "2026-07-13T17:03:07.568606+00:00",
      "start_unix_nanos": 1783962187546561500,
      "end_unix_nanos": 1783962187568606100,
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
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 14884,
      "ppid": 18652,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:07.590442+00:00",
      "end_time": "2026-07-13T17:03:07.736576+00:00",
      "start_unix_nanos": 1783962187590441600,
      "end_unix_nanos": 1783962187736576300,
      "crate_name": "shlex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 8100,
      "ppid": 18652,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:07.593696+00:00",
      "end_time": "2026-07-13T17:03:08.108563+00:00",
      "start_unix_nanos": 1783962187593696200,
      "end_unix_nanos": 1783962188108562600,
      "crate_name": "find_msvc_tools",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 15708,
      "ppid": 18652,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:07.917816+00:00",
      "end_time": "2026-07-13T17:03:08.736324+00:00",
      "start_unix_nanos": 1783962187917815900,
      "end_unix_nanos": 1783962188736323600,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 5900,
      "ppid": 18652,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
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
        "cfg(feature, values(\"nightly\", \"no_cc\"))",
        "-C",
        "metadata=b8feda8a85a20e8d",
        "-C",
        "extra-filename=-f8a22ca61ed6a61c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"nightly\\\", \\\"no_cc\\\"))\" -C metadata=b8feda8a85a20e8d -C extra-filename=-f8a22ca61ed6a61c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
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
        "cfg(feature, values(\"nightly\", \"no_cc\"))",
        "-C",
        "metadata=b8feda8a85a20e8d",
        "-C",
        "extra-filename=-f8a22ca61ed6a61c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:08.753315+00:00",
      "end_time": "2026-07-13T17:03:09.108640+00:00",
      "start_unix_nanos": 1783962188753315400,
      "end_unix_nanos": 1783962189108640400,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-f8a22ca61ed6a61c"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "clear_on_drop:0.2.5:17260",
      "root_process_pid": 14452,
      "pid": 18896,
      "ppid": 18652,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "clear_on_drop",
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
        "cfg(feature, values(\"nightly\", \"no_cc\"))",
        "-C",
        "metadata=a3392dd33cbdef48",
        "-C",
        "extra-filename=-500319c5cc70a38f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
        "-l",
        "static=clear_on_drop"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name clear_on_drop --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"nightly\\\", \\\"no_cc\\\"))\" -C metadata=a3392dd33cbdef48 -C extra-filename=-500319c5cc70a38f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out -l static=clear_on_drop",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "clear_on_drop",
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
        "cfg(feature, values(\"nightly\", \"no_cc\"))",
        "-C",
        "metadata=a3392dd33cbdef48",
        "-C",
        "extra-filename=-500319c5cc70a38f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\build\\clear_on_drop-45b8507410651c5a\\out",
        "-l",
        "static=clear_on_drop"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:03:09.609050+00:00",
      "end_time": "2026-07-13T17:03:09.768638+00:00",
      "start_unix_nanos": 1783962189609050000,
      "end_unix_nanos": 1783962189768638100,
      "crate_name": "clear_on_drop",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-i4_f5ivg\\src\\clear_on_drop-0.2.5\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 3476,
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "crate_id": "8065",
    "version_id": "533357",
    "downloads": 2857540,
    "cumulative_downloads": 108423880455,
    "cumulative_share_of_global": 0.4053718587379386,
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
