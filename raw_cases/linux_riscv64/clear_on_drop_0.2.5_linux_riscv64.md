# `clear_on_drop` `0.2.5`

Platform: Linux riscv64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a`

Owner: `clear_on_drop` `0.2.5`

### Source files

* `/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5/src/hide.c`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/hide.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/",
    "-dumpbase",
    "ea708c7824d36062-hide.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-g",
    "-gdwarf-4",
    "..."
  ],
  "src": "src/hide.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 876218,
  "ppid": 876217,
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 876131,
  "build_script_root_pid": 876213,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 876220,
  "ppid": 876213,
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 876131,
  "build_script_root_pid": 876213,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "workspace_root": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
      "name": "clear_on_drop",
      "version": "0.2.5",
      "manifest_path": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 876192,
  "ppid": 876178,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:8232a70abd00eecb:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
  "pid": 876192,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:a479496f0e5eddde:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
  "pid": 876192,
  "sha256": "43bb0f461f37b287a0d1a57154f8e3ac54d5699666a5e10ec07591515e06b68c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:b975752c0ceb002d:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
  "pid": 876192,
  "sha256": "2104078c8531e15b0b856e0671476c7a6d0d3aaea0b57ea987d0b72ae8efe483",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:45245beb5387db3b:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
  "pid": 876192,
  "sha256": "fe2a8b58fb8b8a568a1c0ff4c99bc243e517dcc084922c203501fce679bc3726",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:f8e337039436a75b:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
  "pid": 876192,
  "sha256": "e84a0fe2c2c6a7e1d10e4078cdaae094e1d5418c52d89408876149eddbab34a0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:28bfbc92890899e0:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
  "pid": 876192,
  "sha256": "c364ff79f2c8fb253dc3cf899c7ebee6434b0845dfd35bb460062e2c8ea15301",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:c606c4b3af94327f:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
  "pid": 876192,
  "sha256": "50c8fd80bf219414ae6129854c6d38bb0a8e0ab7f08bebbf9e465565878f89f3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:affe7193b4d1dcd1:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
  "pid": 876192,
  "sha256": "b23ff5389ad9ed04d81e5c644c5d002d5ff0be59b0ec13958e18282ad8faefec",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:e4c54975224682a6:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
  "pid": 876192,
  "sha256": "4ac9c4220eaf29c9c31b2e7211d373ce0ac002dca7287a82326cded48270a917",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "used:cc:27a7acad25c41f85:193180ea2612066f:05e780806641a877",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
  "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
  "pid": 876192,
  "sha256": "00bdc4bedc6940977b7809080c8598657c074c7db36a0b7c642000ffa0d84b61",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "cargo_pkg_name": "clear_on_drop",
  "cargo_pkg_version": "0.2.5",
  "context_path": "/tmp/native-trace-876092-1783997591859/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-876092-1783997591859/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 876192,
  "ppid": 876178,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U",
    "/target/debug/build/clear_on_drop-7166f128fe0bc058",
    "/target/debug/deps",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/lib64"
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
      "kind": "object",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
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
      "directory": "/lib/x86_64-linux-gnu",
      "kind": "dynamic_library",
      "path": "/lib/x86_64-linux-gnu/libc.so.6",
      "source": "link_trace"
    },
    {
      "directory": "/lib64",
      "kind": "dynamic_library",
      "path": "/lib64/ld-linux-x86-64.so.2",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o",
      "source": "link_trace"
    },
    {
      "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
      "kind": "object",
      "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o",
      "source": "link_trace"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-876192-1783997594666523323.map",
  "pid": 876192,
  "ppid": 876178,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-876192-1783997594666523323.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
  "parsed_event_count": 188,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 189,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "-64.so.2 -pie -z now -z relro ...\n0.845   build-script-bu  876213 876131   0 /target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build\n0.846   riscv64-linux-g  876214 876213   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/10200110540939495728detect_compiler_family.c\n0.847   cc1              876215 876214   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/10200110540939495728detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 10200110540939495728detect_compiler_family.c -dumpbase-ext .c\n0.852   riscv64-linux-g  876216 876213   0 /usr/bin/riscv64-linux-gnu-gcc -?\n0.855   riscv64-linux-g  876217 876213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o -c src/hide.c\n0.857   cc1              876218 876217   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu src/hide.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ -dumpbase ea708c7824d36062-hide.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...\n0.862   as               876219 876217   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o /tmp/cccwZAqe.s\n0.864   riscv64-linux-g  876220 876213   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o\n0.881   riscv64-linux-g  876221 876213   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a\n0.898   rustc            876223 876131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clear_on_drop --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=98d35d6d344c61aa ...\n1.933   runc             876233 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1494758271 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n1.937   exe              876240 876233   0 /proc/self/exe init\n1.963   etcdctl          876242 876233   0 /usr/local/bin/etcdctl endpoint health\n4.001   runc             876255 875058   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf --log-format json --systemd-cgroup kill --all 9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca6 9\n4.019   runc             876262 875058   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf --log-format json --systemd-cgroup delete 9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca6\n4.188   containerd-shim  876268 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca6 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf delete\n4.191   runc             876274 876268   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca --log-format json delete --force 9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca6\n4.235   sh               876283 876280   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethf4ee02b\n4.236   ethtool          876284 876283   0 /usr/sbin/ethtool -i vethf4ee02b\n4.236   sed              876285 876283   0 /usr/bin/sed -n s/^driver: //p\n4.243   systemd-sysctl   876288 876280   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4ee02b --prefix=/net/ipv4/neigh/vethf4ee02b --prefix=/net/ipv6/conf/vethf4ee02b --prefix=/net/ipv6/neigh/vethf4ee02b\n7.318   cross            876291 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n7.320   rustc            876294 876291   0 /home/xmoe/.cargo/bin/rustc --print target-list\n7.327   rustc            876294 876291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n7.343   rustc            876306 876291   0 /home/xmoe/.cargo/bin/rustc -vV\n7.350   rustc            876306 876291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.361   cargo            876316 876291   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n7.368   cargo            876316 876291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n7.381   rustc            876325 876316   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.392   rustc            876327 876316   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n7.406   rustc            876331 876316   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n7.715   rustc            876336 876316   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.875   rustc            876338 876291   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n7.882   rustc            876338 876291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n7.896   docker           876350 876291   0 /usr/bin/docker --help\n7.912   docker           876362 876291   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n7.925   runc             876372 1599     0 /usr/bin/runc --version\n7.928   docker-init      876378 1599     0 /usr/bin/docker-init --version\n7.930   docker           876383 876291   0 /usr/bin/docker info -f {{.SecurityOptions}}\n7.943   runc             876394 1599     0 /usr/bin/runc --version\n7.947   docker-init      876400 1599     0 /usr/bin/docker-init --version\n7.973   rustup           876401 876291   0 /home/xmoe/.cargo/bin/rustup toolchain list\n7.980   rustup           876410 876291   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n8.010   rustup           876419 876291   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n8.040   uname            876428 876291   0 /usr/bin/uname -r\n8.060   docker           876429 876291   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n8.107   systemd-sysctl   876446 876444   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0c64c6f --prefix=/net/ipv4/neigh/veth0c64c6f --prefix=/net/ipv6/conf/veth0c64c6f --prefix=/net/ipv6/neigh/veth0c64c6f\n8.108   systemd-sysctl   876447 876445   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc477d29 --prefix=/net/ipv4/neigh/vethc477d29 --prefix=/net/ipv6/conf/vethc477d29 --prefix=/net/ipv6/neigh/vethc477d29\n8.119   containerd-shim  876467 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e start\n8.122   containerd-shim  876483 876467   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e -address /var/run/docker/containerd/containerd.sock\n8.127   runc             876496 876483   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a073 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a073 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a073 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e\n8.133   exe              876504 876496   0 /proc/self/exe init\n8.174   exe              876512 876496   0 /proc/1599/exe -exec-root=/var/run/docker 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e d7da31e8f8e1\n8.199   exe              876521 1599     0 /proc/self/exe /var/run/docker/netns/a0f64be15e3b all false\n8.252   runc             876540 876483   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a073 --log-format json --systemd-cgroup start 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e\n8.258   sh               876506 876483   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n8.259   cargo            876546 876506   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n8.273   cargo-native-tr  876546 876506   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n8.276   cargo            876547 876546   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n8.290   rustc            876548 876547   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.302   rustc            876550 876547   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.380   execsnoop        876554 876546   0 /usr/local/bin/execsnoop -t\n8.380   python3          876554 876546   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n9.518   16               876557 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n9.531   frpc             876557 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.137  cargo            876563 876546   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n10.148  rustc            876564 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n10.179  rustc            876571 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n10.179  rustc            876572 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n10.241  rustc            876585 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n10.794  rustc            876610 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=2c38527a274a239e ...\n10.829  cc               876624 876610   0 /tmp/native-trace-876546-1783997602154/shims/cc -m64 /target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n10.830  cc               876625 876624   0 /usr/bin/cc -m64 /target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n10.833  collect2         876626 876625   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccS1iR0s.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n10.834  ld.lld           876627 876626   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccS1iR0s.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058 ...\n10.836  rust-lld         876627 876626   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccS1iR0s.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n10.897  build-script-bu  876645 876563   0 /target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build\n10.898  powerpc64le-lin  876646 876645   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/16168903583143736270detect_compiler_family.\n10.900  cc1              876647 876646   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/16168903583143736270detect_compiler_family. -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n10.903  powerpc64le-lin  876648 876645   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n10.905  powerpc64le-lin  876649 876645   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o -c src/hide.c\n10.907  cc1              876650 876649   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu src/hide.c -msecure-plt -quiet -dumpbase hide.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...\n10.915  as               876651 876649   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o /tmp/ccW1uU6i.s\n10.921  powerpc64le-lin  876652 876645   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o\n10.923  powerpc64le-lin  876653 876645   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a\n10.928  rustc            876655 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clear_on_drop --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=b7d7c29f6545bab9 ...\n13.062  cross            876664 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n13.064  rustc            876667 876664   0 /home/xmoe/.cargo/bin/rustc --print target-list\n13.070  rustc            876667 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n13.085  rustc            876679 876664   0 /home/xmoe/.cargo/bin/rustc -vV\n13.092  rustc            876679 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.104  cargo            876689 876664   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n13.110  cargo            876689 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n13.123  rustc            876698 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.134  rustc            876700 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.150  rustc            876704 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n13.245  rustc            876708 876664   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n13.252  rustc            876708 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n13.266  docker           876720 876664   0 /usr/bin/docker --help\n13.282  docker           876731 876664   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n13.297  runc             876743 1599     0 /usr/bin/runc --version\n13.300  docker-init      876749 1599     0 /usr/bin/docker-init --version\n13.301  docker           876750 876664   0 /usr/bin/docker info -f {{.SecurityOptions}}\n13.315  runc             876763 1599     0 /usr/bin/runc --version\n13.319  docker-init      876769 1599     0 /usr/bin/docker-init --version\n13.345  rustup           876770 876664   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.352  rustup           876779 876664   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.384  rustup           876788 876664   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.414  uname            876797 876664   0 /usr/bin/uname -r\n13.434  docker           876798 876664   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n13.482  systemd-sysctl   876814 876812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8ebf659 --prefix=/net/ipv4/neigh/veth8ebf659 --prefix=/net/ipv6/conf/veth8ebf659 --prefix=/net/ipv6/neigh/veth8ebf659\n13.483  systemd-sysctl   876815 876813   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth88c0a91 --prefix=/net/ipv4/neigh/veth88c0a91 --prefix=/net/ipv6/conf/veth88c0a91 --prefix=/net/ipv6/neigh/veth88c0a91\n13.495  containerd-shim  876839 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 start\n13.498  containerd-shim  876854 876839   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 -address /var/run/docker/containerd/containerd.sock\n13.504  runc             876864 876854   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340\n13.509  exe              876872 876864   0 /proc/self/exe init\n13.548  exe              876881 876864   0 /proc/1599/exe -exec-root=/var/run/docker 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 d7da31e8f8e1\n13.573  exe              876889 1599     0 /proc/self/exe /var/run/docker/netns/dc57e9676e3f all false\n13.625  runc             876908 876854   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --log-format json --systemd-cgroup start 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340\n13.630  sh               876875 876854   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.632  cargo            876914 876875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n13.645  cargo-native-tr  876914 876875   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n13.649  cargo            876915 876914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.662  rustc            876916 876915   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.674  rustc            876918 876915   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.720  execsnoop        876922 876914   0 /usr/local/bin/execsnoop -t\n13.721  python3          876922 876914   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.452  cargo            876925 876914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n15.465  rustc            876926 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.491  rustc            876936 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.492  rustc            876938 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de2844ba6b8ae918 ...\n15.492  rustc            876939 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n15.492  rustc            876940 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"avoid-default-panic\", \"encoding-raw\", \"encoding-rzcobs\", \"ip_in_core\", \"unstable-test\")) -C metadata=44a85da66c008e88 ...\n15.493  rustc            876941 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.493  rustc            876942 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/defmt-macros-1.0.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"unstable-test\")) -C metadata=c7338f2308d4bca1 ...\n15.520  cc               876967 876942   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/defmt-macros-fcfcc24ad5e74756/rustc464jBI/symbols.o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.build_script_build.ccd373c524451d1d-cgu.0. /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.70c1azqju59eihbinusj5hug8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n15.521  cc               876968 876967   0 /usr/bin/cc -m64 /target/debug/build/defmt-macros-fcfcc24ad5e74756/rustc464jBI/symbols.o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.build_script_build.ccd373c524451d1d-cgu.0. /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.70c1azqju59eihbinusj5hug8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n15.523  collect2         876971 876968   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.525  ld.lld           876973 876971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756 ...\n15.526  rust-lld         876973 876971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.563  build-script-bu  877034 876925   0 /target/debug/build/defmt-macros-fcfcc24ad5e74756/build-script-build\n15.571  cc               877037 876940   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/defmt-88870500e9779679/rustcTOqJFU/symbols.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.055zk37rzu569svhsi8q0o5qp.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.0rpv6ef39zfh377kqpdwqt6g9.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.158lqt5y2x83b9zsise8h73nq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.3y17x9xbl4j2afwwz8a9jc45o.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.40r4tyzccbeuezyaizzylk2pn.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4bhsadt7ulwe6zi6wa5f8k4aj.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4kywhqz7rbi6dpvtowz2r7nmf.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4n65qxab0563utyx0d6yhcb0d.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.5ufph9gh2gjta1sd3skwekhym.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.6151boy9kvqnlg3qn0nvmpftq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.65m8e7svy2yd8r3ggvoecu0p7.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.69h4j683oo774547xc2muhfit.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.76diyyj2mrnynm3echznpxa7u.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.79h1339cdeg95ond51d88dcrh.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.876z0191hx79yv6qhd5o1wj6b.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.8g047khgm9nav92c2w6gjimps.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.999uopozu2buzwryf507eyhfy.06021wv.rcgu.o ...\n15.572  cc               877038 877037   0 /usr/bin/cc -m64 /target/debug/build/defmt-88870500e9779679/rustcTOqJFU/symbols.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.055zk37rzu569svhsi8q0o5qp.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.0rpv6ef39zfh377kqpdwqt6g9.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.158lqt5y2x83b9zsise8h73nq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.3y17x9xbl4j2afwwz8a9jc45o.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.40r4tyzccbeuezyaizzylk2pn.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4bhsadt7ulwe6zi6wa5f8k4aj.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4kywhqz7rbi6dpvtowz2r7nmf.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4n65qxab0563utyx0d6yhcb0d.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.5ufph9gh2gjta1sd3skwekhym.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.6151boy9kvqnlg3qn0nvmpftq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.65m8e7svy2yd8r3ggvoecu0p7.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.69h4j683oo774547xc2muhfit.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.76diyyj2mrnynm3echznpxa7u.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.79h1339cdeg95ond51d88dcrh.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.876z0191hx79yv6qhd5o1wj6b.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.8g047khgm9nav92c2w6gjimps.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.999uopozu2buzwryf507eyhfy.06021wv.rcgu.o ...\n15.575  collect2         877039 877038   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.576  ld.lld           877040 877039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679 ...\n15.577  rust-lld         877040 877039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.586  cc               877041 876936   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/proc-macro2-9397a4c89a8399e7/rustc2dgGS1/symbols.o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.0.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.1.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.4il8xo66kpq7xyp9ndwunhiok.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.587  cc               877042 877041   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-9397a4c89a8399e7/rustc2dgGS1/symbols.o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.0.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.1.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.4il8xo66kpq7xyp9ndwunhiok.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.589  cc               877059 876941   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcrixLna/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.589  collect2         877060 877042   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.590  cc               877061 877059   0 /usr/bin/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcrixLna/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.590  ld.lld           877062 877060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7 ...\n15.591  rust-lld         877062 877060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.592  collect2         877063 877061   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.593  ld.lld           877064 877063   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b ...\n15.593  rust-lld         877064 877063   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.623  build-script-bu  877098 876925   0 /target/debug/build/defmt-88870500e9779679/build-script-build\n15.632  build-script-bu  877100 876925   0 /target/debug/build/thiserror-c8cdc86597298e7b/build-script-build\n15.633  build-script-bu  877102 876925   0 /target/debug/build/proc-macro2-9397a4c89a8399e7/build-script-build\n15.633  rustc            877103 877100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/thiserror-43e7d0657569a05a/out/probe build/probe.rs --target x86_64-unknown-linux-gnu\n15.634  rustc            877104 877102   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.642  rustc            877109 877102   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-c75d55102dcd3bb9/out/probe build/probe.rs --target x86_64-unknown-linux-gnu\n15.667  rustc            877113 877100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.669  rustc            877115 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.849  rustc            877123 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.943  rustc            877139 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.100/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n15.991  runc             877144 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2279327366 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.996  exe              877151 877144   0 /proc/self/exe init\n16.007  rustc            877160 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-attr2-2.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --check-cfg cfg(docsrs,test) --check-cfg ...\n16.012  curl             877153 877144   0 /usr/bin/curl -f http://localhost:9091/healthz\n16.115  cc               877169 877160   0 /tmp/native-trace-876914-1783997607526/shims/cc -Wl,--version-script=/target/debug/deps/rustc3FdlPW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc3FdlPW/symbols.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.1.rcgu.o /target/debug/deps/rustc3FdlPW/rmeta.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.55sq3uw3glcy6pozjsuixo9q6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-cd059401c8285246.rlib /target/debug/deps/libproc_macro2-02759104fca4896a.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n16.115  cc               877170 877169   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc3FdlPW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc3FdlPW/symbols.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.1.rcgu.o /target/debug/deps/rustc3FdlPW/rmeta.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.55sq3uw3glcy6pozjsuixo9q6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-cd059401c8285246.rlib /target/debug/deps/libproc_macro2-02759104fca4896a.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n16.118  collect2         877171 877170   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc3FdlPW/raw-dylibs ...\n16.119  ld.lld           877172 877171   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc3FdlPW/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.120  rust-lld         877172 877171   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.370  rustc            877192 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error2-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=unexpected_cfgs --allow=clippy::module_name_repetitions --check-cfg cfg(run_ui_tests) --cfg ...\n17.898  rustc            877217 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876213,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
  "pid": 876213,
  "ppid": 876131,
  "root_cargo_pid": 876131,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out"
}
```

