# `clear_on_drop` `0.2.5`

Platform: Linux aarch64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a`

Owner: `clear_on_drop` `0.2.5`

### Source files

* `/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5/src/hide.c`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "src/hide.c",
    "-quiet",
    "-dumpbase",
    "hide.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "..."
  ],
  "src": "src/hide.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 875463,
  "ppid": 875462,
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 875177,
  "build_script_root_pid": 875458,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 875465,
  "ppid": 875458,
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 875177,
  "build_script_root_pid": 875458,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
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
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "workspace_root": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
      "name": "aho-corasick",
      "version": "1.1.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
      "name": "atty",
      "version": "0.2.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
      "name": "autocfg",
      "version": "1.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
      "name": "bitflags",
      "version": "1.3.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.20.3",
      "name": "bumpalo",
      "version": "3.20.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
      "name": "cast",
      "version": "0.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
      "name": "cc",
      "version": "1.2.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
      "name": "cfg-if",
      "version": "1.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@2.34.0",
      "name": "clap",
      "version": "2.34.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
      "name": "clear_on_drop",
      "version": "0.2.5",
      "manifest_path": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.3.6",
      "name": "criterion",
      "version": "0.3.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.4.5",
      "name": "criterion-plot",
      "version": "0.4.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.7",
      "name": "crossbeam-deque",
      "version": "0.8.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.20",
      "name": "crossbeam-epoch",
      "version": "0.9.20",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
      "name": "crossbeam-utils",
      "version": "0.8.22",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv@1.4.0",
      "name": "csv",
      "version": "1.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv-core@0.1.13",
      "name": "csv-core",
      "version": "0.1.13",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
      "name": "either",
      "version": "1.16.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
      "name": "futures-core",
      "version": "0.3.32",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.32",
      "name": "futures-task",
      "version": "0.3.32",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.32",
      "name": "futures-util",
      "version": "0.3.32",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.3",
      "name": "half",
      "version": "1.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
      "name": "hermit-abi",
      "version": "0.1.19",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
      "name": "itertools",
      "version": "0.10.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
      "name": "itoa",
      "version": "1.0.18",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.103",
      "name": "js-sys",
      "version": "0.3.103",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
      "name": "lazy_static",
      "version": "1.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
      "name": "num-traits",
      "version": "0.2.19",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
      "name": "once_cell",
      "version": "1.21.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.5",
      "name": "oorandom",
      "version": "11.1.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
      "name": "pin-project-lite",
      "version": "0.2.17",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
      "name": "plotters",
      "version": "0.3.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
      "name": "plotters-backend",
      "version": "0.3.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
      "name": "plotters-svg",
      "version": "0.3.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
      "name": "proc-macro2",
      "version": "1.0.106",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
      "name": "quote",
      "version": "1.0.46",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.12.0",
      "name": "rayon",
      "version": "1.12.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.13.0",
      "name": "rayon-core",
      "version": "1.13.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
      "name": "regex",
      "version": "1.13.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
      "name": "regex-automata",
      "version": "0.4.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
      "name": "regex-syntax",
      "version": "0.8.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
      "name": "rustversion",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
      "name": "ryu",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
      "name": "same-file",
      "version": "1.0.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
      "name": "serde",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_cbor@0.11.2",
      "name": "serde_cbor",
      "version": "0.11.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
      "name": "serde_core",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
      "name": "serde_derive",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
      "name": "serde_json",
      "version": "1.0.150",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.12",
      "name": "slab",
      "version": "0.4.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
      "name": "syn",
      "version": "2.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.11.0",
      "name": "textwrap",
      "version": "0.11.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
      "name": "tinytemplate",
      "version": "1.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
      "name": "unicode-ident",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
      "name": "unicode-width",
      "version": "0.1.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
      "name": "walkdir",
      "version": "2.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.126",
      "name": "wasm-bindgen",
      "version": "0.2.126",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.126",
      "name": "wasm-bindgen-macro",
      "version": "0.2.126",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.126",
      "name": "wasm-bindgen-macro-support",
      "version": "0.2.126",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.126",
      "name": "wasm-bindgen-shared",
      "version": "0.2.126",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.103",
      "name": "web-sys",
      "version": "0.3.103",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
      "name": "winapi",
      "version": "0.3.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
      "name": "winapi-i686-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
      "name": "winapi-util",
      "version": "0.1.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
      "name": "winapi-x86_64-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
      "name": "windows-link",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
      "name": "windows-sys",
      "version": "0.61.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
      "name": "zmij",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23"
    }
  ],
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 875437,
  "ppid": 875423,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:8ed0fca1fdc3ea79:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
  "pid": 875437,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:2cc2a88d00af5e02:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
  "pid": 875437,
  "sha256": "5afbec68ed40ad6b37cc1f615597ce8acd69271550760432b8a5ef2db3a47502",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:8e3a3067584f6cdf:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
  "pid": 875437,
  "sha256": "a9ff4fab86d9f2801cd6fe51c4346bf29b18edf8b102a584cd4a658ca2b210ef",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:12b87021280df528:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
  "pid": 875437,
  "sha256": "08c899738f261cf1bdd6fd8c86f389965a07757fd3158be800830e069ed4d730",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:2ce3062fdf244e6a:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
  "pid": 875437,
  "sha256": "6f3e412dc616030560ee543d0919ff5998f318466f95b4e01afce864424d09f2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:7dc84ced023ba780:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
  "pid": 875437,
  "sha256": "a8aa8a0750dc530394cda67e856c73feaaf1f253c41eb9b788314bd361cf4715",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:382dedf4b1f2b8f2:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
  "pid": 875437,
  "sha256": "feb974ba589f85baa440a120095f3465df6703017409edbe51a6ef9e03d7db2e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:82173b664572d25c:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
  "pid": 875437,
  "sha256": "57c222de0b0240b57be8673af28c185426de21b62307a11bd21c4d15043b2c8d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:35ed01a5b7e9d141:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
  "pid": 875437,
  "sha256": "155c0dd3a0795355188fb8caaf765d86c5f5b151d0dfa60a1e96392071a0c4e4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:b638a78f527ba3c5:cd378ad8752ed5a7:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
  "pid": 875437,
  "sha256": "00bdc4bedc6940977b7809080c8598657c074c7db36a0b7c642000ffa0d84b61",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
  ],
  "libs": [
    "gcc_s",
    "util",
    "rt",
    "pthread",
    "m",
    "dl",
    "c"
  ],
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "context_path": "/tmp/native-trace-875140-1783997572218/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-875140-1783997572218/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 875437,
  "ppid": 875423,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib(shlex-f2fa52250b1d670f.shlex.352c8e657ac65ae8-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib(std-d1237ef7159db0a2.std.e28293b1aa0f68bd-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib(panic_unwind-4be5972b22d3a6da.panic_unwind.d9b2f7d287d2f9d2-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib(object-2a81194c9d07bbf6.object.4f4cc23e276cbdd5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib(memchr-ea71fa85f6699d6b.memchr.9642f0ce76a98c65-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib(addr2line-a79a8816d9fd6004.addr2line.39b02397e671b2d1-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib(gimli-46dc78dc6a8cb06a.gimli.9d272e8433f81454-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib(rustc_demangle-146c3f1190dee2e2.rustc_demangle.c5a78273c295e539-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib(hashbrown-1448c95121de53aa.hashbrown.c0386ddbfadcbbc1-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib(miniz_oxide-5ad929a15a8e6727.miniz_oxide.b662226d77c6ee8e-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib(adler2-1f570ee5c6635aae.adler2.1d6706876a417dbf-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib(alloc-6e6df4ffe0af4d15.alloc.fdfd2bd8633a6659-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib(core-120cbae4e86ec454.core.c1f1a4ba060b9bfa-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.132.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.187.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.201.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
      "kind": "object",
      "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.261.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libm.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libmvec.so.1",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-875437-1783997574980271213.map",
  "pid": 875437,
  "ppid": 875423,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-875437-1783997574980271213.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 0,
  "parsed_event_count": 0,
  "phase": "start",
  "platform": "linux_ebpf",
  "raw_event_count": 0,
  "spawn_error": null,
  "stderr": "",
  "stdout": ""
}
```

