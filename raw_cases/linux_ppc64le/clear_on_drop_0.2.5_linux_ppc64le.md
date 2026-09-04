# `clear_on_drop` `0.2.5`

Platform: Linux ppc64le

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a`

Owner: `clear_on_drop` `0.2.5`

### Source files

* `/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5/src/hide.c`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/hide.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "hide.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "src/hide.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 876650,
  "ppid": 876649,
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 876563,
  "build_script_root_pid": 876645,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 876652,
  "ppid": 876645,
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 876563,
  "build_script_root_pid": 876645,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "workspace_root": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
      "name": "clear_on_drop",
      "version": "0.2.5",
      "manifest_path": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 876624,
  "ppid": 876610,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:92d4b66b19e40f26:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
  "pid": 876624,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:263fff3c672d10c7:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
  "pid": 876624,
  "sha256": "90f6e0e4a8245af9622a558e455be8ee283a70911e1d4f26086741b20b373804",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:e25c1633e4e5c3fd:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
  "pid": 876624,
  "sha256": "bbbcb614b6abb1a09a32cf8fe2f7215cc8bf042426cbda2cbfca2877cd393d82",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:dd9e20295f81f863:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
  "pid": 876624,
  "sha256": "95d85cfb48222aa81a0ed0f81a9a39aa6ea8bc194cc5927e7c63caccd7c161a9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:eb5a0eb52ff8e3e9:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
  "pid": 876624,
  "sha256": "78f680bbbb58fbce98c8515153a3c26922439392d354916415a3cf891206f597",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:dc2e0c44e885bb25:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
  "pid": 876624,
  "sha256": "db16e67556993886981ac462ba6744b7a08016ba64d1c711c4c768ebe9ef6480",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:2e12e12d59121b06:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
  "pid": 876624,
  "sha256": "24a050c4cb686a13cdc4a4b85d065a57cd2c0213066028b99a72d788cc25d77d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:c2bd8b4ed8d7a44f:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
  "pid": 876624,
  "sha256": "d41207e12829aeb1c0eab21f3e9de1253b5901e24c9f75fbeed44141297d3fd7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:8f3eaf0d523143de:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
  "pid": 876624,
  "sha256": "e1e011a6ee5190c31346e92e1c183af892b95f9bafdbe75dfaa4c172ca15768c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:1dc61a243c4c1b83:b062681c751f8f39:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
  "pid": 876624,
  "sha256": "00bdc4bedc6940977b7809080c8598657c074c7db36a0b7c642000ffa0d84b61",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "context_path": "/tmp/native-trace-876546-1783997602154/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-876546-1783997602154/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 876624,
  "ppid": 876610,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q",
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
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-876624-1783997604710613117.map",
  "pid": 876624,
  "ppid": 876610,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-876624-1783997604710613117.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
  "parsed_event_count": 180,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 181,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "-435d7708213f6542/out/ea708c7824d36062-hide.o /tmp/ccW1uU6i.s\n0.872   powerpc64le-lin  876652 876645   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o\n0.874   powerpc64le-lin  876653 876645   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a\n0.880   rustc            876655 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clear_on_drop --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=b7d7c29f6545bab9 ...\n3.014   cross            876664 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n3.015   rustc            876667 876664   0 /home/xmoe/.cargo/bin/rustc --print target-list\n3.022   rustc            876667 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n3.037   rustc            876679 876664   0 /home/xmoe/.cargo/bin/rustc -vV\n3.044   rustc            876679 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n3.055   cargo            876689 876664   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n3.061   cargo            876689 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n3.074   rustc            876698 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n3.086   rustc            876700 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n3.101   rustc            876704 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n3.197   rustc            876708 876664   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n3.204   rustc            876708 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n3.218   docker           876720 876664   0 /usr/bin/docker --help\n3.234   docker           876731 876664   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n3.248   runc             876743 1599     0 /usr/bin/runc --version\n3.252   docker-init      876749 1599     0 /usr/bin/docker-init --version\n3.253   docker           876750 876664   0 /usr/bin/docker info -f {{.SecurityOptions}}\n3.267   runc             876763 1599     0 /usr/bin/runc --version\n3.270   docker-init      876769 1599     0 /usr/bin/docker-init --version\n3.296   rustup           876770 876664   0 /home/xmoe/.cargo/bin/rustup toolchain list\n3.304   rustup           876779 876664   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n3.335   rustup           876788 876664   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n3.366   uname            876797 876664   0 /usr/bin/uname -r\n3.386   docker           876798 876664   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n3.433   systemd-sysctl   876814 876812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8ebf659 --prefix=/net/ipv4/neigh/veth8ebf659 --prefix=/net/ipv6/conf/veth8ebf659 --prefix=/net/ipv6/neigh/veth8ebf659\n3.434   systemd-sysctl   876815 876813   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth88c0a91 --prefix=/net/ipv4/neigh/veth88c0a91 --prefix=/net/ipv6/conf/veth88c0a91 --prefix=/net/ipv6/neigh/veth88c0a91\n3.446   containerd-shim  876839 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 start\n3.450   containerd-shim  876854 876839   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 -address /var/run/docker/containerd/containerd.sock\n3.455   runc             876864 876854   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340\n3.461   exe              876872 876864   0 /proc/self/exe init\n3.500   exe              876881 876864   0 /proc/1599/exe -exec-root=/var/run/docker 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 d7da31e8f8e1\n3.525   exe              876889 1599     0 /proc/self/exe /var/run/docker/netns/dc57e9676e3f all false\n3.576   runc             876908 876854   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --log-format json --systemd-cgroup start 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340\n3.582   sh               876875 876854   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n3.583   cargo            876914 876875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n3.597   cargo-native-tr  876914 876875   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n3.600   cargo            876915 876914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n3.613   rustc            876916 876915   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n3.626   rustc            876918 876915   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n3.672   execsnoop        876922 876914   0 /usr/local/bin/execsnoop -t\n3.672   python3          876922 876914   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n5.404   cargo            876925 876914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n5.417   rustc            876926 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n5.443   rustc            876936 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n5.444   rustc            876938 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de2844ba6b8ae918 ...\n5.444   rustc            876939 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n5.445   rustc            876941 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n5.445   rustc            876940 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"avoid-default-panic\", \"encoding-raw\", \"encoding-rzcobs\", \"ip_in_core\", \"unstable-test\")) -C metadata=44a85da66c008e88 ...\n5.446   rustc            876942 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/defmt-macros-1.0.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"unstable-test\")) -C metadata=c7338f2308d4bca1 ...\n5.472   cc               876967 876942   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/defmt-macros-fcfcc24ad5e74756/rustc464jBI/symbols.o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.build_script_build.ccd373c524451d1d-cgu.0. /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.70c1azqju59eihbinusj5hug8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.473   cc               876968 876967   0 /usr/bin/cc -m64 /target/debug/build/defmt-macros-fcfcc24ad5e74756/rustc464jBI/symbols.o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.build_script_build.ccd373c524451d1d-cgu.0. /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.70c1azqju59eihbinusj5hug8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.475   collect2         876971 876968   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.476   ld.lld           876973 876971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756 ...\n5.477   rust-lld         876973 876971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.515   build-script-bu  877034 876925   0 /target/debug/build/defmt-macros-fcfcc24ad5e74756/build-script-build\n5.523   cc               877037 876940   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/defmt-88870500e9779679/rustcTOqJFU/symbols.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.055zk37rzu569svhsi8q0o5qp.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.0rpv6ef39zfh377kqpdwqt6g9.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.158lqt5y2x83b9zsise8h73nq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.3y17x9xbl4j2afwwz8a9jc45o.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.40r4tyzccbeuezyaizzylk2pn.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4bhsadt7ulwe6zi6wa5f8k4aj.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4kywhqz7rbi6dpvtowz2r7nmf.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4n65qxab0563utyx0d6yhcb0d.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.5ufph9gh2gjta1sd3skwekhym.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.6151boy9kvqnlg3qn0nvmpftq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.65m8e7svy2yd8r3ggvoecu0p7.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.69h4j683oo774547xc2muhfit.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.76diyyj2mrnynm3echznpxa7u.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.79h1339cdeg95ond51d88dcrh.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.876z0191hx79yv6qhd5o1wj6b.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.8g047khgm9nav92c2w6gjimps.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.999uopozu2buzwryf507eyhfy.06021wv.rcgu.o ...\n5.524   cc               877038 877037   0 /usr/bin/cc -m64 /target/debug/build/defmt-88870500e9779679/rustcTOqJFU/symbols.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.055zk37rzu569svhsi8q0o5qp.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.0rpv6ef39zfh377kqpdwqt6g9.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.158lqt5y2x83b9zsise8h73nq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.3y17x9xbl4j2afwwz8a9jc45o.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.40r4tyzccbeuezyaizzylk2pn.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4bhsadt7ulwe6zi6wa5f8k4aj.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4kywhqz7rbi6dpvtowz2r7nmf.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4n65qxab0563utyx0d6yhcb0d.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.5ufph9gh2gjta1sd3skwekhym.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.6151boy9kvqnlg3qn0nvmpftq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.65m8e7svy2yd8r3ggvoecu0p7.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.69h4j683oo774547xc2muhfit.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.76diyyj2mrnynm3echznpxa7u.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.79h1339cdeg95ond51d88dcrh.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.876z0191hx79yv6qhd5o1wj6b.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.8g047khgm9nav92c2w6gjimps.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.999uopozu2buzwryf507eyhfy.06021wv.rcgu.o ...\n5.526   collect2         877039 877038   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.528   ld.lld           877040 877039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679 ...\n5.529   rust-lld         877040 877039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.538   cc               877041 876936   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/proc-macro2-9397a4c89a8399e7/rustc2dgGS1/symbols.o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.0.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.1.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.4il8xo66kpq7xyp9ndwunhiok.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.539   cc               877042 877041   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-9397a4c89a8399e7/rustc2dgGS1/symbols.o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.0.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.1.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.4il8xo66kpq7xyp9ndwunhiok.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.541   cc               877059 876941   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcrixLna/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.541   collect2         877060 877042   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.541   cc               877061 877059   0 /usr/bin/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcrixLna/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.542   ld.lld           877062 877060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7 ...\n5.543   rust-lld         877062 877060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.543   collect2         877063 877061   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.544   ld.lld           877064 877063   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b ...\n5.545   rust-lld         877064 877063   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.574   build-script-bu  877098 876925   0 /target/debug/build/defmt-88870500e9779679/build-script-build\n5.583   build-script-bu  877100 876925   0 /target/debug/build/thiserror-c8cdc86597298e7b/build-script-build\n5.584   build-script-bu  877102 876925   0 /target/debug/build/proc-macro2-9397a4c89a8399e7/build-script-build\n5.585   rustc            877103 877100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/thiserror-43e7d0657569a05a/out/probe build/probe.rs --target x86_64-unknown-linux-gnu\n5.586   rustc            877104 877102   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n5.594   rustc            877109 877102   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-c75d55102dcd3bb9/out/probe build/probe.rs --target x86_64-unknown-linux-gnu\n5.619   rustc            877113 877100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n5.621   rustc            877115 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n5.801   rustc            877123 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n5.895   rustc            877139 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.100/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n5.943   runc             877144 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2279327366 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n5.948   exe              877151 877144   0 /proc/self/exe init\n5.959   rustc            877160 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-attr2-2.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --check-cfg cfg(docsrs,test) --check-cfg ...\n5.964   curl             877153 877144   0 /usr/bin/curl -f http://localhost:9091/healthz\n6.067   cc               877169 877160   0 /tmp/native-trace-876914-1783997607526/shims/cc -Wl,--version-script=/target/debug/deps/rustc3FdlPW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc3FdlPW/symbols.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.1.rcgu.o /target/debug/deps/rustc3FdlPW/rmeta.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.55sq3uw3glcy6pozjsuixo9q6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-cd059401c8285246.rlib /target/debug/deps/libproc_macro2-02759104fca4896a.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n6.067   cc               877170 877169   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc3FdlPW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc3FdlPW/symbols.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.1.rcgu.o /target/debug/deps/rustc3FdlPW/rmeta.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.55sq3uw3glcy6pozjsuixo9q6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-cd059401c8285246.rlib /target/debug/deps/libproc_macro2-02759104fca4896a.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n6.070   collect2         877171 877170   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc3FdlPW/raw-dylibs ...\n6.071   ld.lld           877172 877171   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc3FdlPW/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n6.072   rust-lld         877172 877171   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n7.322   rustc            877192 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error2-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=unexpected_cfgs --allow=clippy::module_name_repetitions --check-cfg cfg(run_ui_tests) --cfg ...\n7.850   rustc            877217 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n7.940   runc             877221 876026   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --log-format json --systemd-cgroup kill --all 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 9\n7.956   runc             877228 876026   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --log-format json --systemd-cgroup delete 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9\n8.147   containerd-shim  877236 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 delete\n8.149   runc             877243 877236   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad --log-format json delete --force 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9\n8.188   sh               877253 877249   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethd7ce0d8\n8.189   ethtool          877254 877253   0 /usr/sbin/ethtool -i vethd7ce0d8\n8.189   sed              877255 877253   0 /usr/bin/sed -n s/^driver: //p\n8.196   systemd-sysctl   877258 877249   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd7ce0d8 --prefix=/net/ipv4/neigh/vethd7ce0d8 --prefix=/net/ipv6/conf/vethd7ce0d8 --prefix=/net/ipv6/neigh/vethd7ce0d8\n8.367   cc               877274 877217   0 /tmp/native-trace-876914-1783997607526/shims/cc -Wl,--version-script=/target/debug/deps/rustcXcFra1/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcXcFra1/symbols.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.14.rcgu.o ...\n8.368   cc               877275 877274   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcXcFra1/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcXcFra1/symbols.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.14.rcgu.o ...\n8.370   collect2         877276 877275   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm3f3LA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-6252ecb0467e164f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcXcFra1/raw-dylibs ...\n8.372   ld.lld           877277 877276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm3f3LA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-6252ecb0467e164f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcXcFra1/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n8.373   rust-lld         877277 877276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm3f3LA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-6252ecb0467e164f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n8.490   rustc            877295 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n8.519   rustc            877303 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name defmt_parser --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/defmt-parser-1.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"unstable\")) -C metadata=eea9feea4d5ec196 ...\n8.651   rustc            877313 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name defmt_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/defmt-macros-1.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"unstable-test\")) ...\n9.250   cc               877335 877313   0 /tmp/native-trace-876914-1783997607526/shims/cc -Wl,--version-script=/target/debug/deps/rustcjjTQfQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcjjTQfQ/symbols.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.00.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.01.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.02.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.03.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.04.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.05.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.06.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.07.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.08.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.09.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.10.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.11.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.12.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.13.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.14.rcgu.o ...\n9.251   cc               877336 877335   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcjjTQfQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcjjTQfQ/symbols.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.00.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.01.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.02.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.03.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.04.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.05.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.06.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.07.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.08.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.09.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.10.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.11.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.12.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.13.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.14.rcgu.o ...\n9.254   collect2         877337 877336   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2bW18f.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libdefmt_macros-2f40157d788b0673.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcjjTQfQ/raw-dylibs ...\n9.255   ld.lld           877338 877337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2bW18f.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdefmt_macros-2f40157d788b0673.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcjjTQfQ/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n9.256   rust-lld         877338 877337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2bW18f.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdefmt_macros-2f40157d788b0673.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n9.387   rustc            877357 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name defmt --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"avoid-default-panic\", \"encoding-raw\", \"encoding-rzcobs\", \"ip_in_core\", \"unstable-test\")) -C metadata=56cbb9832b59f8ec ...\n14.721  16               877408 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n14.734  frpc             877408 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n14.792  runc             877414 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process1815085682 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n14.799  exe              877421 877414   0 /proc/self/exe init\n14.824  curl             877423 877414   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n17.082  cross            877429 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n17.083  rustc            877432 877429   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.090  rustc            877432 877429   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.104  rustc            877444 877429   0 /home/xmoe/.cargo/bin/rustc -vV\n17.110  rustc            877444 877429   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.121  cargo            877454 877429   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.128  cargo            877454 877429   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.141  rustc            877463 877454   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.152  rustc            877465 877454   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.166  rustc            877469 877454   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.202  rustc            877473 877429   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.209  rustc            877473 877429   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.224  docker           877485 877429   0 /usr/bin/docker --help\n17.239  docker           877496 877429   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.253  runc             877506 1599     0 /usr/bin/runc --version\n17.256  docker-init      877512 1599     0 /usr/bin/docker-init --version\n17.258  docker           877515 877429   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.272  runc             877525 1599     0 /usr/bin/runc --version\n17.276  docker-init      877531 1599     0 /usr/bin/docker-init --version\n17.301  rustup           877532 877429   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.308  rustup           877541 877429   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.339  rustup           877550 877429   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.371  uname            877559 877429   0 /usr/bin/uname -r\n17.391  docker           877560 877429   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.438  systemd-sysctl   877576 877574   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8b13c9c --prefix=/net/ipv4/neigh/veth8b13c9c --prefix=/net/ipv6/conf/veth8b13c9c --prefix=/net/ipv6/neigh/veth8b13c9c\n17.439  systemd-sysctl   877577 877575   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth177e74b --prefix=/net/ipv4/neigh/veth177e74b --prefix=/net/ipv6/conf/veth177e74b --prefix=/net/ipv6/neigh/veth177e74b\n17.453  containerd-shim  877607 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38 start\n17.457  containerd-shim  877616 877607   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38 -address /var/run/docker/containerd/containerd.sock\n17.461  runc             877626 877616   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38\n17.467  exe              877633 877626   0 /proc/self/exe init\n17.503  exe              877642 877626   0 /proc/1599/exe -exec-root=/var/run/docker 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38 d7da31e8f8e1\n17.528  exe              877651 1599     0 /proc/self/exe /var/run/docker/netns/eb4c1e4677e8 all false\n17.587  runc             877671 877616   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e --log-format json --systemd-cgroup start 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38\n17.592  sh               877636 877616   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.593  cargo            877677 877636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.608  cargo-native-tr  877677 877636   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.611  cargo            877678 877677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.625  rustc            877679 877678   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.638  rustc            877681 877678   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.684  execsnoop        877685 877677   0 /usr/local/bin/execsnoop -t\n17.684  python3          877685 877677   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876645,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
  "pid": 876645,
  "ppid": 876563,
  "root_cargo_pid": 876563,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out"
}
```