#### Record 19

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-E",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/10200110540939495728detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876213,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 876214,
  "ppid": 876213,
  "root_cargo_pid": 876131,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-E",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/10200110540939495728detect_compiler_family.c",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-dumpbase",
    "10200110540939495728detect_compiler_family.c",
    "-dumpbase-ext",
    ".c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876213,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 876215,
  "ppid": 876214,
  "root_cargo_pid": 876131,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 21

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876213,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 876216,
  "ppid": 876213,
  "root_cargo_pid": 876131,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 22

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o",
    "-c",
    "src/hide.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876213,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 876217,
  "ppid": 876213,
  "root_cargo_pid": 876131,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 23

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/hide.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/",
    "-dumpbase",
    "ea708c7824d36062-hide.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-g",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 876213,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 876218,
  "ppid": 876217,
  "root_cargo_pid": 876131,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 24

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o",
    "/tmp/cccwZAqe.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876213,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 876219,
  "ppid": 876217,
  "root_cargo_pid": 876131,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 25

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876213,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 876220,
  "ppid": 876213,
  "root_cargo_pid": 876131,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 26

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "sD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 876213,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 876221,
  "ppid": 876213,
  "root_cargo_pid": 876131,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 27

```json
{
  "crate": "clear_on_drop",
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "event_id": "bsrun:baafdddc65e4bf87:0c2e38447dfb082e:022ca268ecfe4b96",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
  "success": true,
  "target": null,
  "version": "0.2.5",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 28

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/hide.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/",
    "-dumpbase",
    "ea708c7824d36062-hide.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-g",
    "-gdwarf-4",
    "..."
  ],
  "src": "src/hide.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 876218,
  "ppid": 876217,
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 876131,
  "build_script_root_pid": 876213,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 29

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 876220,
  "ppid": 876213,
  "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "root_cargo_pid": 876131,
  "build_script_root_pid": 876213,
  "build_script_related": true,
  "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
  "_owner": {
    "crate": "clear_on_drop",
    "version": "0.2.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
    "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
  "_build_script_out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:53:37.159501+00:00",
  "crate": "clear_on_drop",
  "version": "0.2.5",
  "architecture": "riscv64",
  "duration_seconds": 30.089131120126694,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "manifest_path": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "workspace_root": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
          "name": "clear_on_drop",
          "version": "0.2.5",
          "manifest_path": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 876192,
      "ppid": 876178,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:8232a70abd00eecb:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
      "pid": 876192,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:a479496f0e5eddde:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
      "pid": 876192,
      "sha256": "43bb0f461f37b287a0d1a57154f8e3ac54d5699666a5e10ec07591515e06b68c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:b975752c0ceb002d:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
      "pid": 876192,
      "sha256": "2104078c8531e15b0b856e0671476c7a6d0d3aaea0b57ea987d0b72ae8efe483",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:45245beb5387db3b:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
      "pid": 876192,
      "sha256": "fe2a8b58fb8b8a568a1c0ff4c99bc243e517dcc084922c203501fce679bc3726",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:f8e337039436a75b:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
      "pid": 876192,
      "sha256": "e84a0fe2c2c6a7e1d10e4078cdaae094e1d5418c52d89408876149eddbab34a0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:28bfbc92890899e0:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
      "pid": 876192,
      "sha256": "c364ff79f2c8fb253dc3cf899c7ebee6434b0845dfd35bb460062e2c8ea15301",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:c606c4b3af94327f:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
      "pid": 876192,
      "sha256": "50c8fd80bf219414ae6129854c6d38bb0a8e0ab7f08bebbf9e465565878f89f3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:affe7193b4d1dcd1:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
      "pid": 876192,
      "sha256": "b23ff5389ad9ed04d81e5c644c5d002d5ff0be59b0ec13958e18282ad8faefec",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:e4c54975224682a6:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
      "pid": 876192,
      "sha256": "4ac9c4220eaf29c9c31b2e7211d373ce0ac002dca7287a82326cded48270a917",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "used:cc:27a7acad25c41f85:193180ea2612066f:05e780806641a877",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058",
      "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
      "pid": 876192,
      "sha256": "00bdc4bedc6940977b7809080c8598657c074c7db36a0b7c642000ffa0d84b61",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "cargo_pkg_name": "clear_on_drop",
      "cargo_pkg_version": "0.2.5",
      "context_path": "/tmp/native-trace-876092-1783997591859/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-876092-1783997591859/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 876192,
      "ppid": 876178,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U",
        "/target/debug/build/clear_on_drop-7166f128fe0bc058",
        "/target/debug/deps",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu",
        "/lib64"
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/rustc9yY08U/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1bkuety.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1bkuety.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1bkuety.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1bkuety.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1bkuety.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1bkuety.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1bkuety.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1bkuety.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/clear_on_drop-7166f128fe0bc058",
          "kind": "object",
          "path": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1bkuety.rcgu.o",
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
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1",
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
          "directory": "/lib/x86_64-linux-gnu",
          "kind": "dynamic_library",
          "path": "/lib/x86_64-linux-gnu/libc.so.6",
          "source": "link_trace"
        },
        {
          "directory": "/lib64",
          "kind": "dynamic_library",
          "path": "/lib64/ld-linux-x86-64.so.2",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o",
          "source": "link_trace"
        },
        {
          "directory": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
          "kind": "object",
          "path": "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o",
          "source": "link_trace"
        }
      ],
      "kind": "resolved_link",
      "map_path": "/tmp/native-trace-link-cc-876192-1783997594666523323.map",
      "pid": 876192,
      "ppid": 876178,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-876192-1783997594666523323.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
      "parsed_event_count": 188,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 189,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "-64.so.2 -pie -z now -z relro ...\n0.845   build-script-bu  876213 876131   0 /target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build\n0.846   riscv64-linux-g  876214 876213   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/10200110540939495728detect_compiler_family.c\n0.847   cc1              876215 876214   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/10200110540939495728detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 10200110540939495728detect_compiler_family.c -dumpbase-ext .c\n0.852   riscv64-linux-g  876216 876213   0 /usr/bin/riscv64-linux-gnu-gcc -?\n0.855   riscv64-linux-g  876217 876213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o -c src/hide.c\n0.857   cc1              876218 876217   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu src/hide.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ -dumpbase ea708c7824d36062-hide.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...\n0.862   as               876219 876217   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o /tmp/cccwZAqe.s\n0.864   riscv64-linux-g  876220 876213   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o\n0.881   riscv64-linux-g  876221 876213   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a\n0.898   rustc            876223 876131   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clear_on_drop --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=98d35d6d344c61aa ...\n1.933   runc             876233 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1494758271 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n1.937   exe              876240 876233   0 /proc/self/exe init\n1.963   etcdctl          876242 876233   0 /usr/local/bin/etcdctl endpoint health\n4.001   runc             876255 875058   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf --log-format json --systemd-cgroup kill --all 9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca6 9\n4.019   runc             876262 875058   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf --log-format json --systemd-cgroup delete 9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca6\n4.188   containerd-shim  876268 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca6 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf delete\n4.191   runc             876274 876268   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca --log-format json delete --force 9b01485dee6db146ec83e1143eecc4ea2d724fca55cc71a9c5972d574cf92ca6\n4.235   sh               876283 876280   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethf4ee02b\n4.236   ethtool          876284 876283   0 /usr/sbin/ethtool -i vethf4ee02b\n4.236   sed              876285 876283   0 /usr/bin/sed -n s/^driver: //p\n4.243   systemd-sysctl   876288 876280   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4ee02b --prefix=/net/ipv4/neigh/vethf4ee02b --prefix=/net/ipv6/conf/vethf4ee02b --prefix=/net/ipv6/neigh/vethf4ee02b\n7.318   cross            876291 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n7.320   rustc            876294 876291   0 /home/xmoe/.cargo/bin/rustc --print target-list\n7.327   rustc            876294 876291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n7.343   rustc            876306 876291   0 /home/xmoe/.cargo/bin/rustc -vV\n7.350   rustc            876306 876291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.361   cargo            876316 876291   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n7.368   cargo            876316 876291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n7.381   rustc            876325 876316   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.392   rustc            876327 876316   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n7.406   rustc            876331 876316   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n7.715   rustc            876336 876316   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n7.875   rustc            876338 876291   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n7.882   rustc            876338 876291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n7.896   docker           876350 876291   0 /usr/bin/docker --help\n7.912   docker           876362 876291   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n7.925   runc             876372 1599     0 /usr/bin/runc --version\n7.928   docker-init      876378 1599     0 /usr/bin/docker-init --version\n7.930   docker           876383 876291   0 /usr/bin/docker info -f {{.SecurityOptions}}\n7.943   runc             876394 1599     0 /usr/bin/runc --version\n7.947   docker-init      876400 1599     0 /usr/bin/docker-init --version\n7.973   rustup           876401 876291   0 /home/xmoe/.cargo/bin/rustup toolchain list\n7.980   rustup           876410 876291   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n8.010   rustup           876419 876291   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n8.040   uname            876428 876291   0 /usr/bin/uname -r\n8.060   docker           876429 876291   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n8.107   systemd-sysctl   876446 876444   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0c64c6f --prefix=/net/ipv4/neigh/veth0c64c6f --prefix=/net/ipv6/conf/veth0c64c6f --prefix=/net/ipv6/neigh/veth0c64c6f\n8.108   systemd-sysctl   876447 876445   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc477d29 --prefix=/net/ipv4/neigh/vethc477d29 --prefix=/net/ipv6/conf/vethc477d29 --prefix=/net/ipv6/neigh/vethc477d29\n8.119   containerd-shim  876467 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e start\n8.122   containerd-shim  876483 876467   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e -address /var/run/docker/containerd/containerd.sock\n8.127   runc             876496 876483   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a073 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a073 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a073 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e\n8.133   exe              876504 876496   0 /proc/self/exe init\n8.174   exe              876512 876496   0 /proc/1599/exe -exec-root=/var/run/docker 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e d7da31e8f8e1\n8.199   exe              876521 1599     0 /proc/self/exe /var/run/docker/netns/a0f64be15e3b all false\n8.252   runc             876540 876483   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a073 --log-format json --systemd-cgroup start 394afca4af64724e982a68928713e24131a93ea7d3b0ddfbc0226a7a0733da8e\n8.258   sh               876506 876483   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n8.259   cargo            876546 876506   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n8.273   cargo-native-tr  876546 876506   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n8.276   cargo            876547 876546   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n8.290   rustc            876548 876547   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.302   rustc            876550 876547   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.380   execsnoop        876554 876546   0 /usr/local/bin/execsnoop -t\n8.380   python3          876554 876546   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n9.518   16               876557 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n9.531   frpc             876557 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.137  cargo            876563 876546   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n10.148  rustc            876564 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n10.179  rustc            876571 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n10.179  rustc            876572 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n10.241  rustc            876585 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n10.794  rustc            876610 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=2c38527a274a239e ...\n10.829  cc               876624 876610   0 /tmp/native-trace-876546-1783997602154/shims/cc -m64 /target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n10.830  cc               876625 876624   0 /usr/bin/cc -m64 /target/debug/build/clear_on_drop-7166f128fe0bc058/rustcKkCa1Q/symbols.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.18j3f7y609igv7l6670rim542.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.23kjdu97q51jyrkgunk9dz1y0.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.3qdtlwkfsv8pxfu7pgisdg2f4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.4oz252zq6p52zuisj06uc81x3.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.528il3e30vqgroky3em5px1be.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.6nybrxbwmek3q90h4db80efj4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.82ls7wtqfqq99ymdo0rbj29x4.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.dd05bta6k21td2f0tybxyo4kd.1oobkxd.rcgu.o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058.7ya1c3lk38nue75ali3gmsp6r.1oobkxd.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n10.833  collect2         876626 876625   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccS1iR0s.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n10.834  ld.lld           876627 876626   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccS1iR0s.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/clear_on_drop-7166f128fe0bc058/build_script_build-7166f128fe0bc058 ...\n10.836  rust-lld         876627 876626   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccS1iR0s.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n10.897  build-script-bu  876645 876563   0 /target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build\n10.898  powerpc64le-lin  876646 876645   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/16168903583143736270detect_compiler_family.\n10.900  cc1              876647 876646   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/16168903583143736270detect_compiler_family. -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n10.903  powerpc64le-lin  876648 876645   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n10.905  powerpc64le-lin  876649 876645   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o -c src/hide.c\n10.907  cc1              876650 876649   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu src/hide.c -msecure-plt -quiet -dumpbase hide.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...\n10.915  as               876651 876649   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o /tmp/ccW1uU6i.s\n10.921  powerpc64le-lin  876652 876645   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/ea708c7824d36062-hide.o\n10.923  powerpc64le-lin  876653 876645   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/clear_on_drop-435d7708213f6542/out/libclear_on_drop.a\n10.928  rustc            876655 876563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clear_on_drop --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"nightly\", \"no_cc\")) -C metadata=b7d7c29f6545bab9 ...\n13.062  cross            876664 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n13.064  rustc            876667 876664   0 /home/xmoe/.cargo/bin/rustc --print target-list\n13.070  rustc            876667 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n13.085  rustc            876679 876664   0 /home/xmoe/.cargo/bin/rustc -vV\n13.092  rustc            876679 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.104  cargo            876689 876664   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n13.110  cargo            876689 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n13.123  rustc            876698 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.134  rustc            876700 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.150  rustc            876704 876689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n13.245  rustc            876708 876664   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n13.252  rustc            876708 876664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n13.266  docker           876720 876664   0 /usr/bin/docker --help\n13.282  docker           876731 876664   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n13.297  runc             876743 1599     0 /usr/bin/runc --version\n13.300  docker-init      876749 1599     0 /usr/bin/docker-init --version\n13.301  docker           876750 876664   0 /usr/bin/docker info -f {{.SecurityOptions}}\n13.315  runc             876763 1599     0 /usr/bin/runc --version\n13.319  docker-init      876769 1599     0 /usr/bin/docker-init --version\n13.345  rustup           876770 876664   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.352  rustup           876779 876664   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.384  rustup           876788 876664   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.414  uname            876797 876664   0 /usr/bin/uname -r\n13.434  docker           876798 876664   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n13.482  systemd-sysctl   876814 876812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8ebf659 --prefix=/net/ipv4/neigh/veth8ebf659 --prefix=/net/ipv6/conf/veth8ebf659 --prefix=/net/ipv6/neigh/veth8ebf659\n13.483  systemd-sysctl   876815 876813   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth88c0a91 --prefix=/net/ipv4/neigh/veth88c0a91 --prefix=/net/ipv6/conf/veth88c0a91 --prefix=/net/ipv6/neigh/veth88c0a91\n13.495  containerd-shim  876839 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 start\n13.498  containerd-shim  876854 876839   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 -address /var/run/docker/containerd/containerd.sock\n13.504  runc             876864 876854   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340\n13.509  exe              876872 876864   0 /proc/self/exe init\n13.548  exe              876881 876864   0 /proc/1599/exe -exec-root=/var/run/docker 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340 d7da31e8f8e1\n13.573  exe              876889 1599     0 /proc/self/exe /var/run/docker/netns/dc57e9676e3f all false\n13.625  runc             876908 876854   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea3961 --log-format json --systemd-cgroup start 484427cdec955c48ad444fe68a045d8806bc9c013ec79479ac501ea396100340\n13.630  sh               876875 876854   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.632  cargo            876914 876875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n13.645  cargo-native-tr  876914 876875   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n13.649  cargo            876915 876914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.662  rustc            876916 876915   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.674  rustc            876918 876915   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.720  execsnoop        876922 876914   0 /usr/local/bin/execsnoop -t\n13.721  python3          876922 876914   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.452  cargo            876925 876914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n15.465  rustc            876926 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.491  rustc            876936 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.492  rustc            876938 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de2844ba6b8ae918 ...\n15.492  rustc            876939 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"default\", \"example_generated\", \"rustc-dep-of-std\")) ...\n15.492  rustc            876940 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"avoid-default-panic\", \"encoding-raw\", \"encoding-rzcobs\", \"ip_in_core\", \"unstable-test\")) -C metadata=44a85da66c008e88 ...\n15.493  rustc            876941 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-2.0.12/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.493  rustc            876942 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/defmt-macros-1.0.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"unstable-test\")) -C metadata=c7338f2308d4bca1 ...\n15.520  cc               876967 876942   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/defmt-macros-fcfcc24ad5e74756/rustc464jBI/symbols.o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.build_script_build.ccd373c524451d1d-cgu.0. /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.70c1azqju59eihbinusj5hug8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n15.521  cc               876968 876967   0 /usr/bin/cc -m64 /target/debug/build/defmt-macros-fcfcc24ad5e74756/rustc464jBI/symbols.o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.build_script_build.ccd373c524451d1d-cgu.0. /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756.70c1azqju59eihbinusj5hug8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n15.523  collect2         876971 876968   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.525  ld.lld           876973 876971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/defmt-macros-fcfcc24ad5e74756/build_script_build-fcfcc24ad5e74756 ...\n15.526  rust-lld         876973 876971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbiX4Cq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.563  build-script-bu  877034 876925   0 /target/debug/build/defmt-macros-fcfcc24ad5e74756/build-script-build\n15.571  cc               877037 876940   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/defmt-88870500e9779679/rustcTOqJFU/symbols.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.055zk37rzu569svhsi8q0o5qp.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.0rpv6ef39zfh377kqpdwqt6g9.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.158lqt5y2x83b9zsise8h73nq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.3y17x9xbl4j2afwwz8a9jc45o.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.40r4tyzccbeuezyaizzylk2pn.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4bhsadt7ulwe6zi6wa5f8k4aj.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4kywhqz7rbi6dpvtowz2r7nmf.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4n65qxab0563utyx0d6yhcb0d.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.5ufph9gh2gjta1sd3skwekhym.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.6151boy9kvqnlg3qn0nvmpftq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.65m8e7svy2yd8r3ggvoecu0p7.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.69h4j683oo774547xc2muhfit.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.76diyyj2mrnynm3echznpxa7u.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.79h1339cdeg95ond51d88dcrh.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.876z0191hx79yv6qhd5o1wj6b.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.8g047khgm9nav92c2w6gjimps.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.999uopozu2buzwryf507eyhfy.06021wv.rcgu.o ...\n15.572  cc               877038 877037   0 /usr/bin/cc -m64 /target/debug/build/defmt-88870500e9779679/rustcTOqJFU/symbols.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.055zk37rzu569svhsi8q0o5qp.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.0rpv6ef39zfh377kqpdwqt6g9.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.158lqt5y2x83b9zsise8h73nq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.3y17x9xbl4j2afwwz8a9jc45o.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.40r4tyzccbeuezyaizzylk2pn.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4bhsadt7ulwe6zi6wa5f8k4aj.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4kywhqz7rbi6dpvtowz2r7nmf.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.4n65qxab0563utyx0d6yhcb0d.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.5ufph9gh2gjta1sd3skwekhym.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.6151boy9kvqnlg3qn0nvmpftq.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.65m8e7svy2yd8r3ggvoecu0p7.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.69h4j683oo774547xc2muhfit.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.76diyyj2mrnynm3echznpxa7u.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.79h1339cdeg95ond51d88dcrh.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.876z0191hx79yv6qhd5o1wj6b.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.8g047khgm9nav92c2w6gjimps.06021wv.rcgu.o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679.999uopozu2buzwryf507eyhfy.06021wv.rcgu.o ...\n15.575  collect2         877039 877038   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.576  ld.lld           877040 877039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/defmt-88870500e9779679/build_script_build-88870500e9779679 ...\n15.577  rust-lld         877040 877039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccePgDWH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.586  cc               877041 876936   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/proc-macro2-9397a4c89a8399e7/rustc2dgGS1/symbols.o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.0.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.1.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.4il8xo66kpq7xyp9ndwunhiok.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.587  cc               877042 877041   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-9397a4c89a8399e7/rustc2dgGS1/symbols.o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.0.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.build_script_build.1d5c82cd6b4704b6-cgu.1.r /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7.4il8xo66kpq7xyp9ndwunhiok.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.589  cc               877059 876941   0 /tmp/native-trace-876914-1783997607526/shims/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcrixLna/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.589  collect2         877060 877042   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.590  cc               877061 877059   0 /usr/bin/cc -m64 /target/debug/build/thiserror-c8cdc86597298e7b/rustcrixLna/symbols.o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.0.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.build_script_build.96a46619f53350b1-cgu.1.rcg /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b.9ynru7dq8x5rowdfp4zmwji47.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.590  ld.lld           877062 877060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-9397a4c89a8399e7/build_script_build-9397a4c89a8399e7 ...\n15.591  rust-lld         877062 877060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuYP0UY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.592  collect2         877063 877061   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.593  ld.lld           877064 877063   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/thiserror-c8cdc86597298e7b/build_script_build-c8cdc86597298e7b ...\n15.593  rust-lld         877064 877063   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjmXObp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.623  build-script-bu  877098 876925   0 /target/debug/build/defmt-88870500e9779679/build-script-build\n15.632  build-script-bu  877100 876925   0 /target/debug/build/thiserror-c8cdc86597298e7b/build-script-build\n15.633  build-script-bu  877102 876925   0 /target/debug/build/proc-macro2-9397a4c89a8399e7/build-script-build\n15.633  rustc            877103 877100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/thiserror-43e7d0657569a05a/out/probe build/probe.rs --target x86_64-unknown-linux-gnu\n15.634  rustc            877104 877102   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.642  rustc            877109 877102   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-c75d55102dcd3bb9/out/probe build/probe.rs --target x86_64-unknown-linux-gnu\n15.667  rustc            877113 877100   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.669  rustc            877115 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.849  rustc            877123 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.943  rustc            877139 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.100/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n15.991  runc             877144 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2279327366 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.996  exe              877151 877144   0 /proc/self/exe init\n16.007  rustc            877160 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-attr2-2.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --check-cfg cfg(docsrs,test) --check-cfg ...\n16.012  curl             877153 877144   0 /usr/bin/curl -f http://localhost:9091/healthz\n16.115  cc               877169 877160   0 /tmp/native-trace-876914-1783997607526/shims/cc -Wl,--version-script=/target/debug/deps/rustc3FdlPW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc3FdlPW/symbols.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.1.rcgu.o /target/debug/deps/rustc3FdlPW/rmeta.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.55sq3uw3glcy6pozjsuixo9q6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-cd059401c8285246.rlib /target/debug/deps/libproc_macro2-02759104fca4896a.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n16.115  cc               877170 877169   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc3FdlPW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc3FdlPW/symbols.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.proc_macro_error_attr2.5b6917e80a6623bc-cgu.1.rcgu.o /target/debug/deps/rustc3FdlPW/rmeta.o /target/debug/deps/proc_macro_error_attr2-9aa77094cc12b522.55sq3uw3glcy6pozjsuixo9q6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-cd059401c8285246.rlib /target/debug/deps/libproc_macro2-02759104fca4896a.rlib /target/debug/deps/libunicode_ident-a00e74d44458319e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n16.118  collect2         877171 877170   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc3FdlPW/raw-dylibs ...\n16.119  ld.lld           877172 877171   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc3FdlPW/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.120  rust-lld         877172 877171   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3eiQqE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr2-9aa77094cc12b522.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.370  rustc            877192 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error2-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=unexpected_cfgs --allow=clippy::module_name_repetitions --check-cfg cfg(run_ui_tests) --cfg ...\n17.898  rustc            877217 876925   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-2.0.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n"
    },
    {
      "argv": [
        "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876213,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
      "pid": 876213,
      "ppid": 876131,
      "root_cargo_pid": 876131,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-E",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/10200110540939495728detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876213,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 876214,
      "ppid": 876213,
      "root_cargo_pid": 876131,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-E",
        "-quiet",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/10200110540939495728detect_compiler_family.c",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-dumpbase",
        "10200110540939495728detect_compiler_family.c",
        "-dumpbase-ext",
        ".c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876213,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 876215,
      "ppid": 876214,
      "root_cargo_pid": 876131,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876213,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 876216,
      "ppid": 876213,
      "root_cargo_pid": 876131,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-Wall",
        "-Wextra",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o",
        "-c",
        "src/hide.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876213,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 876217,
      "ppid": 876213,
      "root_cargo_pid": 876131,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "src/hide.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/",
        "-dumpbase",
        "ea708c7824d36062-hide.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-g",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 876213,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 876218,
      "ppid": 876217,
      "root_cargo_pid": 876131,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o",
        "/tmp/cccwZAqe.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876213,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 876219,
      "ppid": 876217,
      "root_cargo_pid": 876131,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "cqD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/ea708c7824d36062-hide.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876213,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 876220,
      "ppid": 876213,
      "root_cargo_pid": 876131,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "sD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/clear_on_drop-6e4f24b7f5149792/out/libclear_on_drop.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 876213,
      "build_script_target_dir": "clear_on_drop-7166f128fe0bc058",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 876221,
      "ppid": 876213,
      "root_cargo_pid": 876131,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "clear_on_drop",
      "cwd": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "event_id": "bsrun:baafdddc65e4bf87:0c2e38447dfb082e:022ca268ecfe4b96",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/clear_on_drop-7166f128fe0bc058/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
      "out_dir": "/target/debug/build/clear_on_drop-7166f128fe0bc058/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
      "success": true,
      "target": null,
      "version": "0.2.5",
      "_owner": {
        "crate": "clear_on_drop",
        "version": "0.2.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5#clear_on_drop@0.2.5",
        "manifest_dir": "/tmp/crate-build-riscv64-_apc1xhw/src/clear_on_drop-0.2.5",
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