#### Record 17

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 138,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 139,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "0.111   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            875177 875140   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n0.122   cargo            875178 875157   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n0.123   rustc            875179 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.133   rustc            875183 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.166   rustc            875190 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n0.166   rustc            875191 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n0.171   rustc            875197 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name version_check --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de4e2c29a5a03308 ...\n0.171   rustc            875200 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name once_cell --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"race\" --check-cfg cfg(docsrs,test) ...\n0.171   rustc            875199 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\")) -C metadata=44346b50c4e9393e ...\n0.171   rustc            875203 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerocopy --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.7.35/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"__internal_use_only_features_that_work_on_stable\", \"alloc\", \"byteorder\", \"default\", \"derive\", \"simd\", \"simd ...\n0.172   rustc            875205 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libm-0.2.11/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"force-soft-floats\", \"unstable\")) -C metadata=d3c80d784b571fe6 ...\n0.173   rustc            875206 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"use_std\")) -C metadata=b95e3260cc387c27 ...\n0.173   rustc            875207 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ryu --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\", \"small\")) -C metadata=d897da932e6d081b ...\n0.174   rustc            875208 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"32_bit_limbs\", \"bin_build\", \"doc-images\", \"embed-doc-image\", \"enable_pyo3\", \"enable_serde\", \"float_helpers\" -C metadata=901ba5ff8206392c ...\n0.207   cc               875251 875208   0 /tmp/native-trace-875157-1783997572290/shims/cc -m64 /target/debug/build/malachite-nz-0a453eba9576b92e/rustcjPnlvD/symbols.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.4gfy13mc7bx9q35wq4kiuxeak.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.5orosh8uci9mizcbhbzr6d9rc.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.89qs6bwmpw7u1ruzktae2wr54.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.8d3w2xcpnkbowv8go275tdgn5.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.b01o0sy7lxdgp913vrb3pmu62.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.7m5fhhic994jdurk7ucpabj28.0b02m5y.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n0.208   cc               875253 875251   0 /usr/bin/cc -m64 /target/debug/build/malachite-nz-0a453eba9576b92e/rustcjPnlvD/symbols.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.4gfy13mc7bx9q35wq4kiuxeak.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.5orosh8uci9mizcbhbzr6d9rc.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.89qs6bwmpw7u1ruzktae2wr54.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.8d3w2xcpnkbowv8go275tdgn5.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.b01o0sy7lxdgp913vrb3pmu62.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.7m5fhhic994jdurk7ucpabj28.0b02m5y.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n0.211   collect2         875254 875253   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccVPpaJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.213   ld.lld           875255 875254   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccVPpaJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e ...\n0.214   rust-lld         875255 875254   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccVPpaJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.218   cc               875256 875205   0 /tmp/native-trace-875157-1783997572290/shims/cc -m64 /target/debug/build/libm-910d88a93f185b04/rustcpsO7u9/symbols.o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04.build_script_build.f6b38c9b0eadb864-cgu.0.rcgu.o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04.8l5jcmjrty1l8geid53ytmrq0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n0.219   cc               875257 875256   0 /usr/bin/cc -m64 /target/debug/build/libm-910d88a93f185b04/rustcpsO7u9/symbols.o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04.build_script_build.f6b38c9b0eadb864-cgu.0.rcgu.o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04.8l5jcmjrty1l8geid53ytmrq0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n0.222   collect2         875258 875257   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSOrLu1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.223   ld.lld           875262 875258   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSOrLu1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04 ...\n0.224   rust-lld         875262 875258   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSOrLu1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.253   rustc            875304 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n0.259   build-script-bu  875306 875178   0 /target/debug/build/malachite-nz-0a453eba9576b92e/build-script-build\n0.263   rustc            875314 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itertools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.11.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"use_alloc\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"use_alloc\", \"use_std\")) ...\n0.273   build-script-bu  875322 875178   0 /target/debug/build/libm-910d88a93f185b04/build-script-build\n0.276   rustc            875325 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libm --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libm-0.2.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"force-soft-floats\", \"unstable\")) -C metadata=3a9ad9f01559f546 ...\n0.336   rustc            875335 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.8.11/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"getrandom\", \"nightly-arm-aes\", \"no-rng\",  -C metadata=096f1abcdbdab4f7 ...\n0.375   cc               875345 875335   0 /tmp/native-trace-875157-1783997572290/shims/cc -m64 /target/debug/build/ahash-0cff4c0ebf5b28c1/rustcpjpgRl/symbols.o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1.build_script_build.a1f81c1da7fc0dba-cgu.0.rcgu.o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1.e0jr0p837vufj6ixr4fmad7c1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.376   cc               875346 875345   0 /usr/bin/cc -m64 /target/debug/build/ahash-0cff4c0ebf5b28c1/rustcpjpgRl/symbols.o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1.build_script_build.a1f81c1da7fc0dba-cgu.0.rcgu.o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1.e0jr0p837vufj6ixr4fmad7c1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.378   collect2         875347 875346   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp6mhVM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.380   ld.lld           875348 875347   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp6mhVM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1 ...\n0.381   rust-lld         875348 875347   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp6mhVM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.426   build-script-bu  875366 875178   0 /target/debug/build/ahash-0cff4c0ebf5b28c1/build-script-build\n0.427   rustc            875367 875366   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n0.439   rustc            875370 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ahash --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"getrandom\", \"nightly-arm-aes\", \"no-rng\",  -C metadata=abf4e3363be259a1 ...\n0.512   rustc            875381 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.14.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"inline-more\" --check-cfg cfg(docsrs,test) ...\n0.891   rustc            875417 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name malachite_base --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/malachite-base-0.4.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bin_build\", \"clap\", \"getrandom\", \"gnuplot\", \"rand\", \"rand_chacha\", \"random\", \"sha3\", \"test_build\", \"time\",  -C metadata=a7e0312decc7bd16 ...\n0.923   rustc            875423 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=2c38527a274a239e ...\n0.960   cc               875437 875423   0 /tmp/native-trace-875140-1783997572218/shims/cc -m64 /target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n0.960   cc               875438 875437   0 /usr/bin/cc -m64 /target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n0.963   collect2         875439 875438   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjFDd9J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.964   ld.lld           875440 875439   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjFDd9J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058 ...\n0.965   rust-lld         875440 875439   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjFDd9J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.021   build-script-bu  875458 875177   0 /target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build\n1.023   aarch64-linux-g  875459 875458   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/9836205225435430491detect_compiler_family.c\n1.024   cc1              875460 875459   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/9836205225435430491detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n1.027   aarch64-linux-g  875461 875458   0 /usr/bin/aarch64-linux-gnu-gcc -?\n1.029   aarch64-linux-g  875462 875458   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o -c src/hide.c\n1.031   cc1              875463 875462   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu src/hide.c -quiet -dumpbase hide.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...\n1.039   as               875464 875462   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o /tmp/ccyyXD0y.s\n1.047   aarch64-linux-g  875465 875458   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o\n1.049   aarch64-linux-g  875466 875458   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a\n1.054   rustc            875468 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clear_on_drop --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=e4b1ea9974a8bd2b ...\n3.279   rustc            875480 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name malachite_nz --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"32_bit_limbs\", \"bin_build\", \"doc-images\", \"embed-doc-image\", \"enable_pyo3\", \"enable_serde\", \"float_helpers\" -C metadata=70747f4aa1dcfe90 ...\n5.818   runc             875500 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process3001826282 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n5.822   exe              875508 875500   0 /proc/self/exe init\n5.840   curl             875510 875500   0 /usr/bin/curl -f http://localhost:9091/healthz\n6.701   rustc            875776 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name malachite_nz_main --edition=2021 src/bin.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"32_bit_limbs\", \"bin_build\", \"doc-images\", \"embed-doc-image\", \"enable_pyo3\", \"enable_serde\", \"float_helpers\" -C metadata=f48fb8a5f7723374 ...\n6.730   powerpc64le-lin  875787 875776   0 /usr/bin/powerpc64le-linux-gnu-gcc -m64 /target/powerpc64le-unknown-linux-gnu/debug/deps/rustcgjFmLS/symbols.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.3ey8zpb5abetuideiny3hja0i.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.79zexu2aon0cxg3vwbga70sfp.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.8q5kyec1tjy20v4lpcftqq67e.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.90ab3ewap2nh6pxuxbb6yq69m.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.agrcwdtiqzn63nd4l7g63rsn9.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.b3e911h6c4vvl5c3l7djmdiqz.1q0o912.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libstd-2bd27d6e1ee2a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libpanic_unwind-1229 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libobject-b154051326 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libmemchr-66b2d23f17 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libaddr2line-ce8bc2a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libgimli-86f7a2944bc /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libcfg_if-bf61722313 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/librustc_demangle-26 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libstd_detect-d5bc4f ...\n6.732   collect2         875788 875787   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjt1lw7.res --sysroot=/ --build-id --eh-frame-hdr -m elf64lppc --hash-style=gnu --as-needed -dynamic-linker /lib64/ld64.so.2 -pie -z now -z relro -o ...\n6.733   ld               875789 875788   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjt1lw7.res --sysroot=/ --build-id --eh-frame-hdr -m elf64lppc --hash-style=gnu --as-needed -dynamic-linker /lib64/ld64.so.2 -pie -z now -z relro -o ...\n7.888   git              875790 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n8.865   sh               875791 2147557   0 /bin/sh -c which ps\n8.866   which            875791 2147557   0 /usr/bin/which ps\n8.868   sh               875792 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n8.869   ps               875792 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n8.891   sh               875793 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n8.892   cpuUsage.sh      875793 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n8.893   sed              875794 875793   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n8.895   cat              875795 875793   0 /usr/bin/cat /proc/2240539/stat\n8.897   cat              875796 875793   0 /usr/bin/cat /proc/4193716/stat\n8.898   sleep            875797 875793   0 /usr/bin/sleep 1\n9.900   sed              875800 875793   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n9.903   cat              875801 875793   0 /usr/bin/cat /proc/2240539/stat\n9.906   cat              875803 875793   0 /usr/bin/cat /proc/4193716/stat\n13.866  sh               875805 2147557   0 /bin/sh -c which ps\n13.867  which            875805 2147557   0 /usr/bin/which ps\n13.869  sh               875806 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.870  ps               875806 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.899  sh               875807 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n13.901  cpuUsage.sh      875807 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n13.902  sed              875808 875807   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.905  cat              875809 875807   0 /usr/bin/cat /proc/2240539/stat\n13.907  cat              875810 875807   0 /usr/bin/cat /proc/4193716/stat\n13.908  sleep            875811 875807   0 /usr/bin/sleep 1\n14.130  16               875812 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n14.151  frpc             875812 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n14.651  runc             875819 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process950899817 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n14.657  exe              875826 875819   0 /proc/self/exe init\n14.685  curl             875829 875819   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n14.911  sed              875835 875807   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.914  cat              875836 875807   0 /usr/bin/cat /proc/2240539/stat\n14.917  cat              875838 875807   0 /usr/bin/cat /proc/4193716/stat\n16.888  cross            875840 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n16.889  rustc            875843 875840   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.896  rustc            875843 875840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.911  rustc            875855 875840   0 /home/xmoe/.cargo/bin/rustc -vV\n16.917  rustc            875855 875840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.928  cargo            875865 875840   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.935  cargo            875865 875840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.948  rustc            875874 875865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.960  rustc            875876 875865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.973  rustc            875880 875865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.270  rustc            875885 875865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.434  rustc            875887 875840   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.441  rustc            875887 875840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.456  docker           875899 875840   0 /usr/bin/docker --help\n17.471  docker           875909 875840   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.485  runc             875920 1599     0 /usr/bin/runc --version\n17.488  docker-init      875926 1599     0 /usr/bin/docker-init --version\n17.489  docker           875927 875840   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.503  runc             875938 1599     0 /usr/bin/runc --version\n17.507  docker-init      875944 1599     0 /usr/bin/docker-init --version\n17.533  rustup           875947 875840   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.540  rustup           875956 875840   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.570  rustup           875965 875840   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.599  uname            875974 875840   0 /usr/bin/uname -r\n17.619  docker           875975 875840   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.670  systemd-sysctl   875992 875990   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd7ce0d8 --prefix=/net/ipv4/neigh/vethd7ce0d8 --prefix=/net/ipv6/conf/vethd7ce0d8 --prefix=/net/ipv6/neigh/vethd7ce0d8\n17.672  systemd-sysctl   875993 875991   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9242e3d --prefix=/net/ipv4/neigh/veth9242e3d --prefix=/net/ipv6/conf/veth9242e3d --prefix=/net/ipv6/neigh/veth9242e3d\n17.682  containerd-shim  876010 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 start\n17.685  containerd-shim  876026 876010   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 -address /var/run/docker/containerd/containerd.sock\n17.690  runc             876042 876026   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9\n17.696  exe              876049 876042   0 /proc/self/exe init\n17.734  exe              876059 876042   0 /proc/1599/exe -exec-root=/var/run/docker 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 d7da31e8f8e1\n17.758  exe              876067 1599     0 /proc/self/exe /var/run/docker/netns/c7922c379b1e all false\n17.817  runc             876086 876026   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --log-format json --systemd-cgroup start 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9\n17.823  sh               876053 876026   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.824  cargo            876092 876053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.839  cargo-native-tr  876092 876053   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.842  cargo            876093 876092   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.857  rustc            876094 876093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.868  rustc            876096 876093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.946  execsnoop        876100 876092   0 /usr/local/bin/execsnoop -t\n17.947  python3          876100 876092   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 875458,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
  "pid": 875458,
  "ppid": 875177,
  "root_cargo_pid": 875177,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out"
}
```

#### Record 19

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/9836205225435430491detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 875458,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 875459,
  "ppid": 875458,
  "root_cargo_pid": 875177,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/9836205225435430491detect_compiler_family.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 875458,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 875460,
  "ppid": 875459,
  "root_cargo_pid": 875177,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 21

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 875458,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 875461,
  "ppid": 875458,
  "root_cargo_pid": 875177,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 22

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 875458,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 875462,
  "ppid": 875458,
  "root_cargo_pid": 875177,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 23

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "src/hide.c",
    "-quiet",
    "-dumpbase",
    "hide.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 875458,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 875463,
  "ppid": 875462,
  "root_cargo_pid": 875177,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 24

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
    "/tmp/ccyyXD0y.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 875458,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 875464,
  "ppid": 875462,
  "root_cargo_pid": 875177,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 25

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 875458,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 875465,
  "ppid": 875458,
  "root_cargo_pid": 875177,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 26

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "sD",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 875458,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 875466,
  "ppid": 875458,
  "root_cargo_pid": 875177,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 27

```json
{
  "crate": "clear_on_drop",
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "event_id": "bsrun:6d0e13ed906e2dd8:0c2e38447dfb082e:022ca268ecfe4b96",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
  "success": true,
  "target": null,
  "version": "0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 28

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "src/hide.c",
    "-quiet",
    "-dumpbase",
    "hide.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "..."
  ],
  "src": "src/hide.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 875463,
  "ppid": 875462,
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 875177,
  "build_script_root_pid": 875458,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 29

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 875465,
  "ppid": 875458,
  "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 875177,
  "build_script_root_pid": 875458,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:53:17.458127+00:00",
  "crate": "clear_on_drop",
  "version": "0.2.5",
  "architecture": "aarch64",
  "duration_seconds": 29.980806129984558,
  "trace_record_count": 27,
  "trace_owner_summary": {
    "owner_package_count": 72,
    "owner_packages": [
      {
        "crate": "wasm-bindgen-macro-support",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.126",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126/Cargo.toml"
      },
      {
        "crate": "winapi-x86_64-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "winapi-i686-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-shared",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.126",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.126",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126/Cargo.toml"
      },
      {
        "crate": "pin-project-lite",
        "version": "0.2.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml"
      },
      {
        "crate": "crossbeam-epoch",
        "version": "0.9.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.20",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/Cargo.toml"
      },
      {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml"
      },
      {
        "crate": "plotters-backend",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7/Cargo.toml"
      },
      {
        "crate": "crossbeam-deque",
        "version": "0.8.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/Cargo.toml"
      },
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml"
      },
      {
        "crate": "criterion-plot",
        "version": "0.4.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.4.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml"
      },
      {
        "crate": "unicode-width",
        "version": "0.1.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.126",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126/Cargo.toml"
      },
      {
        "crate": "futures-core",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml"
      },
      {
        "crate": "futures-task",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.32",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32/Cargo.toml"
      },
      {
        "crate": "futures-util",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.32",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml"
      },
      {
        "crate": "plotters-svg",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7/Cargo.toml"
      },
      {
        "crate": "rustversion",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23/Cargo.toml"
      },
      {
        "crate": "serde_core",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.150",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml"
      },
      {
        "crate": "tinytemplate",
        "version": "1.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml"
      },
      {
        "crate": "windows-link",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.61.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml"
      },
      {
        "crate": "hermit-abi",
        "version": "0.1.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19/Cargo.toml"
      },
      {
        "crate": "lazy_static",
        "version": "1.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml"
      },
      {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/Cargo.toml"
      },
      {
        "crate": "rayon-core",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0/Cargo.toml"
      },
      {
        "crate": "serde_cbor",
        "version": "0.11.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_cbor@0.11.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2/Cargo.toml"
      },
      {
        "crate": "itertools",
        "version": "0.10.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.21.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml"
      },
      {
        "crate": "criterion",
        "version": "0.3.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.3.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6/Cargo.toml"
      },
      {
        "crate": "csv-core",
        "version": "0.1.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv-core@0.1.13",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13/Cargo.toml"
      },
      {
        "crate": "oorandom",
        "version": "11.1.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5/Cargo.toml"
      },
      {
        "crate": "same-file",
        "version": "1.0.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml"
      },
      {
        "crate": "textwrap",
        "version": "0.11.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.11.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0/Cargo.toml"
      },
      {
        "crate": "web-sys",
        "version": "0.3.103",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.103",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "1.3.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/Cargo.toml"
      },
      {
        "crate": "bumpalo",
        "version": "3.20.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.20.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3/Cargo.toml"
      },
      {
        "crate": "js-sys",
        "version": "0.3.103",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.103",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103/Cargo.toml"
      },
      {
        "crate": "plotters",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "either",
        "version": "1.16.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml"
      },
      {
        "crate": "walkdir",
        "version": "2.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml"
      },
      {
        "crate": "rayon",
        "version": "1.12.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.12.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "atty",
        "version": "0.2.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14/Cargo.toml"
      },
      {
        "crate": "clap",
        "version": "2.34.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@2.34.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml"
      },
      {
        "crate": "slab",
        "version": "0.4.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml"
      },
      {
        "crate": "zmij",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml"
      },
      {
        "crate": "cast",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml"
      },
      {
        "crate": "half",
        "version": "1.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml"
      },
      {
        "crate": "csv",
        "version": "1.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv@1.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0/Cargo.toml"
      },
      {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "manifest_path": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5/Cargo.toml"
      }
    ],
    "attributed_event_count": 16,
    "unattributed_event_count": 11,
    "owners": [
      {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "event_count": 16,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 10,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "workspace_root": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
          "name": "aho-corasick",
          "version": "1.1.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
          "name": "atty",
          "version": "0.2.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
          "name": "autocfg",
          "version": "1.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
          "name": "bitflags",
          "version": "1.3.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.20.3",
          "name": "bumpalo",
          "version": "3.20.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
          "name": "cast",
          "version": "0.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
          "name": "cc",
          "version": "1.2.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
          "name": "cfg-if",
          "version": "1.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@2.34.0",
          "name": "clap",
          "version": "2.34.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
          "name": "clear_on_drop",
          "version": "0.2.5",
          "manifest_path": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.3.6",
          "name": "criterion",
          "version": "0.3.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.4.5",
          "name": "criterion-plot",
          "version": "0.4.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.7",
          "name": "crossbeam-deque",
          "version": "0.8.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.20",
          "name": "crossbeam-epoch",
          "version": "0.9.20",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
          "name": "crossbeam-utils",
          "version": "0.8.22",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv@1.4.0",
          "name": "csv",
          "version": "1.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv-core@0.1.13",
          "name": "csv-core",
          "version": "0.1.13",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
          "name": "either",
          "version": "1.16.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
          "name": "futures-core",
          "version": "0.3.32",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.32",
          "name": "futures-task",
          "version": "0.3.32",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.32",
          "name": "futures-util",
          "version": "0.3.32",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.3",
          "name": "half",
          "version": "1.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
          "name": "hermit-abi",
          "version": "0.1.19",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
          "name": "itertools",
          "version": "0.10.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
          "name": "itoa",
          "version": "1.0.18",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.103",
          "name": "js-sys",
          "version": "0.3.103",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
          "name": "lazy_static",
          "version": "1.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
          "name": "num-traits",
          "version": "0.2.19",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
          "name": "once_cell",
          "version": "1.21.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.5",
          "name": "oorandom",
          "version": "11.1.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
          "name": "pin-project-lite",
          "version": "0.2.17",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
          "name": "plotters",
          "version": "0.3.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
          "name": "plotters-backend",
          "version": "0.3.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
          "name": "plotters-svg",
          "version": "0.3.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
          "name": "proc-macro2",
          "version": "1.0.106",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
          "name": "quote",
          "version": "1.0.46",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.12.0",
          "name": "rayon",
          "version": "1.12.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.13.0",
          "name": "rayon-core",
          "version": "1.13.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
          "name": "regex",
          "version": "1.13.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
          "name": "regex-automata",
          "version": "0.4.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
          "name": "regex-syntax",
          "version": "0.8.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
          "name": "rustversion",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
          "name": "ryu",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
          "name": "same-file",
          "version": "1.0.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
          "name": "serde",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_cbor@0.11.2",
          "name": "serde_cbor",
          "version": "0.11.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
          "name": "serde_core",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
          "name": "serde_derive",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
          "name": "serde_json",
          "version": "1.0.150",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.12",
          "name": "slab",
          "version": "0.4.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
          "name": "syn",
          "version": "2.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.11.0",
          "name": "textwrap",
          "version": "0.11.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
          "name": "tinytemplate",
          "version": "1.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
          "name": "unicode-ident",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
          "name": "unicode-width",
          "version": "0.1.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
          "name": "walkdir",
          "version": "2.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.126",
          "name": "wasm-bindgen",
          "version": "0.2.126",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.126",
          "name": "wasm-bindgen-macro",
          "version": "0.2.126",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.126",
          "name": "wasm-bindgen-macro-support",
          "version": "0.2.126",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.126",
          "name": "wasm-bindgen-shared",
          "version": "0.2.126",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.103",
          "name": "web-sys",
          "version": "0.3.103",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
          "name": "winapi",
          "version": "0.3.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
          "name": "winapi-i686-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
          "name": "winapi-util",
          "version": "0.1.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
          "name": "winapi-x86_64-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
          "name": "windows-link",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
          "name": "windows-sys",
          "version": "0.61.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
          "name": "zmij",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23"
        }
      ],
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 875437,
      "ppid": 875423,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:8ed0fca1fdc3ea79:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
      "pid": 875437,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:2cc2a88d00af5e02:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
      "pid": 875437,
      "sha256": "5afbec68ed40ad6b37cc1f615597ce8acd69271550760432b8a5ef2db3a47502",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:8e3a3067584f6cdf:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
      "pid": 875437,
      "sha256": "a9ff4fab86d9f2801cd6fe51c4346bf29b18edf8b102a584cd4a658ca2b210ef",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:12b87021280df528:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
      "pid": 875437,
      "sha256": "08c899738f261cf1bdd6fd8c86f389965a07757fd3158be800830e069ed4d730",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:2ce3062fdf244e6a:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
      "pid": 875437,
      "sha256": "6f3e412dc616030560ee543d0919ff5998f318466f95b4e01afce864424d09f2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:7dc84ced023ba780:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
      "pid": 875437,
      "sha256": "a8aa8a0750dc530394cda67e856c73feaaf1f253c41eb9b788314bd361cf4715",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:382dedf4b1f2b8f2:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
      "pid": 875437,
      "sha256": "feb974ba589f85baa440a120095f3465df6703017409edbe51a6ef9e03d7db2e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:82173b664572d25c:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
      "pid": 875437,
      "sha256": "57c222de0b0240b57be8673af28c185426de21b62307a11bd21c4d15043b2c8d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:35ed01a5b7e9d141:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
      "pid": 875437,
      "sha256": "155c0dd3a0795355188fb8caaf765d86c5f5b151d0dfa60a1e96392071a0c4e4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:b638a78f527ba3c5:cd378ad8752ed5a7:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
      "pid": 875437,
      "sha256": "00bdc4bedc6940977b7809080c8598657c074c7db36a0b7c642000ffa0d84b61",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib"
      ],
      "libs": [
        "gcc_s",
        "util",
        "rt",
        "pthread",
        "m",
        "dl",
        "c"
      ],
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "context_path": "/tmp/native-trace-875140-1783997572218/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-875140-1783997572218/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 875437,
      "ppid": 875423,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058",
        "/target/debug/deps",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu"
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.09.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.10.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.11.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.12.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.13.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.14.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.15.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib(shlex-f2fa52250b1d670f.shlex.352c8e657ac65ae8-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib(std-d1237ef7159db0a2.std.e28293b1aa0f68bd-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib(panic_unwind-4be5972b22d3a6da.panic_unwind.d9b2f7d287d2f9d2-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib(object-2a81194c9d07bbf6.object.4f4cc23e276cbdd5-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib(memchr-ea71fa85f6699d6b.memchr.9642f0ce76a98c65-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib(addr2line-a79a8816d9fd6004.addr2line.39b02397e671b2d1-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib(gimli-46dc78dc6a8cb06a.gimli.9d272e8433f81454-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib(rustc_demangle-146c3f1190dee2e2.rustc_demangle.c5a78273c295e539-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib(hashbrown-1448c95121de53aa.hashbrown.c0386ddbfadcbbc1-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib(miniz_oxide-5ad929a15a8e6727.miniz_oxide.b662226d77c6ee8e-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib(adler2-1f570ee5c6635aae.adler2.1d6706876a417dbf-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib(alloc-6e6df4ffe0af4d15.alloc.fdfd2bd8633a6659-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib(core-120cbae4e86ec454.core.c1f1a4ba060b9bfa-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.132.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.187.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.201.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
          "kind": "object",
          "path": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib(compiler_builtins-27cfc16bdf3bb694.compiler_builtins.4e30281dd23088d2-cgu.261.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libm.so.6",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libmvec.so.1",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libc.so.6",
          "source": "link_trace"
        },
        {
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o",
          "source": "link_trace"
        }
      ],
      "kind": "resolved_link",
      "map_path": "/tmp/native-trace-link-cc-875437-1783997574980271213.map",
      "pid": 875437,
      "ppid": 875423,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-875437-1783997574980271213.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "/usr/local/bin/execsnoop",
        "-t"
      ],
      "event": "process_tracer_diagnostic",
      "exit_status": null,
      "parse_error_count": 0,
      "parsed_event_count": 0,
      "phase": "start",
      "platform": "linux_ebpf",
      "raw_event_count": 0,
      "spawn_error": null,
      "stderr": "",
      "stdout": ""
    },
    {
      "argv": [
        "/usr/local/bin/execsnoop",
        "-t"
      ],
      "event": "process_tracer_diagnostic",
      "exit_status": null,
      "parse_error_count": 1,
      "parsed_event_count": 138,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 139,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "0.111   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            875177 875140   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n0.122   cargo            875178 875157   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n0.123   rustc            875179 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.133   rustc            875183 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.166   rustc            875190 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n0.166   rustc            875191 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n0.171   rustc            875197 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name version_check --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de4e2c29a5a03308 ...\n0.171   rustc            875200 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name once_cell --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"race\" --check-cfg cfg(docsrs,test) ...\n0.171   rustc            875199 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\")) -C metadata=44346b50c4e9393e ...\n0.171   rustc            875203 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerocopy --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.7.35/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"simd\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"__internal_use_only_features_that_work_on_stable\", \"alloc\", \"byteorder\", \"default\", \"derive\", \"simd\", \"simd ...\n0.172   rustc            875205 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libm-0.2.11/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"force-soft-floats\", \"unstable\")) -C metadata=d3c80d784b571fe6 ...\n0.173   rustc            875206 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"use_std\")) -C metadata=b95e3260cc387c27 ...\n0.173   rustc            875207 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ryu --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"no-panic\", \"small\")) -C metadata=d897da932e6d081b ...\n0.174   rustc            875208 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"32_bit_limbs\", \"bin_build\", \"doc-images\", \"embed-doc-image\", \"enable_pyo3\", \"enable_serde\", \"float_helpers\" -C metadata=901ba5ff8206392c ...\n0.207   cc               875251 875208   0 /tmp/native-trace-875157-1783997572290/shims/cc -m64 /target/debug/build/malachite-nz-0a453eba9576b92e/rustcjPnlvD/symbols.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.4gfy13mc7bx9q35wq4kiuxeak.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.5orosh8uci9mizcbhbzr6d9rc.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.89qs6bwmpw7u1ruzktae2wr54.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.8d3w2xcpnkbowv8go275tdgn5.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.b01o0sy7lxdgp913vrb3pmu62.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.7m5fhhic994jdurk7ucpabj28.0b02m5y.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n0.208   cc               875253 875251   0 /usr/bin/cc -m64 /target/debug/build/malachite-nz-0a453eba9576b92e/rustcjPnlvD/symbols.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.4gfy13mc7bx9q35wq4kiuxeak.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.5orosh8uci9mizcbhbzr6d9rc.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.89qs6bwmpw7u1ruzktae2wr54.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.8d3w2xcpnkbowv8go275tdgn5.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.b01o0sy7lxdgp913vrb3pmu62.0b02m5y.rcgu.o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e.7m5fhhic994jdurk7ucpabj28.0b02m5y.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 ...\n0.211   collect2         875254 875253   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccVPpaJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.213   ld.lld           875255 875254   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccVPpaJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/malachite-nz-0a453eba9576b92e/build_script_build-0a453eba9576b92e ...\n0.214   rust-lld         875255 875254   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccVPpaJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.218   cc               875256 875205   0 /tmp/native-trace-875157-1783997572290/shims/cc -m64 /target/debug/build/libm-910d88a93f185b04/rustcpsO7u9/symbols.o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04.build_script_build.f6b38c9b0eadb864-cgu.0.rcgu.o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04.8l5jcmjrty1l8geid53ytmrq0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n0.219   cc               875257 875256   0 /usr/bin/cc -m64 /target/debug/build/libm-910d88a93f185b04/rustcpsO7u9/symbols.o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04.build_script_build.f6b38c9b0eadb864-cgu.0.rcgu.o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04.8l5jcmjrty1l8geid53ytmrq0.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n0.222   collect2         875258 875257   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSOrLu1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.223   ld.lld           875262 875258   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSOrLu1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libm-910d88a93f185b04/build_script_build-910d88a93f185b04 ...\n0.224   rust-lld         875262 875258   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSOrLu1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.253   rustc            875304 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n0.259   build-script-bu  875306 875178   0 /target/debug/build/malachite-nz-0a453eba9576b92e/build-script-build\n0.263   rustc            875314 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itertools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.11.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"use_alloc\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"use_alloc\", \"use_std\")) ...\n0.273   build-script-bu  875322 875178   0 /target/debug/build/libm-910d88a93f185b04/build-script-build\n0.276   rustc            875325 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libm --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libm-0.2.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"force-soft-floats\", \"unstable\")) -C metadata=3a9ad9f01559f546 ...\n0.336   rustc            875335 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.8.11/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"getrandom\", \"nightly-arm-aes\", \"no-rng\",  -C metadata=096f1abcdbdab4f7 ...\n0.375   cc               875345 875335   0 /tmp/native-trace-875157-1783997572290/shims/cc -m64 /target/debug/build/ahash-0cff4c0ebf5b28c1/rustcpjpgRl/symbols.o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1.build_script_build.a1f81c1da7fc0dba-cgu.0.rcgu.o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1.e0jr0p837vufj6ixr4fmad7c1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.376   cc               875346 875345   0 /usr/bin/cc -m64 /target/debug/build/ahash-0cff4c0ebf5b28c1/rustcpjpgRl/symbols.o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1.build_script_build.a1f81c1da7fc0dba-cgu.0.rcgu.o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1.e0jr0p837vufj6ixr4fmad7c1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.378   collect2         875347 875346   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp6mhVM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.380   ld.lld           875348 875347   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp6mhVM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/ahash-0cff4c0ebf5b28c1/build_script_build-0cff4c0ebf5b28c1 ...\n0.381   rust-lld         875348 875347   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp6mhVM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.426   build-script-bu  875366 875178   0 /target/debug/build/ahash-0cff4c0ebf5b28c1/build-script-build\n0.427   rustc            875367 875366   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n0.439   rustc            875370 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ahash --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"getrandom\", \"nightly-arm-aes\", \"no-rng\",  -C metadata=abf4e3363be259a1 ...\n0.512   rustc            875381 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.14.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"inline-more\" --check-cfg cfg(docsrs,test) ...\n0.891   rustc            875417 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name malachite_base --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/malachite-base-0.4.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bin_build\", \"clap\", \"getrandom\", \"gnuplot\", \"rand\", \"rand_chacha\", \"random\", \"sha3\", \"test_build\", \"time\",  -C metadata=a7e0312decc7bd16 ...\n0.923   rustc            875423 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=2c38527a274a239e ...\n0.960   cc               875437 875423   0 /tmp/native-trace-875140-1783997572218/shims/cc -m64 /target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n0.960   cc               875438 875437   0 /usr/bin/cc -m64 /target/debug/build/clear_on_drop-7166f128fe0bc058/rustcdTqAmW/symbols.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1uz77bb.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1uz77bb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n0.963   collect2         875439 875438   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjFDd9J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.964   ld.lld           875440 875439   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjFDd9J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058 ...\n0.965   rust-lld         875440 875439   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjFDd9J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.021   build-script-bu  875458 875177   0 /target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build\n1.023   aarch64-linux-g  875459 875458   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/9836205225435430491detect_compiler_family.c\n1.024   cc1              875460 875459   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/9836205225435430491detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n1.027   aarch64-linux-g  875461 875458   0 /usr/bin/aarch64-linux-gnu-gcc -?\n1.029   aarch64-linux-g  875462 875458   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o -c src/hide.c\n1.031   cc1              875463 875462   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu src/hide.c -quiet -dumpbase hide.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...\n1.039   as               875464 875462   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o /tmp/ccyyXD0y.s\n1.047   aarch64-linux-g  875465 875458   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o\n1.049   aarch64-linux-g  875466 875458   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a\n1.054   rustc            875468 875177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clear_on_drop --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=e4b1ea9974a8bd2b ...\n3.279   rustc            875480 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name malachite_nz --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"32_bit_limbs\", \"bin_build\", \"doc-images\", \"embed-doc-image\", \"enable_pyo3\", \"enable_serde\", \"float_helpers\" -C metadata=70747f4aa1dcfe90 ...\n5.818   runc             875500 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process3001826282 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n5.822   exe              875508 875500   0 /proc/self/exe init\n5.840   curl             875510 875500   0 /usr/bin/curl -f http://localhost:9091/healthz\n6.701   rustc            875776 875178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name malachite_nz_main --edition=2021 src/bin.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"32_bit_limbs\", \"bin_build\", \"doc-images\", \"embed-doc-image\", \"enable_pyo3\", \"enable_serde\", \"float_helpers\" -C metadata=f48fb8a5f7723374 ...\n6.730   powerpc64le-lin  875787 875776   0 /usr/bin/powerpc64le-linux-gnu-gcc -m64 /target/powerpc64le-unknown-linux-gnu/debug/deps/rustcgjFmLS/symbols.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.3ey8zpb5abetuideiny3hja0i.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.79zexu2aon0cxg3vwbga70sfp.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.8q5kyec1tjy20v4lpcftqq67e.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.90ab3ewap2nh6pxuxbb6yq69m.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.agrcwdtiqzn63nd4l7g63rsn9.1q0o912.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/malachite_nz_main-3c9259b554ddc95a.b3e911h6c4vvl5c3l7djmdiqz.1q0o912.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libstd-2bd27d6e1ee2a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libpanic_unwind-1229 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libobject-b154051326 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libmemchr-66b2d23f17 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libaddr2line-ce8bc2a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libgimli-86f7a2944bc /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libcfg_if-bf61722313 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/librustc_demangle-26 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/powerpc64le-unknown-linux-gnu/lib/libstd_detect-d5bc4f ...\n6.732   collect2         875788 875787   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjt1lw7.res --sysroot=/ --build-id --eh-frame-hdr -m elf64lppc --hash-style=gnu --as-needed -dynamic-linker /lib64/ld64.so.2 -pie -z now -z relro -o ...\n6.733   ld               875789 875788   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjt1lw7.res --sysroot=/ --build-id --eh-frame-hdr -m elf64lppc --hash-style=gnu --as-needed -dynamic-linker /lib64/ld64.so.2 -pie -z now -z relro -o ...\n7.888   git              875790 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n8.865   sh               875791 2147557   0 /bin/sh -c which ps\n8.866   which            875791 2147557   0 /usr/bin/which ps\n8.868   sh               875792 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n8.869   ps               875792 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n8.891   sh               875793 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n8.892   cpuUsage.sh      875793 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n8.893   sed              875794 875793   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n8.895   cat              875795 875793   0 /usr/bin/cat /proc/2240539/stat\n8.897   cat              875796 875793   0 /usr/bin/cat /proc/4193716/stat\n8.898   sleep            875797 875793   0 /usr/bin/sleep 1\n9.900   sed              875800 875793   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n9.903   cat              875801 875793   0 /usr/bin/cat /proc/2240539/stat\n9.906   cat              875803 875793   0 /usr/bin/cat /proc/4193716/stat\n13.866  sh               875805 2147557   0 /bin/sh -c which ps\n13.867  which            875805 2147557   0 /usr/bin/which ps\n13.869  sh               875806 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.870  ps               875806 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.899  sh               875807 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n13.901  cpuUsage.sh      875807 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n13.902  sed              875808 875807   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.905  cat              875809 875807   0 /usr/bin/cat /proc/2240539/stat\n13.907  cat              875810 875807   0 /usr/bin/cat /proc/4193716/stat\n13.908  sleep            875811 875807   0 /usr/bin/sleep 1\n14.130  16               875812 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n14.151  frpc             875812 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n14.651  runc             875819 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process950899817 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n14.657  exe              875826 875819   0 /proc/self/exe init\n14.685  curl             875829 875819   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n14.911  sed              875835 875807   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.914  cat              875836 875807   0 /usr/bin/cat /proc/2240539/stat\n14.917  cat              875838 875807   0 /usr/bin/cat /proc/4193716/stat\n16.888  cross            875840 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n16.889  rustc            875843 875840   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.896  rustc            875843 875840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.911  rustc            875855 875840   0 /home/xmoe/.cargo/bin/rustc -vV\n16.917  rustc            875855 875840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.928  cargo            875865 875840   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.935  cargo            875865 875840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.948  rustc            875874 875865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.960  rustc            875876 875865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.973  rustc            875880 875865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.270  rustc            875885 875865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.434  rustc            875887 875840   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.441  rustc            875887 875840   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.456  docker           875899 875840   0 /usr/bin/docker --help\n17.471  docker           875909 875840   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.485  runc             875920 1599     0 /usr/bin/runc --version\n17.488  docker-init      875926 1599     0 /usr/bin/docker-init --version\n17.489  docker           875927 875840   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.503  runc             875938 1599     0 /usr/bin/runc --version\n17.507  docker-init      875944 1599     0 /usr/bin/docker-init --version\n17.533  rustup           875947 875840   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.540  rustup           875956 875840   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.570  rustup           875965 875840   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.599  uname            875974 875840   0 /usr/bin/uname -r\n17.619  docker           875975 875840   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.670  systemd-sysctl   875992 875990   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd7ce0d8 --prefix=/net/ipv4/neigh/vethd7ce0d8 --prefix=/net/ipv6/conf/vethd7ce0d8 --prefix=/net/ipv6/neigh/vethd7ce0d8\n17.672  systemd-sysctl   875993 875991   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9242e3d --prefix=/net/ipv4/neigh/veth9242e3d --prefix=/net/ipv6/conf/veth9242e3d --prefix=/net/ipv6/neigh/veth9242e3d\n17.682  containerd-shim  876010 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 start\n17.685  containerd-shim  876026 876010   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 -address /var/run/docker/containerd/containerd.sock\n17.690  runc             876042 876026   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9\n17.696  exe              876049 876042   0 /proc/self/exe init\n17.734  exe              876059 876042   0 /proc/1599/exe -exec-root=/var/run/docker 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 d7da31e8f8e1\n17.758  exe              876067 1599     0 /proc/self/exe /var/run/docker/netns/c7922c379b1e all false\n17.817  runc             876086 876026   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --log-format json --systemd-cgroup start 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9\n17.823  sh               876053 876026   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.824  cargo            876092 876053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.839  cargo-native-tr  876092 876053   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.842  cargo            876093 876092   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.857  rustc            876094 876093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.868  rustc            876096 876093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.946  execsnoop        876100 876092   0 /usr/local/bin/execsnoop -t\n17.947  python3          876100 876092   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n"
    },
    {
      "argv": [
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 875458,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
      "pid": 875458,
      "ppid": 875177,
      "root_cargo_pid": 875177,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/9836205225435430491detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 875458,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 875459,
      "ppid": 875458,
      "root_cargo_pid": 875177,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/9836205225435430491detect_compiler_family.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 875458,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 875460,
      "ppid": 875459,
      "root_cargo_pid": 875177,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 875458,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 875461,
      "ppid": 875458,
      "root_cargo_pid": 875177,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-Wall",
        "-Wextra",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 875458,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 875462,
      "ppid": 875458,
      "root_cargo_pid": 875177,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "src/hide.c",
        "-quiet",
        "-dumpbase",
        "hide.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 875458,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 875463,
      "ppid": 875462,
      "root_cargo_pid": 875177,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o",
        "/tmp/ccyyXD0y.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 875458,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 875464,
      "ppid": 875462,
      "root_cargo_pid": 875177,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cqD",
        "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/ea708c7824d36062-hide.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 875458,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 875465,
      "ppid": 875458,
      "root_cargo_pid": 875177,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "sD",
        "/target/aarch64-unknown-linux-gnu/debug/build/clear_on_drop-b8e9a502004fa27c/out/libclear_on_drop.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 875458,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 875466,
      "ppid": 875458,
      "root_cargo_pid": 875177,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "clear_on_drop",
      "cwd": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "event_id": "bsrun:6d0e13ed906e2dd8:0c2e38447dfb082e:022ca268ecfe4b96",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
      "out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
      "success": true,
      "target": null,
      "version": "0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-aarch64-061i23vs/src/clear_on_drop-0.2.5",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
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