#### Record 19

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/16168903583143736270detect_compiler_family."
  ],
  "build_script_related": true,
  "build_script_root_pid": 876645,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 876646,
  "ppid": 876645,
  "root_cargo_pid": 876563,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/16168903583143736270detect_compiler_family.",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876645,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 876647,
  "ppid": 876646,
  "root_cargo_pid": 876563,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 21

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876645,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 876648,
  "ppid": 876645,
  "root_cargo_pid": 876563,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 22

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876645,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 876649,
  "ppid": 876645,
  "root_cargo_pid": 876563,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 23

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/hide.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "hide.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 876645,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 876650,
  "ppid": 876649,
  "root_cargo_pid": 876563,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 24

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
    "/tmp/ccW1uU6i.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876645,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 876651,
  "ppid": 876649,
  "root_cargo_pid": 876563,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 25

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876645,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 876652,
  "ppid": 876645,
  "root_cargo_pid": 876563,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 26

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "sD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876645,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 876653,
  "ppid": 876645,
  "root_cargo_pid": 876563,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 27

```json
{
  "crate": "clear_on_drop",
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "event_id": "bsrun:839cb6e3f248b25f:0c2e38447dfb082e:022ca268ecfe4b96",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
  "success": true,
  "target": null,
  "version": "0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 28

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/hide.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "hide.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "src/hide.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 876650,
  "ppid": 876649,
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 876563,
  "build_script_root_pid": 876645,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 29

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 876652,
  "ppid": 876645,
  "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 876563,
  "build_script_root_pid": 876645,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:53:47.182161+00:00",
  "crate": "clear_on_drop",
  "version": "0.2.5",
  "architecture": "ppc64le",
  "duration_seconds": 29.71398456208408,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "manifest_path": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "workspace_root": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
          "name": "clear_on_drop",
          "version": "0.2.5",
          "manifest_path": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 876624,
      "ppid": 876610,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:92d4b66b19e40f26:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
      "pid": 876624,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:263fff3c672d10c7:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
      "pid": 876624,
      "sha256": "90f6e0e4a8245af9622a558e455be8ee283a70911e1d4f26086741b20b373804",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:e25c1633e4e5c3fd:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
      "pid": 876624,
      "sha256": "bbbcb614b6abb1a09a32cf8fe2f7215cc8bf042426cbda2cbfca2877cd393d82",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:dd9e20295f81f863:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
      "pid": 876624,
      "sha256": "95d85cfb48222aa81a0ed0f81a9a39aa6ea8bc194cc5927e7c63caccd7c161a9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:eb5a0eb52ff8e3e9:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
      "pid": 876624,
      "sha256": "78f680bbbb58fbce98c8515153a3c26922439392d354916415a3cf891206f597",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:dc2e0c44e885bb25:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
      "pid": 876624,
      "sha256": "db16e67556993886981ac462ba6744b7a08016ba64d1c711c4c768ebe9ef6480",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:2e12e12d59121b06:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
      "pid": 876624,
      "sha256": "24a050c4cb686a13cdc4a4b85d065a57cd2c0213066028b99a72d788cc25d77d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:c2bd8b4ed8d7a44f:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
      "pid": 876624,
      "sha256": "d41207e12829aeb1c0eab21f3e9de1253b5901e24c9f75fbeed44141297d3fd7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:8f3eaf0d523143de:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
      "pid": 876624,
      "sha256": "e1e011a6ee5190c31346e92e1c183af892b95f9bafdbe75dfaa4c172ca15768c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:1dc61a243c4c1b83:b062681c751f8f39:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
      "pid": 876624,
      "sha256": "00bdc4bedc6940977b7809080c8598657c074c7db36a0b7c642000ffa0d84b61",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "context_path": "/tmp/native-trace-876546-1783997602154/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-876546-1783997602154/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 876624,
      "ppid": 876610,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q",
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
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-876624-1783997604710613117.map",
      "pid": 876624,
      "ppid": 876610,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-876624-1783997604710613117.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
      "parsed_event_count": 180,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 181,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "-435d7708213f6542/out/ea708c7824d36062-hide.o /tmp/ccW1uU6i.s\n0.872   powerpc64le-lin  876652 876645   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o\n0.874   powerpc64le-lin  876653 876645   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a\n0.880   rustc            876655 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clear_on_drop --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=b7d7c29f6545bab9 ...\n3.014   cross            876664 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n3.015   rustc            876667 876664   0 /home/xmoe/.cargo/bin/rustc --print target-list\n3.022   rustc            876667 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n3.037   rustc            876679 876664   0 /home/xmoe/.cargo/bin/rustc -vV\n3.044   rustc            876679 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n3.055   cargo            876689 876664   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n3.061   cargo            876689 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n3.074   rustc            876698 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n3.086   rustc            876700 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n3.101   rustc            876704 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n3.197   rustc            876708 876664   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n3.204   rustc            876708 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n3.218   docker           876720 876664   0 /usr/bin/docker --help\n3.234   docker           876731 876664   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n3.248   runc             876743 1599     0 /usr/bin/runc --version\n3.252   docker-init      876749 1599     0 /usr/bin/docker-init --version\n3.253   docker           876750 876664   0 /usr/bin/docker info -f {{.SecurityOptions}}\n3.267   runc             876763 1599     0 /usr/bin/runc --version\n3.270   docker-init      876769 1599     0 /usr/bin/docker-init --version\n3.296   rustup           876770 876664   0 /home/xmoe/.cargo/bin/rustup toolchain list\n3.304   rustup           876779 876664   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n3.335   rustup           876788 876664   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n3.366   uname            876797 876664   0 /usr/bin/uname -r\n3.386   docker           876798 876664   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n3.433   systemd-sysctl   876814 876812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8ebf659 --prefix=/net/ipv4/neigh/veth8ebf659 --prefix=/net/ipv6/conf/veth8ebf659 --prefix=/net/ipv6/neigh/veth8ebf659\n3.434   systemd-sysctl   876815 876813   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth88c0a91 --prefix=/net/ipv4/neigh/veth88c0a91 --prefix=/net/ipv6/conf/veth88c0a91 --prefix=/net/ipv6/neigh/veth88c0a91\n3.446   containerd-shim  876839 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 start\n3.450   containerd-shim  876854 876839   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 -address /var/run/docker/containerd/containerd.sock\n3.455   runc             876864 876854   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340\n3.461   exe              876872 876864   0 /proc/self/exe init\n3.500   exe              876881 876864   0 /proc/1599/exe -exec-root=/var/run/docker 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 d7da31e8f8e1\n3.525   exe              876889 1599     0 /proc/self/exe /var/run/docker/netns/dc57e9676e3f all false\n3.576   runc             876908 876854   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --log-format json --systemd-cgroup start 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340\n3.582   sh               876875 876854   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n3.583   cargo            876914 876875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n3.597   cargo-native-tr  876914 876875   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n3.600   cargo            876915 876914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n3.613   rustc            876916 876915   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n3.626   rustc            876918 876915   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n3.672   execsnoop        876922 876914   0 /usr/local/bin/execsnoop -t\n3.672   python3          876922 876914   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n5.404   cargo            876925 876914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n5.417   rustc            876926 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n5.443   rustc            876936 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n5.444   rustc            876938 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de2844ba6b8ae918 ...\n5.444   rustc            876939 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n5.445   rustc            876941 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n5.445   rustc            876940 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"avoid-default-panic\", \"encoding-raw\", \"encoding-rzcobs\", \"ip_in_core\", \"unstable-test\")) -C metadata=44a85da66c008e88 ...\n5.446   rustc            876942 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/defmt-macros-1.0.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"unstable-test\")) -C metadata=c7338f2308d4bca1 ...\n5.472   cc               876967 876942   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/defmt-macros-fcfcc24ad5e74756/rustc464jBI/symbols.o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.build_script_build.ccd373c524451d1d-cgu.0. /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.70c1azqju59eihbinusj5hug8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.473   cc               876968 876967   0 /usr/bin/cc -m64 /target/debug/build/defmt-macros-fcfcc24ad5e74756/rustc464jBI/symbols.o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.build_script_build.ccd373c524451d1d-cgu.0. /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.70c1azqju59eihbinusj5hug8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.475   collect2         876971 876968   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.476   ld.lld           876973 876971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756 ...\n5.477   rust-lld         876973 876971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.515   build-script-bu  877034 876925   0 /target/debug/build/defmt-macros-fcfcc24ad5e74756/build-script-build\n5.523   cc               877037 876940   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/defmt-88870500e9779679/rustcTOqJFU/symbols.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.055zk37rzu569svhsi8q0o5qp.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.0rpv6ef39zfh377kqpdwqt6g9.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.158lqt5y2x83b9zsise8h73nq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.3y17x9xbl4j2afwwz8a9jc45o.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.40r4tyzccbeuezyaizzylk2pn.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4bhsadt7ulwe6zi6wa5f8k4aj.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4kywhqz7rbi6dpvtowz2r7nmf.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4n65qxab0563utyx0d6yhcb0d.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.5ufph9gh2gjta1sd3skwekhym.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.6151boy9kvqnlg3qn0nvmpftq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.65m8e7svy2yd8r3ggvoecu0p7.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.69h4j683oo774547xc2muhfit.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.76diyyj2mrnynm3echznpxa7u.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.79h1339cdeg95ond51d88dcrh.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.876z0191hx79yv6qhd5o1wj6b.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.8g047khgm9nav92c2w6gjimps.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.999uopozu2buzwryf507eyhfy.06021wv.rcgu.o ...\n5.524   cc               877038 877037   0 /usr/bin/cc -m64 /target/debug/build/defmt-88870500e9779679/rustcTOqJFU/symbols.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.055zk37rzu569svhsi8q0o5qp.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.0rpv6ef39zfh377kqpdwqt6g9.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.158lqt5y2x83b9zsise8h73nq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.3y17x9xbl4j2afwwz8a9jc45o.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.40r4tyzccbeuezyaizzylk2pn.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4bhsadt7ulwe6zi6wa5f8k4aj.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4kywhqz7rbi6dpvtowz2r7nmf.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4n65qxab0563utyx0d6yhcb0d.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.5ufph9gh2gjta1sd3skwekhym.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.6151boy9kvqnlg3qn0nvmpftq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.65m8e7svy2yd8r3ggvoecu0p7.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.69h4j683oo774547xc2muhfit.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.76diyyj2mrnynm3echznpxa7u.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.79h1339cdeg95ond51d88dcrh.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.876z0191hx79yv6qhd5o1wj6b.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.8g047khgm9nav92c2w6gjimps.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.999uopozu2buzwryf507eyhfy.06021wv.rcgu.o ...\n5.526   collect2         877039 877038   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.528   ld.lld           877040 877039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679 ...\n5.529   rust-lld         877040 877039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.538   cc               877041 876936   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/proc-macro2-9397a4c89a8399e7/rustc2dgGS1/symbols.o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.0.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.1.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.4il8xo66kpq7xyp9ndwunhiok.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.539   cc               877042 877041   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-9397a4c89a8399e7/rustc2dgGS1/symbols.o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.0.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.1.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.4il8xo66kpq7xyp9ndwunhiok.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.541   cc               877059 876941   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcrixLna/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.541   collect2         877060 877042   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.541   cc               877061 877059   0 /usr/bin/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcrixLna/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.542   ld.lld           877062 877060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7 ...\n5.543   rust-lld         877062 877060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.543   collect2         877063 877061   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.544   ld.lld           877064 877063   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b ...\n5.545   rust-lld         877064 877063   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.574   build-script-bu  877098 876925   0 /target/debug/build/defmt-88870500e9779679/build-script-build\n5.583   build-script-bu  877100 876925   0 /target/debug/build/thiserror-c8cdc86597298e7b/build-script-build\n5.584   build-script-bu  877102 876925   0 /target/debug/build/proc-macro2-9397a4c89a8399e7/build-script-build\n5.585   rustc            877103 877100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/thiserror-43e7d0657569a05a/out/probe build/probe.rs --target x86_64-unknown-linux-gnu\n5.586   rustc            877104 877102   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n5.594   rustc            877109 877102   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-c75d55102dcd3bb9/out/probe build/probe.rs --target x86_64-unknown-linux-gnu\n5.619   rustc            877113 877100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n5.621   rustc            877115 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n5.801   rustc            877123 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n5.895   rustc            877139 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.100/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n5.943   runc             877144 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2279327366 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n5.948   exe              877151 877144   0 /proc/self/exe init\n5.959   rustc            877160 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-attr2-2.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --check-cfg cfg(docsrs,test) --check-cfg ...\n5.964   curl             877153 877144   0 /usr/bin/curl -f http://localhost:9091/healthz\n6.067   cc               877169 877160   0 /tmp/native-trace-876914-1783997607526/shims/cc -Wl,--version-script=/target/debug/deps/rustc3FdlPW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc3FdlPW/symbols.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.1.rcgu.o /target/debug/deps/rustc3FdlPW/rmeta.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.55sq3uw3glcy6pozjsuixo9q6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-cd059401c8285246.rlib /target/debug/deps/libproc_macro2-02759104fca4896a.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n6.067   cc               877170 877169   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc3FdlPW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc3FdlPW/symbols.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.1.rcgu.o /target/debug/deps/rustc3FdlPW/rmeta.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.55sq3uw3glcy6pozjsuixo9q6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-cd059401c8285246.rlib /target/debug/deps/libproc_macro2-02759104fca4896a.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n6.070   collect2         877171 877170   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc3FdlPW/raw-dylibs ...\n6.071   ld.lld           877172 877171   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc3FdlPW/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n6.072   rust-lld         877172 877171   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n7.322   rustc            877192 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error2-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=unexpected_cfgs --allow=clippy::module_name_repetitions --check-cfg cfg(run_ui_tests) --cfg ...\n7.850   rustc            877217 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n7.940   runc             877221 876026   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --log-format json --systemd-cgroup kill --all 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 9\n7.956   runc             877228 876026   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 --log-format json --systemd-cgroup delete 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9\n8.147   containerd-shim  877236 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc9 delete\n8.149   runc             877243 877236   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad --log-format json delete --force 869bed3400697c117b6025033a22e57d974bd49e7245d1bdca47ce80bc971ad9\n8.188   sh               877253 877249   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethd7ce0d8\n8.189   ethtool          877254 877253   0 /usr/sbin/ethtool -i vethd7ce0d8\n8.189   sed              877255 877253   0 /usr/bin/sed -n s/^driver: //p\n8.196   systemd-sysctl   877258 877249   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd7ce0d8 --prefix=/net/ipv4/neigh/vethd7ce0d8 --prefix=/net/ipv6/conf/vethd7ce0d8 --prefix=/net/ipv6/neigh/vethd7ce0d8\n8.367   cc               877274 877217   0 /tmp/native-trace-876914-1783997607526/shims/cc -Wl,--version-script=/target/debug/deps/rustcXcFra1/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcXcFra1/symbols.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.14.rcgu.o ...\n8.368   cc               877275 877274   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcXcFra1/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcXcFra1/symbols.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-6252ecb0467e164f.thiserror_impl.ecbc402b1c1c9493-cgu.14.rcgu.o ...\n8.370   collect2         877276 877275   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm3f3LA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-6252ecb0467e164f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcXcFra1/raw-dylibs ...\n8.372   ld.lld           877277 877276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm3f3LA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-6252ecb0467e164f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcXcFra1/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n8.373   rust-lld         877277 877276   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm3f3LA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-6252ecb0467e164f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n8.490   rustc            877295 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n8.519   rustc            877303 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name defmt_parser --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/defmt-parser-1.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"unstable\")) -C metadata=eea9feea4d5ec196 ...\n8.651   rustc            877313 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name defmt_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/defmt-macros-1.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"unstable-test\")) ...\n9.250   cc               877335 877313   0 /tmp/native-trace-876914-1783997607526/shims/cc -Wl,--version-script=/target/debug/deps/rustcjjTQfQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcjjTQfQ/symbols.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.00.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.01.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.02.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.03.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.04.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.05.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.06.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.07.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.08.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.09.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.10.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.11.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.12.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.13.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.14.rcgu.o ...\n9.251   cc               877336 877335   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcjjTQfQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcjjTQfQ/symbols.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.00.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.01.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.02.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.03.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.04.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.05.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.06.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.07.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.08.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.09.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.10.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.11.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.12.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.13.rcgu.o /target/debug/deps/defmt_macros-2f40157d788b0673.defmt_macros.d08415cac75d37bf-cgu.14.rcgu.o ...\n9.254   collect2         877337 877336   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2bW18f.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libdefmt_macros-2f40157d788b0673.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcjjTQfQ/raw-dylibs ...\n9.255   ld.lld           877338 877337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2bW18f.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdefmt_macros-2f40157d788b0673.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcjjTQfQ/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n9.256   rust-lld         877338 877337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2bW18f.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdefmt_macros-2f40157d788b0673.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n9.387   rustc            877357 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name defmt --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"avoid-default-panic\", \"encoding-raw\", \"encoding-rzcobs\", \"ip_in_core\", \"unstable-test\")) -C metadata=56cbb9832b59f8ec ...\n14.721  16               877408 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n14.734  frpc             877408 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n14.792  runc             877414 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process1815085682 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n14.799  exe              877421 877414   0 /proc/self/exe init\n14.824  curl             877423 877414   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n17.082  cross            877429 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n17.083  rustc            877432 877429   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.090  rustc            877432 877429   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.104  rustc            877444 877429   0 /home/xmoe/.cargo/bin/rustc -vV\n17.110  rustc            877444 877429   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.121  cargo            877454 877429   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.128  cargo            877454 877429   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.141  rustc            877463 877454   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.152  rustc            877465 877454   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.166  rustc            877469 877454   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.202  rustc            877473 877429   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.209  rustc            877473 877429   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.224  docker           877485 877429   0 /usr/bin/docker --help\n17.239  docker           877496 877429   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.253  runc             877506 1599     0 /usr/bin/runc --version\n17.256  docker-init      877512 1599     0 /usr/bin/docker-init --version\n17.258  docker           877515 877429   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.272  runc             877525 1599     0 /usr/bin/runc --version\n17.276  docker-init      877531 1599     0 /usr/bin/docker-init --version\n17.301  rustup           877532 877429   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.308  rustup           877541 877429   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.339  rustup           877550 877429   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.371  uname            877559 877429   0 /usr/bin/uname -r\n17.391  docker           877560 877429   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.438  systemd-sysctl   877576 877574   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8b13c9c --prefix=/net/ipv4/neigh/veth8b13c9c --prefix=/net/ipv6/conf/veth8b13c9c --prefix=/net/ipv6/neigh/veth8b13c9c\n17.439  systemd-sysctl   877577 877575   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth177e74b --prefix=/net/ipv4/neigh/veth177e74b --prefix=/net/ipv6/conf/veth177e74b --prefix=/net/ipv6/neigh/veth177e74b\n17.453  containerd-shim  877607 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38 start\n17.457  containerd-shim  877616 877607   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38 -address /var/run/docker/containerd/containerd.sock\n17.461  runc             877626 877616   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38\n17.467  exe              877633 877626   0 /proc/self/exe init\n17.503  exe              877642 877626   0 /proc/1599/exe -exec-root=/var/run/docker 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38 d7da31e8f8e1\n17.528  exe              877651 1599     0 /proc/self/exe /var/run/docker/netns/eb4c1e4677e8 all false\n17.587  runc             877671 877616   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e --log-format json --systemd-cgroup start 45ea242302ec69da6eecc2db35503b1551268e09119c2fb5a7aae51c05e8cd38\n17.592  sh               877636 877616   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.593  cargo            877677 877636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.608  cargo-native-tr  877677 877636   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.611  cargo            877678 877677   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.625  rustc            877679 877678   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.638  rustc            877681 877678   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.684  execsnoop        877685 877677   0 /usr/local/bin/execsnoop -t\n17.684  python3          877685 877677   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n"
    },
    {
      "argv": [
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876645,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
      "pid": 876645,
      "ppid": 876563,
      "root_cargo_pid": 876563,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/16168903583143736270detect_compiler_family."
      ],
      "build_script_related": true,
      "build_script_root_pid": 876645,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 876646,
      "ppid": 876645,
      "root_cargo_pid": 876563,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/16168903583143736270detect_compiler_family.",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876645,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 876647,
      "ppid": 876646,
      "root_cargo_pid": 876563,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876645,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 876648,
      "ppid": 876645,
      "root_cargo_pid": 876563,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-Wall",
        "-Wextra",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876645,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 876649,
      "ppid": 876645,
      "root_cargo_pid": 876563,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "src/hide.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "hide.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 876645,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 876650,
      "ppid": 876649,
      "root_cargo_pid": 876563,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o",
        "/tmp/ccW1uU6i.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876645,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 876651,
      "ppid": 876649,
      "root_cargo_pid": 876563,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cqD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876645,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 876652,
      "ppid": 876645,
      "root_cargo_pid": 876563,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "sD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876645,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 876653,
      "ppid": 876645,
      "root_cargo_pid": 876563,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "clear_on_drop",
      "cwd": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "event_id": "bsrun:839cb6e3f248b25f:0c2e38447dfb082e:022ca268ecfe4b96",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
      "out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
      "success": true,
      "target": null,
      "version": "0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-1p08bhds/src/clear_on_drop-0.2.5",
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
