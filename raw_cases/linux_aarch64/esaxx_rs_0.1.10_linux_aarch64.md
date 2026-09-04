# `esaxx-rs` `0.1.10`

Platform: Linux aarch64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a`

Owner: `esaxx-rs` `0.1.10`

### Source files

* `/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10/src/esaxx.cpp`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "src/esaxx.cpp",
    "-quiet",
    "-dumpbase",
    "esaxx.cpp",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "..."
  ],
  "src": "src/esaxx.cpp",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 283187,
  "ppid": 283158,
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 282276,
  "build_script_root_pid": 283156,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
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
    "cq",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 283452,
  "ppid": 283156,
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 282276,
  "build_script_root_pid": 283156,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
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
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "workspace_root": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.1",
      "name": "aho-corasick",
      "version": "1.1.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#anes@0.1.6",
      "name": "anes",
      "version": "0.1.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#anstyle@1.0.4",
      "name": "anstyle",
      "version": "1.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
      "name": "autocfg",
      "version": "1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.4.0",
      "name": "bitflags",
      "version": "2.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
      "name": "bumpalo",
      "version": "3.14.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
      "name": "cast",
      "version": "0.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
      "name": "cc",
      "version": "1.0.83",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.1",
      "name": "ciborium",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-io@0.2.1",
      "name": "ciborium-io",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-ll@0.2.1",
      "name": "ciborium-ll",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@4.4.6",
      "name": "clap",
      "version": "4.4.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_builder@4.4.6",
      "name": "clap_builder",
      "version": "4.4.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_lex@0.5.1",
      "name": "clap_lex",
      "version": "0.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.5.1",
      "name": "criterion",
      "version": "0.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.5.0",
      "name": "criterion-plot",
      "version": "0.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.3",
      "name": "crossbeam-deque",
      "version": "0.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.15",
      "name": "crossbeam-epoch",
      "version": "0.9.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.16",
      "name": "crossbeam-utils",
      "version": "0.8.16",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.9.0",
      "name": "either",
      "version": "1.9.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.4",
      "name": "errno",
      "version": "0.3.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno-dragonfly@0.1.2",
      "name": "errno-dragonfly",
      "version": "0.1.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
      "name": "esaxx-rs",
      "version": "0.1.10",
      "manifest_path": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.2",
      "name": "half",
      "version": "1.8.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.3.3",
      "name": "hermit-abi",
      "version": "0.3.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#is-terminal@0.4.9",
      "name": "is-terminal",
      "version": "0.4.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
      "name": "itertools",
      "version": "0.10.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.9",
      "name": "itoa",
      "version": "1.0.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.64",
      "name": "js-sys",
      "version": "0.3.64",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
      "name": "libc",
      "version": "0.2.148",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.8",
      "name": "linux-raw-sys",
      "version": "0.4.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
      "name": "log",
      "version": "0.4.20",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.6.4",
      "name": "memchr",
      "version": "2.6.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.0",
      "name": "memoffset",
      "version": "0.9.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.16",
      "name": "num-traits",
      "version": "0.2.16",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.18.0",
      "name": "once_cell",
      "version": "1.18.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.3",
      "name": "oorandom",
      "version": "11.1.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.5",
      "name": "plotters",
      "version": "0.3.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.5",
      "name": "plotters-backend",
      "version": "0.3.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.5",
      "name": "plotters-svg",
      "version": "0.3.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.67",
      "name": "proc-macro2",
      "version": "1.0.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.33",
      "name": "quote",
      "version": "1.0.33",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.8.0",
      "name": "rayon",
      "version": "1.8.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.12.0",
      "name": "rayon-core",
      "version": "1.12.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.9.6",
      "name": "regex",
      "version": "1.9.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.3.9",
      "name": "regex-automata",
      "version": "0.3.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.7.5",
      "name": "regex-syntax",
      "version": "0.7.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.17",
      "name": "rustix",
      "version": "0.38.17",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.15",
      "name": "ryu",
      "version": "1.0.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
      "name": "same-file",
      "version": "1.0.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
      "name": "scopeguard",
      "version": "1.2.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.188",
      "name": "serde",
      "version": "1.0.188",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.188",
      "name": "serde_derive",
      "version": "1.0.188",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.107",
      "name": "serde_json",
      "version": "1.0.107",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.37",
      "name": "syn",
      "version": "2.0.37",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
      "name": "tinytemplate",
      "version": "1.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
      "name": "unicode-ident",
      "version": "1.0.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.4.0",
      "name": "walkdir",
      "version": "2.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.87",
      "name": "wasm-bindgen",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.87",
      "name": "wasm-bindgen-backend",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.87",
      "name": "wasm-bindgen-macro",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.87",
      "name": "wasm-bindgen-macro-support",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.87",
      "name": "wasm-bindgen-shared",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.64",
      "name": "web-sys",
      "version": "0.3.64",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
      "name": "winapi-util",
      "version": "0.1.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
      "name": "winapi-x86_64-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.48.0",
      "name": "windows-sys",
      "version": "0.48.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.48.5",
      "name": "windows-targets",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.48.5",
      "name": "windows_aarch64_gnullvm",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.48.5",
      "name": "windows_aarch64_msvc",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.48.5",
      "name": "windows_i686_gnu",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.48.5",
      "name": "windows_i686_msvc",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.48.5",
      "name": "windows_x86_64_gnu",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.48.5",
      "name": "windows_x86_64_gnullvm",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
      "name": "windows_x86_64_msvc",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5"
    }
  ],
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "exit_code": 0,
  "kind": "exec",
  "pid": 282423,
  "ppid": 282309,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "used:cc:018871c2723b82d0:77a9563caf473fbf:3e55491827d9b9d7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "path": "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
  "pid": 282423,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "used:cc:018871c2723b82d0:ffbb52dee619e4f7:3e55491827d9b9d7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
  "pid": 282423,
  "sha256": "0084afdb6795e37eed7874e70d007107abbf84e8be21d962ee5ecd567f7f3a7d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "used:cc:018871c2723b82d0:6cd16efd838c1c1f:3e55491827d9b9d7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
  "pid": 282423,
  "sha256": "42de4168bfa675af3241b604230d4f16a1a324228feaa59aab5a71ca5f3153b5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "used:cc:018871c2723b82d0:a759f47395afa91f:3e55491827d9b9d7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
  "pid": 282423,
  "sha256": "e4901fc88fe2f91f7fad9706b9a4cdff37a573f9a087101074a5b4e6e11154c0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
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
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "context_path": "/tmp/native-trace-281850-1783993689305/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-281850-1783993689305/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 282423,
  "ppid": 282309,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
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
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/libc-8a12625678126bc3/rustc16zksV",
    "/target/debug/build/libc-8a12625678126bc3",
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
      "directory": "/target/debug/build/libc-8a12625678126bc3/rustc16zksV",
      "kind": "object",
      "path": "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a12625678126bc3",
      "kind": "object",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a12625678126bc3",
      "kind": "object",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a12625678126bc3",
      "kind": "object",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-282423-1783993701489242245.map",
  "pid": 282423,
  "ppid": 282309,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-282423-1783993701489242245.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 283063,
  "ppid": 283015,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:f914cd700233e190:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
  "pid": 283063,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:a4be52e84de5233d:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
  "pid": 283063,
  "sha256": "06e0a7fe93d0fe65e5e0b5b8ad71f189c5e0695f4c9f1d30be96f1caf31a1c77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:be176e8d076b30fd:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
  "pid": 283063,
  "sha256": "bb1ffe7aed9b52d038e9fa57a755815aed7151580c02d8e02bad405bd62845f0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:a3b7896a178c6ae0:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
  "pid": 283063,
  "sha256": "c0430de796a0cf9aee624b66f5bc83c41675b5fcec79a2b75a25a8d7391ceaf7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:4a1eb1f091eeab47:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
  "pid": 283063,
  "sha256": "3259e7258d9a3108a4008ab18e1af565e3c024066beeffed659312af39fc14d3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:df680ed573768aad:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
  "pid": 283063,
  "sha256": "5e2e1d5101126099523f7656a84a3b5d2bc4b3aff449f8afe6c967124cfec5fa",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:a62329485a68f5ba:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
  "pid": 283063,
  "sha256": "78d8c7ad64fc95fdd41c10e27aa710a54e5371954f00932f748e1da68c4d7cdb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:b95aa416170c8e2b:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
  "pid": 283063,
  "sha256": "cd9ac12f7fe957318ba5a0db37e53c0c8333bc25a9fef1eb9b4e9199e67b297f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:4e780f6907409d1b:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
  "pid": 283063,
  "sha256": "eb8164bb68e398317f4df1538373ede98e2ae7282836aa0d9bc90da23ffb5965",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:6fd5e83716b2b202:2c6491785c43daac:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
  "pid": 283063,
  "sha256": "b5d70f58226e48020baead62f879a65339ae344afe36358deccd208d1c4137a6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
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
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "context_path": "/tmp/native-trace-281850-1783993689305/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-281850-1783993689305/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 283063,
  "ppid": 283015,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
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
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.1.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-283063-1783993709076396264.map",
  "pid": 283063,
  "ppid": 283015,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-283063-1783993709076396264.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

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

#### Record 25

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 422,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 423,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "wn-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n23.270  cc               284378 284377   0 /usr/bin/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcxqQSD6/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n23.370  collect2         284379 284378   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfh87jv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n23.389  ld.lld           284390 284379   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfh87jv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3 ...\n23.398  rust-lld         284390 284379   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfh87jv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n23.636  build-script-bu  284425 284300   0 /target/debug/build/libc-8a12625678126bc3/build-script-build\n23.639  rustc            284426 284425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n23.682  rustc            284431 284300   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n23.840  runc             284435 281624   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6 --log-format json --systemd-cgroup kill --all dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85c 9\n23.910  runc             284441 281624   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6 --log-format json --systemd-cgroup delete dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85c\n24.165  containerd-shim  284450 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6 delete\n24.170  runc             284459 284450   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85 --log-format json delete --force dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85c\n24.305  powerpc64le-lin  284466 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n24.329  cc1plus          284467 284466   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n24.363  systemd-sysctl   284469 284468   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc8ccc1a --prefix=/net/ipv4/neigh/vethc8ccc1a --prefix=/net/ipv6/conf/vethc8ccc1a --prefix=/net/ipv6/neigh/vethc8ccc1a\n24.452  as               284472 274506   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/3ac6d140080a8125-version_builder.o /tmp/ccUXCxG5.s\n24.537  as               284473 244909   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/fb8935d9b2e862b1-db_impl.o /tmp/ccW68F9I.s\n24.553  rustc            284478 284250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=18831150b9e7f196 ...\n24.979  rustc            284487 284300   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=18831150b9e7f196 ...\n25.261  aarch64-linux-g  284500 277046   0 /usr/bin/aarch64-linux-gnu-gcc /target/aarch64-unknown-linux-gnu/debug/deps/rustcfr72S2/symbols.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.00r9eycqmv6875teof0nzfsfs.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.03unpa094f0624y346we3ct8t.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.04o6ulm54kkww12hyjjbnna91.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.05u83lh5wm60nxef5na5033ky.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.07gsl84shgfie1g4ih4irhdmr.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.08wxndnwuhx76g3xd8iqxn6dq.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0d5drd91i7g641erc3yld0ca1.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0e0clpwkeot615wigqii7nk2u.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0lbkagnyle9bftb5rlyupzc38.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0r8rbj3ejwtaxvyrrtwhp1yjz.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0rb1kipsp8r6fzb4aydt8qrxx.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0sr11atuve2ds0cz1p6ihvs7l.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.12c7tz1j6hb38sip2yf229soo.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.16jeffe7l9zmd428916qkm00g.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.16zeke45n5a7qqrm94ohojyri.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.17v1jnqsgnzqkpmxxo4rroj84.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.18bxxafzl2bubxrr3yxecek15.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.18g9wkqghlpsot0p3lmsh16mg.0xwyj3u.rcgu.o ...\n25.279  collect2         284502 284500   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFRWL.res --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux --fix-cortex-a53-843419 -pie -z now -z ...\n25.288  ld               284503 284502   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFRWL.res --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux --fix-cortex-a53-843419 -pie -z now -z ...\n25.776  runc             284525 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process851379402 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n26.026  exe              284554 284525   0 /proc/self/exe init\n26.067  curl             284556 284525   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n26.265  rustc            284577 284250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n26.376  rustc            284583 284300   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n26.521  powerpc64le-lin  284593 229287   0 \n26.521  cc1plus          284594 284593   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n26.545  cc               284611 284583   0 /tmp/native-trace-283957-1783993716140/shims/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcoMtnjY/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.056l8e5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n26.548  cc               284614 284611   0 /usr/bin/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcoMtnjY/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.056l8e5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n26.555  collect2         284615 284614   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjUp0Yn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n26.557  cc               284613 284304   0 /tmp/native-trace-279094-1783993664521/shims/cc -Wl,--version-script=/target/debug/deps/rustcG6c7Ji/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcG6c7Ji/symbols.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.00.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.01.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.02.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.03.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.04.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.05.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.06.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.07.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.08.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.09.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.10.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.11.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.12.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.13.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.14.rcgu.o ...\n26.561  cc               284617 284613   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcG6c7Ji/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcG6c7Ji/symbols.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.00.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.01.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.02.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.03.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.04.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.05.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.06.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.07.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.08.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.09.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.10.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.11.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.12.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.13.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.14.rcgu.o ...\n26.561  ld.lld           284616 284615   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjUp0Yn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c ...\n26.569  collect2         284618 284617   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclVVPfD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-2eed6651630996d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcG6c7Ji/raw-dylibs ...\n26.572  rust-lld         284616 284615   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjUp0Yn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n26.572  ld.lld           284619 284618   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclVVPfD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-2eed6651630996d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcG6c7Ji/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n26.576  rust-lld         284619 284618   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclVVPfD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-2eed6651630996d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n26.599  cc               284612 284577   0 /tmp/native-trace-283640-1783993713810/shims/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcPh9bmV/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.010locg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n26.601  cc               284637 284612   0 /usr/bin/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcPh9bmV/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.010locg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n26.608  collect2         284638 284637   0 \n26.612  ld.lld           284639 284638   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfT3uX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c ...\n26.612  rust-lld         284639 284638   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfT3uX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n26.792  build-script-bu  284676 284300   0 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build\n26.796  powerpc64le-lin  284678 284676   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src -Wall -Wextra -std=c++11 -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -c src/esaxx.cpp\n26.799  cc1plus          284679 284678   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I src -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE src/esaxx.cpp -msecure-plt -quiet -dumpbase esaxx.cpp -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -gdwarf-4 -O0 -Wall -Wextra ...\n26.810  as               284680 280108   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/3ac6d140080a8125-write_thread.o /tmp/ccwCtlBC.s\n26.820  as               284681 281760   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/676314c7dcdc695c-env_encryption.o /tmp/ccVBM2Sx.s\n26.846  build-script-bu  284683 284250   0 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build\n26.851  riscv64-linux-g  284685 284683   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -mcmodel=medany -I src -Wall -Wextra -std=c++11 -o /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o -c src/esaxx.cpp\n26.855  cc1plus          284686 284685   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE src/esaxx.cpp -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/ -dumpbase esaxx.cpp -dumpbase-ext .cpp -march=rv64gc -mabi=lp64d -mcmodel=medany ...\n27.016  rustc            284691 279808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stdweb_internal_macros --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stdweb-internal-macros-0.2.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n27.016  rustc            284690 279808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stdweb_derive --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stdweb-derive-0.5.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n27.070  riscv64-linux-g  284698 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n27.078  cc1plus          284699 284698   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n27.091  as               284700 280215   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-trim_history_scheduler.o /tmp/ccGL5G5Z.s\n27.416  as               284705 284685   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o /tmp/ccGrWgJ4.s\n27.454  riscv64-linux-g  284706 284683   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o\n27.482  as               284707 284678   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I src -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o /tmp/ccJ5cyhb.s\n27.518  powerpc64le-lin  284710 284676   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o\n27.553  powerpc64le-lin  284711 284676   0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a\n27.567  rustc            284714 284300   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name esaxx_rs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n27.594  aarch64-linux-g  284715 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n27.606  cc1plus          284721 284715   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n27.610  aarch64-linux-g  284720 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n27.613  cc1plus          284722 284720   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n27.737  riscv64-linux-g  284728 284683   0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a\n27.819  cc               284730 284690   0 /tmp/native-trace-279094-1783993664521/shims/cc -Wl,--version-script=/target/debug/deps/rustcTJKp6L/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTJKp6L/symbols.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.0.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.1.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.2.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.3.rcgu.o /target/debug/deps/rustcTJKp6L/rmeta.o /target/debug/deps/stdweb_derive-672a03522bab9858.0htv00vx0bhk7szwtxlazw85e.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-c27db84f59d4ae56.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n27.823  cc               284731 284730   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcTJKp6L/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTJKp6L/symbols.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.0.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.1.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.2.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.3.rcgu.o /target/debug/deps/rustcTJKp6L/rmeta.o /target/debug/deps/stdweb_derive-672a03522bab9858.0htv00vx0bhk7szwtxlazw85e.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-c27db84f59d4ae56.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n27.827  collect2         284732 284731   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7gscYc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libstdweb_derive-672a03522bab9858.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTJKp6L/raw-dylibs ...\n27.834  ld.lld           284733 284732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7gscYc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libstdweb_derive-672a03522bab9858.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTJKp6L/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n27.843  rust-lld         284733 284732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7gscYc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libstdweb_derive-672a03522bab9858.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n27.891  rustc            284736 284250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name esaxx_rs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n28.181  runc             284813 283788   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2de --log-format json --systemd-cgroup kill --all ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442b 9\n28.199  runc             284821 283788   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2de --log-format json --systemd-cgroup delete ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442b\n28.212  containerd-shim  284828 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2de delete\n28.220  runc             284839 284828   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442 --log-format json delete --force ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442b\n28.292  sh               284859 284853   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth6d59671\n28.292  sed              284865 284859   0 /usr/bin/sed -n s/^driver: //p\n28.300  ethtool          284864 284859   0 /usr/sbin/ethtool -i veth6d59671\n28.310  systemd-sysctl   284880 284853   0 \n28.400  runc             284903 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process3885722702 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n28.411  exe              284911 284903   0 /proc/self/exe init\n28.430  curl             284914 284903   0 /usr/bin/curl -f http://localhost:9091/healthz\n28.573  runc             284942 283264   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a57 --log-format json --systemd-cgroup kill --all 60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2d 9\n28.587  runc             284949 283264   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a57 --log-format json --systemd-cgroup delete 60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2d\n28.600  containerd-shim  284955 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a57 delete\n28.604  runc             284961 284955   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2 --log-format json delete --force 60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2d\n28.627  riscv64-linux-g  284967 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n28.632  cc               284968 284691   0 /tmp/native-trace-279094-1783993664521/shims/cc -Wl,--version-script=/target/debug/deps/rustcDc5ZvR/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcDc5ZvR/symbols.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.0.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.1.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.2.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.3.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.4.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.5.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.6.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.7.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.8.rcgu.o /target/debug/deps/rustcDc5ZvR/rmeta.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.91mzy2jb87iqcicyfj8osa4hp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsha1-e3a4ab61b7d8390a.rlib /target/debug/deps/libsha1_smol-4d14c8b23817f26e.rlib ...\n28.634  cc               284970 284968   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcDc5ZvR/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcDc5ZvR/symbols.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.0.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.1.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.2.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.3.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.4.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.5.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.6.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.7.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.8.rcgu.o /target/debug/deps/rustcDc5ZvR/rmeta.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.91mzy2jb87iqcicyfj8osa4hp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsha1-e3a4ab61b7d8390a.rlib /target/debug/deps/libsha1_smol-4d14c8b23817f26e.rlib ...\n28.637  cc1plus          284969 284967   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n28.640  collect2         284972 284970   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfTRkj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libstdweb_internal_macros-b05f4def71556e89.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcDc5ZvR/raw-dylibs ...\n28.642  ld.lld           284973 284972   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfTRkj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libstdweb_internal_macros-b05f4def71556e89.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcDc5ZvR/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n28.644  systemd-sysctl   284974 284921   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb1a6e24 --prefix=/net/ipv4/neigh/vethb1a6e24 --prefix=/net/ipv6/conf/vethb1a6e24 --prefix=/net/ipv6/neigh/vethb1a6e24\n28.677  rust-lld         284973 284972   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfTRkj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libstdweb_internal_macros-b05f4def71556e89.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n28.879  aarch64-linux-g  285014 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n28.892  cc1plus          285015 285014   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n29.007  rustc            285035 279808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stdweb --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"serde_json\" ...\n29.082  16               285039 1        0 \n29.116  frpc             285039 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg /usr/local/bin/frpc -c /etc/frp/frpc.toml\n29.162  as               285043 275729   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-memtable.o /tmp/ccj0Y6Hx.s\n29.280  as               285044 271948   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-forward_iterator.o /tmp/ccCGgcID.s\n29.888  as               285046 272511   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-internal_stats.o /tmp/ccq3GIoe.s\n29.898  powerpc64le-lin  285045 278490   0 /usr/bin/powerpc64le-linux-gnu-gcc -m64 /target/powerpc64le-unknown-linux-gnu/debug/deps/rustc9CiLv0/symbols.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.018rkip0j4fw6w68mbnw1m28e.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.02xar1dge2qgjfm7ojjrp2mwj.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.094nqzoy52cliyyejrb0pptzw.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0axtmd151x2gxji5hgaq952fu.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0eham50qb6sadz3naptnvenvu.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0ejw0seg5qcta6jrsus80sslq.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0ew4u3oh428h4oiqaofccy56u.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0i3nl5nntn96u5y8hsln2wgp5.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0jxb4krgel0ba9ds61gcjwdys.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0lj497v4qk9aovyppwzs7dpel.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0ro3wg5lkmn9x02zkchrllnxb.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0us3t2aaeumy5uk4q0o97m273.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0vu2sjb9clr4slpkbzylai5zc.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0w0j1l26uxszpkq86jb8uylok.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0xwz4p4fto6rpnhb41v34osp4.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.10rwmdknl4mm7in9vjvkox1u5.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.12m7jtsy8uxaf7qn5aavxw02l.19sy07c.rcgu.o ...\n29.917  collect2         285047 285045   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKjJQY.res --sysroot=/ --build-id --eh-frame-hdr -m elf64lppc --hash-style=gnu --as-needed -dynamic-linker /lib64/ld64.so.2 -pie -z now -z relro -o ...\n29.923  ld               285048 285047   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKjJQY.res --sysroot=/ --build-id --eh-frame-hdr -m elf64lppc --hash-style=gnu --as-needed -dynamic-linker /lib64/ld64.so.2 -pie -z now -z relro -o ...\n30.088  as               285049 279694   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/3ac6d140080a8125-write_stall_stats.o /tmp/ccLQGnHk.s\n30.400  as               285050 284593   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/fe29f3d3b3c15862-wide_column_serialization /tmp/cc984JNM.s\n30.435  as               285051 280041   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-transaction_log_impl.o /tmp/ccgRzrSA.s\n30.996  as               285052 284125   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-wal_edit.o /tmp/ccUvaHKn.s\n31.036  aarch64-linux-g  285053 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n31.047  cc1plus          285054 285053   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.080  powerpc64le-lin  285055 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.091  cc1plus          285057 285055   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.101  powerpc64le-lin  285056 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.110  as               285060 271975   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/3ac6d140080a8125-repair.o /tmp/ccdfhuuF.s\n31.128  powerpc64le-lin  285058 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.133  powerpc64le-lin  285061 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.146  cc1plus          285063 285061   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.219  cc1plus          285059 285056   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.240  as               285065 281129   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/676314c7dcdc695c-env.o /tmp/ccw8HX3Q.s\n31.245  powerpc64le-lin  285064 229287   0 /usr/bin/powerpc64le-linux-gnu-g++  -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.252  cc1plus          285066 285064   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.356  as               285067 239340   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/fb8935d9b2e862b1-db_impl.o /tmp/ccIi9GvW.s\n31.573  cc1plus          285062 285058   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.898  as               285068 278751   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-table_cache.o /tmp/ccA6JFa6.s\n32.195  runc             285069 272235   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a --log-format json --systemd-cgroup kill --all 152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e7 9\n32.253  riscv64-linux-g  285075 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n32.257  cc1plus          285076 285075   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n32.301  as               285077 273395   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-memtable_list.o /tmp/ccOUyD0T.s\n32.381  runc             285078 272235   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a --log-format json --systemd-cgroup delete 152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e7\n32.457  as               285084 280902   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-version_edit.o /tmp/ccI8nO5W.s\n32.475  containerd-shim  285085 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a delete\n32.481  runc             285092 285085   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e --log-format json delete --force 152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e7\n32.542  systemd-sysctl   285098 285097   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6f4c4fa --prefix=/net/ipv4/neigh/veth6f4c4fa --prefix=/net/ipv6/conf/veth6f4c4fa --prefix=/net/ipv6/neigh/veth6f4c4fa\n32.565  aarch64-linux-g  285099 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n32.576  cc1plus          285101 285099   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n32.605  riscv64-linux-g  285102 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n"
}
```

#### Record 26

```json
{
  "argv": [
    "/target/debug/build/libc-8a12625678126bc3/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 282509,
  "build_script_target_dir": "libc-8a12625678126bc3",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
  "pid": 282509,
  "ppid": 282276,
  "root_cargo_pid": 282276,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_build_script_out_dir": "/target/debug/build/libc-8a12625678126bc3/out"
}
```

#### Record 27

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 282509,
  "build_script_target_dir": "libc-8a12625678126bc3",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 282510,
  "ppid": 282509,
  "root_cargo_pid": 282276,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_build_script_out_dir": "/target/debug/build/libc-8a12625678126bc3/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 28

```json
{
  "argv": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 283156,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
  "pid": 283156,
  "ppid": 282276,
  "root_cargo_pid": 282276,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out"
}
```

#### Record 29

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
    "-c",
    "src/esaxx.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 283156,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-g++",
  "pid": 283158,
  "ppid": 283156,
  "root_cargo_pid": 282276,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "src/esaxx.cpp",
    "-quiet",
    "-dumpbase",
    "esaxx.cpp",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 283156,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "pid": 283187,
  "ppid": 283158,
  "root_cargo_pid": 282276,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 31

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-I",
    "src",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
    "/tmp/ccC3S2vg.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 283156,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 283433,
  "ppid": 283158,
  "root_cargo_pid": 282276,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 32

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cq",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 283156,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 283452,
  "ppid": 283156,
  "root_cargo_pid": 282276,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "s",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 283156,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 283464,
  "ppid": 283156,
  "root_cargo_pid": 282276,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "bsrun:2ebdc03c5a2acb3f:d2cbd9eb7f36ae5e:094a542f6f4ffc0f",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "out_dir": "/target/debug/build/libc-8a12625678126bc3/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
  "success": true,
  "target": null,
  "version": "0.2.148",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
    "source": "cwd_prefix"
  }
}
```

#### Record 35

```json
{
  "crate": "esaxx-rs",
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "event_id": "bsrun:aec4a6297808479c:58c8166d76a53504:5698292d0e3f3d21",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
  "success": true,
  "target": null,
  "version": "0.1.10",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 282509,
  "build_script_target_dir": "libc-8a12625678126bc3",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 282510,
  "ppid": 282509,
  "root_cargo_pid": 282276,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 37

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "src/esaxx.cpp",
    "-quiet",
    "-dumpbase",
    "esaxx.cpp",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "..."
  ],
  "src": "src/esaxx.cpp",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 283187,
  "ppid": 283158,
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 282276,
  "build_script_root_pid": 283156,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 38

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cq",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 283452,
  "ppid": 283156,
  "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 282276,
  "build_script_root_pid": 283156,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:48:57.431905+00:00",
  "crate": "esaxx-rs",
  "version": "0.1.10",
  "architecture": "aarch64",
  "duration_seconds": 55.17764875525609,
  "trace_record_count": 35,
  "trace_owner_summary": {
    "owner_package_count": 78,
    "owner_packages": [
      {
        "crate": "winapi-x86_64-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro-support",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87/Cargo.toml"
      },
      {
        "crate": "winapi-i686-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_gnullvm",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnullvm",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-backend",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-shared",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5/Cargo.toml"
      },
      {
        "crate": "crossbeam-epoch",
        "version": "0.9.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15/Cargo.toml"
      },
      {
        "crate": "crossbeam-utils",
        "version": "0.8.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.16",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16/Cargo.toml"
      },
      {
        "crate": "plotters-backend",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5/Cargo.toml"
      },
      {
        "crate": "crossbeam-deque",
        "version": "0.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3/Cargo.toml"
      },
      {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno-dragonfly@0.1.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2/Cargo.toml"
      },
      {
        "crate": "criterion-plot",
        "version": "0.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.188",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.188",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml"
      },
      {
        "crate": "linux-raw-sys",
        "version": "0.4.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1/Cargo.toml"
      },
      {
        "crate": "clap_builder",
        "version": "4.4.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_builder@4.4.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6/Cargo.toml"
      },
      {
        "crate": "plotters-svg",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.67",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.7.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.7.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.107",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.107",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107/Cargo.toml"
      },
      {
        "crate": "tinytemplate",
        "version": "1.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.48.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.48.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0/Cargo.toml"
      },
      {
        "crate": "ciborium-io",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-io@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1/Cargo.toml"
      },
      {
        "crate": "ciborium-ll",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-ll@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1/Cargo.toml"
      },
      {
        "crate": "is-terminal",
        "version": "0.4.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#is-terminal@0.4.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9/Cargo.toml"
      },
      {
        "crate": "num-traits",
        "version": "0.2.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.16",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16/Cargo.toml"
      },
      {
        "crate": "rayon-core",
        "version": "1.12.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.12.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6/Cargo.toml"
      },
      {
        "crate": "hermit-abi",
        "version": "0.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.3.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3/Cargo.toml"
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
        "version": "1.18.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.18.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0/Cargo.toml"
      },
      {
        "crate": "scopeguard",
        "version": "1.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml"
      },
      {
        "crate": "criterion",
        "version": "0.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1/Cargo.toml"
      },
      {
        "crate": "memoffset",
        "version": "0.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0/Cargo.toml"
      },
      {
        "crate": "oorandom",
        "version": "11.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3/Cargo.toml"
      },
      {
        "crate": "same-file",
        "version": "1.0.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "2.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0/Cargo.toml"
      },
      {
        "crate": "bumpalo",
        "version": "3.14.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml"
      },
      {
        "crate": "ciborium",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1/Cargo.toml"
      },
      {
        "crate": "clap_lex",
        "version": "0.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_lex@0.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1/Cargo.toml"
      },
      {
        "crate": "plotters",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5/Cargo.toml"
      },
      {
        "crate": "rustix",
        "version": "0.38.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.17",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17/Cargo.toml"
      },
      {
        "crate": "web-sys",
        "version": "0.3.64",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.64",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64/Cargo.toml"
      },
      {
        "crate": "anstyle",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#anstyle@1.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml"
      },
      {
        "crate": "js-sys",
        "version": "0.3.64",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.64",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.188",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.188",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188/Cargo.toml"
      },
      {
        "crate": "walkdir",
        "version": "2.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml"
      },
      {
        "crate": "either",
        "version": "1.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.9.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.6.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.6.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.33",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.33",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "errno",
        "version": "0.3.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4/Cargo.toml"
      },
      {
        "crate": "rayon",
        "version": "1.8.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.8.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.9.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.9.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6/Cargo.toml"
      },
      {
        "crate": "anes",
        "version": "0.1.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#anes@0.1.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6/Cargo.toml"
      },
      {
        "crate": "cast",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml"
      },
      {
        "crate": "clap",
        "version": "4.4.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@4.4.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6/Cargo.toml"
      },
      {
        "crate": "half",
        "version": "1.8.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.37",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.37",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.0.83",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/Cargo.toml"
      },
      {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "manifest_path": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10/Cargo.toml"
      }
    ],
    "attributed_event_count": 25,
    "unattributed_event_count": 10,
    "owners": [
      {
        "crate": "esaxx-rs",
        "version": "0.1.10",
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
      },
      {
        "crate": "libc",
        "version": "0.2.148",
        "event_count": 9,
        "kind_counts": {
          "exec": 1,
          "used_input": 4,
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
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "workspace_root": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.1",
          "name": "aho-corasick",
          "version": "1.1.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#anes@0.1.6",
          "name": "anes",
          "version": "0.1.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#anstyle@1.0.4",
          "name": "anstyle",
          "version": "1.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
          "name": "autocfg",
          "version": "1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.4.0",
          "name": "bitflags",
          "version": "2.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
          "name": "bumpalo",
          "version": "3.14.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
          "name": "cast",
          "version": "0.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
          "name": "cc",
          "version": "1.0.83",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.1",
          "name": "ciborium",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-io@0.2.1",
          "name": "ciborium-io",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-ll@0.2.1",
          "name": "ciborium-ll",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@4.4.6",
          "name": "clap",
          "version": "4.4.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_builder@4.4.6",
          "name": "clap_builder",
          "version": "4.4.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_lex@0.5.1",
          "name": "clap_lex",
          "version": "0.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.5.1",
          "name": "criterion",
          "version": "0.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.5.0",
          "name": "criterion-plot",
          "version": "0.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.3",
          "name": "crossbeam-deque",
          "version": "0.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.15",
          "name": "crossbeam-epoch",
          "version": "0.9.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.16",
          "name": "crossbeam-utils",
          "version": "0.8.16",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.9.0",
          "name": "either",
          "version": "1.9.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.4",
          "name": "errno",
          "version": "0.3.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno-dragonfly@0.1.2",
          "name": "errno-dragonfly",
          "version": "0.1.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
          "name": "esaxx-rs",
          "version": "0.1.10",
          "manifest_path": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.2",
          "name": "half",
          "version": "1.8.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.3.3",
          "name": "hermit-abi",
          "version": "0.3.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#is-terminal@0.4.9",
          "name": "is-terminal",
          "version": "0.4.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
          "name": "itertools",
          "version": "0.10.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.9",
          "name": "itoa",
          "version": "1.0.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.64",
          "name": "js-sys",
          "version": "0.3.64",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
          "name": "libc",
          "version": "0.2.148",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.8",
          "name": "linux-raw-sys",
          "version": "0.4.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
          "name": "log",
          "version": "0.4.20",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.6.4",
          "name": "memchr",
          "version": "2.6.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.0",
          "name": "memoffset",
          "version": "0.9.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.16",
          "name": "num-traits",
          "version": "0.2.16",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.18.0",
          "name": "once_cell",
          "version": "1.18.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.3",
          "name": "oorandom",
          "version": "11.1.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.5",
          "name": "plotters",
          "version": "0.3.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.5",
          "name": "plotters-backend",
          "version": "0.3.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.5",
          "name": "plotters-svg",
          "version": "0.3.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.67",
          "name": "proc-macro2",
          "version": "1.0.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.33",
          "name": "quote",
          "version": "1.0.33",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.8.0",
          "name": "rayon",
          "version": "1.8.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.12.0",
          "name": "rayon-core",
          "version": "1.12.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.9.6",
          "name": "regex",
          "version": "1.9.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.3.9",
          "name": "regex-automata",
          "version": "0.3.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.7.5",
          "name": "regex-syntax",
          "version": "0.7.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.17",
          "name": "rustix",
          "version": "0.38.17",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.15",
          "name": "ryu",
          "version": "1.0.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
          "name": "same-file",
          "version": "1.0.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
          "name": "scopeguard",
          "version": "1.2.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.188",
          "name": "serde",
          "version": "1.0.188",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.188",
          "name": "serde_derive",
          "version": "1.0.188",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.107",
          "name": "serde_json",
          "version": "1.0.107",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.37",
          "name": "syn",
          "version": "2.0.37",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
          "name": "tinytemplate",
          "version": "1.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
          "name": "unicode-ident",
          "version": "1.0.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.4.0",
          "name": "walkdir",
          "version": "2.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.87",
          "name": "wasm-bindgen",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.87",
          "name": "wasm-bindgen-backend",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.87",
          "name": "wasm-bindgen-macro",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.87",
          "name": "wasm-bindgen-macro-support",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.87",
          "name": "wasm-bindgen-shared",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.64",
          "name": "web-sys",
          "version": "0.3.64",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
          "name": "winapi-util",
          "version": "0.1.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
          "name": "winapi-x86_64-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.48.0",
          "name": "windows-sys",
          "version": "0.48.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.48.5",
          "name": "windows-targets",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.48.5",
          "name": "windows_aarch64_gnullvm",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.48.5",
          "name": "windows_aarch64_msvc",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.48.5",
          "name": "windows_i686_gnu",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.48.5",
          "name": "windows_i686_msvc",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.48.5",
          "name": "windows_x86_64_gnu",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.48.5",
          "name": "windows_x86_64_gnullvm",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
          "name": "windows_x86_64_msvc",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5"
        }
      ],
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
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
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "exit_code": 0,
      "kind": "exec",
      "pid": 282423,
      "ppid": 282309,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
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
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "used:cc:018871c2723b82d0:77a9563caf473fbf:3e55491827d9b9d7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "path": "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
      "pid": 282423,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
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
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "used:cc:018871c2723b82d0:ffbb52dee619e4f7:3e55491827d9b9d7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
      "pid": 282423,
      "sha256": "0084afdb6795e37eed7874e70d007107abbf84e8be21d962ee5ecd567f7f3a7d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
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
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "used:cc:018871c2723b82d0:6cd16efd838c1c1f:3e55491827d9b9d7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
      "pid": 282423,
      "sha256": "42de4168bfa675af3241b604230d4f16a1a324228feaa59aab5a71ca5f3153b5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
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
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "used:cc:018871c2723b82d0:a759f47395afa91f:3e55491827d9b9d7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
      "pid": 282423,
      "sha256": "e4901fc88fe2f91f7fad9706b9a4cdff37a573f9a087101074a5b4e6e11154c0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
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
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
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
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
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
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "context_path": "/tmp/native-trace-281850-1783993689305/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-281850-1783993689305/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 282423,
      "ppid": 282309,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
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
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/libc-8a12625678126bc3/rustc16zksV",
        "/target/debug/build/libc-8a12625678126bc3",
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
          "directory": "/target/debug/build/libc-8a12625678126bc3/rustc16zksV",
          "kind": "object",
          "path": "/target/debug/build/libc-8a12625678126bc3/rustc16zksV/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a12625678126bc3",
          "kind": "object",
          "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a12625678126bc3",
          "kind": "object",
          "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a12625678126bc3",
          "kind": "object",
          "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-282423-1783993701489242245.map",
      "pid": 282423,
      "ppid": 282309,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-282423-1783993701489242245.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 283063,
      "ppid": 283015,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:f914cd700233e190:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
      "pid": 283063,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:a4be52e84de5233d:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
      "pid": 283063,
      "sha256": "06e0a7fe93d0fe65e5e0b5b8ad71f189c5e0695f4c9f1d30be96f1caf31a1c77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:be176e8d076b30fd:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
      "pid": 283063,
      "sha256": "bb1ffe7aed9b52d038e9fa57a755815aed7151580c02d8e02bad405bd62845f0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:a3b7896a178c6ae0:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
      "pid": 283063,
      "sha256": "c0430de796a0cf9aee624b66f5bc83c41675b5fcec79a2b75a25a8d7391ceaf7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:4a1eb1f091eeab47:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
      "pid": 283063,
      "sha256": "3259e7258d9a3108a4008ab18e1af565e3c024066beeffed659312af39fc14d3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:df680ed573768aad:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
      "pid": 283063,
      "sha256": "5e2e1d5101126099523f7656a84a3b5d2bc4b3aff449f8afe6c967124cfec5fa",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:a62329485a68f5ba:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
      "pid": 283063,
      "sha256": "78d8c7ad64fc95fdd41c10e27aa710a54e5371954f00932f748e1da68c4d7cdb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:b95aa416170c8e2b:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
      "pid": 283063,
      "sha256": "cd9ac12f7fe957318ba5a0db37e53c0c8333bc25a9fef1eb9b4e9199e67b297f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:4e780f6907409d1b:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
      "pid": 283063,
      "sha256": "eb8164bb68e398317f4df1538373ede98e2ae7282836aa0d9bc90da23ffb5965",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:6fd5e83716b2b202:2c6491785c43daac:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
      "pid": 283063,
      "sha256": "b5d70f58226e48020baead62f879a65339ae344afe36358deccd208d1c4137a6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
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
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "context_path": "/tmp/native-trace-281850-1783993689305/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-281850-1783993689305/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 283063,
      "ppid": 283015,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
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
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc1ybI4F/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.11esyul.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.11esyul.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.11esyul.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.11esyul.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.11esyul.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.11esyul.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.11esyul.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.11esyul.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.11esyul.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.09.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.10.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.11.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.12.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.13.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.14.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.15.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.1.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-283063-1783993709076396264.map",
      "pid": 283063,
      "ppid": 283015,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-283063-1783993709076396264.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
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
      "parsed_event_count": 422,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 423,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "wn-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n23.270  cc               284378 284377   0 /usr/bin/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcxqQSD6/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n23.370  collect2         284379 284378   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfh87jv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n23.389  ld.lld           284390 284379   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfh87jv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3 ...\n23.398  rust-lld         284390 284379   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfh87jv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n23.636  build-script-bu  284425 284300   0 /target/debug/build/libc-8a12625678126bc3/build-script-build\n23.639  rustc            284426 284425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n23.682  rustc            284431 284300   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n23.840  runc             284435 281624   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6 --log-format json --systemd-cgroup kill --all dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85c 9\n23.910  runc             284441 281624   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6 --log-format json --systemd-cgroup delete dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85c\n24.165  containerd-shim  284450 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6 delete\n24.170  runc             284459 284450   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85 --log-format json delete --force dfe0e37827f2b226d499340c8915d25dd57fcea3439a644370305d8d9a6ae85c\n24.305  powerpc64le-lin  284466 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n24.329  cc1plus          284467 284466   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n24.363  systemd-sysctl   284469 284468   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc8ccc1a --prefix=/net/ipv4/neigh/vethc8ccc1a --prefix=/net/ipv6/conf/vethc8ccc1a --prefix=/net/ipv6/neigh/vethc8ccc1a\n24.452  as               284472 274506   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/3ac6d140080a8125-version_builder.o /tmp/ccUXCxG5.s\n24.537  as               284473 244909   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/fb8935d9b2e862b1-db_impl.o /tmp/ccW68F9I.s\n24.553  rustc            284478 284250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=18831150b9e7f196 ...\n24.979  rustc            284487 284300   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=18831150b9e7f196 ...\n25.261  aarch64-linux-g  284500 277046   0 /usr/bin/aarch64-linux-gnu-gcc /target/aarch64-unknown-linux-gnu/debug/deps/rustcfr72S2/symbols.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.00r9eycqmv6875teof0nzfsfs.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.03unpa094f0624y346we3ct8t.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.04o6ulm54kkww12hyjjbnna91.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.05u83lh5wm60nxef5na5033ky.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.07gsl84shgfie1g4ih4irhdmr.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.08wxndnwuhx76g3xd8iqxn6dq.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0d5drd91i7g641erc3yld0ca1.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0e0clpwkeot615wigqii7nk2u.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0lbkagnyle9bftb5rlyupzc38.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0r8rbj3ejwtaxvyrrtwhp1yjz.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0rb1kipsp8r6fzb4aydt8qrxx.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.0sr11atuve2ds0cz1p6ihvs7l.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.12c7tz1j6hb38sip2yf229soo.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.16jeffe7l9zmd428916qkm00g.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.16zeke45n5a7qqrm94ohojyri.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.17v1jnqsgnzqkpmxxo4rroj84.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.18bxxafzl2bubxrr3yxecek15.0xwyj3u.rcgu.o /target/aarch64-unknown-linux-gnu/debug/deps/rav1e-5d5188a7e77436f5.18g9wkqghlpsot0p3lmsh16mg.0xwyj3u.rcgu.o ...\n25.279  collect2         284502 284500   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFRWL.res --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux --fix-cortex-a53-843419 -pie -z now -z ...\n25.288  ld               284503 284502   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFRWL.res --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux --fix-cortex-a53-843419 -pie -z now -z ...\n25.776  runc             284525 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process851379402 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n26.026  exe              284554 284525   0 /proc/self/exe init\n26.067  curl             284556 284525   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n26.265  rustc            284577 284250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n26.376  rustc            284583 284300   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n26.521  powerpc64le-lin  284593 229287   0 \n26.521  cc1plus          284594 284593   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n26.545  cc               284611 284583   0 /tmp/native-trace-283957-1783993716140/shims/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcoMtnjY/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.056l8e5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n26.548  cc               284614 284611   0 /usr/bin/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcoMtnjY/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.056l8e5.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.056l8e5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n26.555  collect2         284615 284614   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjUp0Yn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n26.557  cc               284613 284304   0 /tmp/native-trace-279094-1783993664521/shims/cc -Wl,--version-script=/target/debug/deps/rustcG6c7Ji/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcG6c7Ji/symbols.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.00.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.01.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.02.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.03.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.04.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.05.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.06.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.07.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.08.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.09.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.10.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.11.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.12.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.13.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.14.rcgu.o ...\n26.561  cc               284617 284613   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcG6c7Ji/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcG6c7Ji/symbols.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.00.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.01.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.02.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.03.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.04.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.05.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.06.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.07.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.08.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.09.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.10.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.11.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.12.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.13.rcgu.o /target/debug/deps/serde_derive-2eed6651630996d9.serde_derive.a96eb68d199f1877-cgu.14.rcgu.o ...\n26.561  ld.lld           284616 284615   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjUp0Yn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c ...\n26.569  collect2         284618 284617   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclVVPfD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-2eed6651630996d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcG6c7Ji/raw-dylibs ...\n26.572  rust-lld         284616 284615   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjUp0Yn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n26.572  ld.lld           284619 284618   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclVVPfD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-2eed6651630996d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcG6c7Ji/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n26.576  rust-lld         284619 284618   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclVVPfD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-2eed6651630996d9.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n26.599  cc               284612 284577   0 /tmp/native-trace-283640-1783993713810/shims/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcPh9bmV/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.010locg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n26.601  cc               284637 284612   0 /usr/bin/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcPh9bmV/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.010locg.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.010locg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n26.608  collect2         284638 284637   0 \n26.612  ld.lld           284639 284638   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfT3uX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c ...\n26.612  rust-lld         284639 284638   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfT3uX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n26.792  build-script-bu  284676 284300   0 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build\n26.796  powerpc64le-lin  284678 284676   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src -Wall -Wextra -std=c++11 -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -c src/esaxx.cpp\n26.799  cc1plus          284679 284678   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I src -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE src/esaxx.cpp -msecure-plt -quiet -dumpbase esaxx.cpp -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -gdwarf-4 -O0 -Wall -Wextra ...\n26.810  as               284680 280108   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/3ac6d140080a8125-write_thread.o /tmp/ccwCtlBC.s\n26.820  as               284681 281760   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/676314c7dcdc695c-env_encryption.o /tmp/ccVBM2Sx.s\n26.846  build-script-bu  284683 284250   0 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build\n26.851  riscv64-linux-g  284685 284683   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -mcmodel=medany -I src -Wall -Wextra -std=c++11 -o /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o -c src/esaxx.cpp\n26.855  cc1plus          284686 284685   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE src/esaxx.cpp -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/ -dumpbase esaxx.cpp -dumpbase-ext .cpp -march=rv64gc -mabi=lp64d -mcmodel=medany ...\n27.016  rustc            284691 279808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stdweb_internal_macros --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stdweb-internal-macros-0.2.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n27.016  rustc            284690 279808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stdweb_derive --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stdweb-derive-0.5.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n27.070  riscv64-linux-g  284698 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n27.078  cc1plus          284699 284698   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n27.091  as               284700 280215   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-trim_history_scheduler.o /tmp/ccGL5G5Z.s\n27.416  as               284705 284685   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o /tmp/ccGrWgJ4.s\n27.454  riscv64-linux-g  284706 284683   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o\n27.482  as               284707 284678   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I src -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o /tmp/ccJ5cyhb.s\n27.518  powerpc64le-lin  284710 284676   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o\n27.553  powerpc64le-lin  284711 284676   0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a\n27.567  rustc            284714 284300   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name esaxx_rs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n27.594  aarch64-linux-g  284715 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n27.606  cc1plus          284721 284715   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n27.610  aarch64-linux-g  284720 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n27.613  cc1plus          284722 284720   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n27.737  riscv64-linux-g  284728 284683   0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a\n27.819  cc               284730 284690   0 /tmp/native-trace-279094-1783993664521/shims/cc -Wl,--version-script=/target/debug/deps/rustcTJKp6L/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTJKp6L/symbols.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.0.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.1.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.2.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.3.rcgu.o /target/debug/deps/rustcTJKp6L/rmeta.o /target/debug/deps/stdweb_derive-672a03522bab9858.0htv00vx0bhk7szwtxlazw85e.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-c27db84f59d4ae56.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n27.823  cc               284731 284730   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcTJKp6L/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTJKp6L/symbols.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.0.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.1.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.2.rcgu.o /target/debug/deps/stdweb_derive-672a03522bab9858.stdweb_derive.7d30f7800abc3a6d-cgu.3.rcgu.o /target/debug/deps/rustcTJKp6L/rmeta.o /target/debug/deps/stdweb_derive-672a03522bab9858.0htv00vx0bhk7szwtxlazw85e.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-c27db84f59d4ae56.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n27.827  collect2         284732 284731   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7gscYc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libstdweb_derive-672a03522bab9858.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTJKp6L/raw-dylibs ...\n27.834  ld.lld           284733 284732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7gscYc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libstdweb_derive-672a03522bab9858.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcTJKp6L/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n27.843  rust-lld         284733 284732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7gscYc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libstdweb_derive-672a03522bab9858.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n27.891  rustc            284736 284250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name esaxx_rs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n28.181  runc             284813 283788   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2de --log-format json --systemd-cgroup kill --all ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442b 9\n28.199  runc             284821 283788   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2de --log-format json --systemd-cgroup delete ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442b\n28.212  containerd-shim  284828 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2de delete\n28.220  runc             284839 284828   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442 --log-format json delete --force ecc3daefaf5dabd45ce5f805ea26ba73edf5e8b449c596f22e67939c2deb442b\n28.292  sh               284859 284853   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth6d59671\n28.292  sed              284865 284859   0 /usr/bin/sed -n s/^driver: //p\n28.300  ethtool          284864 284859   0 /usr/sbin/ethtool -i veth6d59671\n28.310  systemd-sysctl   284880 284853   0 \n28.400  runc             284903 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process3885722702 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n28.411  exe              284911 284903   0 /proc/self/exe init\n28.430  curl             284914 284903   0 /usr/bin/curl -f http://localhost:9091/healthz\n28.573  runc             284942 283264   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a57 --log-format json --systemd-cgroup kill --all 60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2d 9\n28.587  runc             284949 283264   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a57 --log-format json --systemd-cgroup delete 60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2d\n28.600  containerd-shim  284955 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a57 delete\n28.604  runc             284961 284955   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2 --log-format json delete --force 60624eda14d94fe728e1b6b4c61e050138952bf8b49bfbcb4a896ea8a572da2d\n28.627  riscv64-linux-g  284967 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n28.632  cc               284968 284691   0 /tmp/native-trace-279094-1783993664521/shims/cc -Wl,--version-script=/target/debug/deps/rustcDc5ZvR/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcDc5ZvR/symbols.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.0.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.1.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.2.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.3.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.4.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.5.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.6.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.7.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.8.rcgu.o /target/debug/deps/rustcDc5ZvR/rmeta.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.91mzy2jb87iqcicyfj8osa4hp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsha1-e3a4ab61b7d8390a.rlib /target/debug/deps/libsha1_smol-4d14c8b23817f26e.rlib ...\n28.634  cc               284970 284968   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcDc5ZvR/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcDc5ZvR/symbols.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.0.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.1.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.2.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.3.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.4.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.5.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.6.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.7.rcgu.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.stdweb_internal_macros.f2f34201592ebed6-cgu.8.rcgu.o /target/debug/deps/rustcDc5ZvR/rmeta.o /target/debug/deps/stdweb_internal_macros-b05f4def71556e89.91mzy2jb87iqcicyfj8osa4hp.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsha1-e3a4ab61b7d8390a.rlib /target/debug/deps/libsha1_smol-4d14c8b23817f26e.rlib ...\n28.637  cc1plus          284969 284967   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n28.640  collect2         284972 284970   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfTRkj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libstdweb_internal_macros-b05f4def71556e89.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcDc5ZvR/raw-dylibs ...\n28.642  ld.lld           284973 284972   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfTRkj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libstdweb_internal_macros-b05f4def71556e89.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcDc5ZvR/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n28.644  systemd-sysctl   284974 284921   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb1a6e24 --prefix=/net/ipv4/neigh/vethb1a6e24 --prefix=/net/ipv6/conf/vethb1a6e24 --prefix=/net/ipv6/neigh/vethb1a6e24\n28.677  rust-lld         284973 284972   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYfTRkj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libstdweb_internal_macros-b05f4def71556e89.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n28.879  aarch64-linux-g  285014 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n28.892  cc1plus          285015 285014   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n29.007  rustc            285035 279808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stdweb --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"serde_json\" ...\n29.082  16               285039 1        0 \n29.116  frpc             285039 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg /usr/local/bin/frpc -c /etc/frp/frpc.toml\n29.162  as               285043 275729   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-memtable.o /tmp/ccj0Y6Hx.s\n29.280  as               285044 271948   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-forward_iterator.o /tmp/ccCGgcID.s\n29.888  as               285046 272511   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-internal_stats.o /tmp/ccq3GIoe.s\n29.898  powerpc64le-lin  285045 278490   0 /usr/bin/powerpc64le-linux-gnu-gcc -m64 /target/powerpc64le-unknown-linux-gnu/debug/deps/rustc9CiLv0/symbols.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.018rkip0j4fw6w68mbnw1m28e.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.02xar1dge2qgjfm7ojjrp2mwj.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.094nqzoy52cliyyejrb0pptzw.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0axtmd151x2gxji5hgaq952fu.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0eham50qb6sadz3naptnvenvu.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0ejw0seg5qcta6jrsus80sslq.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0ew4u3oh428h4oiqaofccy56u.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0i3nl5nntn96u5y8hsln2wgp5.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0jxb4krgel0ba9ds61gcjwdys.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0lj497v4qk9aovyppwzs7dpel.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0ro3wg5lkmn9x02zkchrllnxb.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0us3t2aaeumy5uk4q0o97m273.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0vu2sjb9clr4slpkbzylai5zc.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0w0j1l26uxszpkq86jb8uylok.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.0xwz4p4fto6rpnhb41v34osp4.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.10rwmdknl4mm7in9vjvkox1u5.19sy07c.rcgu.o /target/powerpc64le-unknown-linux-gnu/debug/deps/rav1e-4706710c31c185ad.12m7jtsy8uxaf7qn5aavxw02l.19sy07c.rcgu.o ...\n29.917  collect2         285047 285045   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKjJQY.res --sysroot=/ --build-id --eh-frame-hdr -m elf64lppc --hash-style=gnu --as-needed -dynamic-linker /lib64/ld64.so.2 -pie -z now -z relro -o ...\n29.923  ld               285048 285047   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMKjJQY.res --sysroot=/ --build-id --eh-frame-hdr -m elf64lppc --hash-style=gnu --as-needed -dynamic-linker /lib64/ld64.so.2 -pie -z now -z relro -o ...\n30.088  as               285049 279694   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/3ac6d140080a8125-write_stall_stats.o /tmp/ccLQGnHk.s\n30.400  as               285050 284593   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/fe29f3d3b3c15862-wide_column_serialization /tmp/cc984JNM.s\n30.435  as               285051 280041   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-transaction_log_impl.o /tmp/ccgRzrSA.s\n30.996  as               285052 284125   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/librocksdb-sys-b169f8fa00eee22f/out/3ac6d140080a8125-wal_edit.o /tmp/ccUvaHKn.s\n31.036  aarch64-linux-g  285053 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n31.047  cc1plus          285054 285053   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.080  powerpc64le-lin  285055 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.091  cc1plus          285057 285055   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.101  powerpc64le-lin  285056 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.110  as               285060 271975   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/3ac6d140080a8125-repair.o /tmp/ccdfhuuF.s\n31.128  powerpc64le-lin  285058 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.133  powerpc64le-lin  285061 229287   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.146  cc1plus          285063 285061   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.219  cc1plus          285059 285056   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.240  as               285065 281129   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/676314c7dcdc695c-env.o /tmp/ccw8HX3Q.s\n31.245  powerpc64le-lin  285064 229287   0 /usr/bin/powerpc64le-linux-gnu-g++  -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 ...\n31.252  cc1plus          285066 285064   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.356  as               285067 239340   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/librocksdb-sys-9c6178faf0604017/out/fb8935d9b2e862b1-db_impl.o /tmp/ccIi9GvW.s\n31.573  cc1plus          285062 285058   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n31.898  as               285068 278751   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-table_cache.o /tmp/ccA6JFa6.s\n32.195  runc             285069 272235   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a --log-format json --systemd-cgroup kill --all 152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e7 9\n32.253  riscv64-linux-g  285075 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n32.257  cc1plus          285076 285075   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ...\n32.301  as               285077 273395   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-memtable_list.o /tmp/ccOUyD0T.s\n32.381  runc             285078 272235   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a --log-format json --systemd-cgroup delete 152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e7\n32.457  as               285084 280902   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/librocksdb-sys-865f667fccf0d0aa/out/3ac6d140080a8125-version_edit.o /tmp/ccI8nO5W.s\n32.475  containerd-shim  285085 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a delete\n32.481  runc             285092 285085   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e --log-format json delete --force 152b9a9ed17a5e9768acaebf9e1a3c4328cb49026cf58debcb7c434595a3c7e7\n32.542  systemd-sysctl   285098 285097   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6f4c4fa --prefix=/net/ipv4/neigh/veth6f4c4fa --prefix=/net/ipv6/conf/veth6f4c4fa --prefix=/net/ipv6/neigh/veth6f4c4fa\n32.565  aarch64-linux-g  285099 229024   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra -std=c++17 -Wsign-compare ...\n32.576  cc1plus          285101 285099   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D NDEBUG=1 -D OS_LINUX -D ROCKSDB_PLATFORM_POSIX -D ...\n32.605  riscv64-linux-g  285102 229324   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I rocksdb/include/ -I rocksdb/ -I rocksdb/third-party/gtest-1.8.1/fused-src/ -I . -Wall -Wextra ...\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-8a12625678126bc3/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 282509,
      "build_script_target_dir": "libc-8a12625678126bc3",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
      "pid": 282509,
      "ppid": 282276,
      "root_cargo_pid": 282276,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 282509,
      "build_script_target_dir": "libc-8a12625678126bc3",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 282510,
      "ppid": 282509,
      "root_cargo_pid": 282276,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 283156,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
      "pid": 283156,
      "ppid": 282276,
      "root_cargo_pid": 282276,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-std=c++11",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
        "-c",
        "src/esaxx.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 283156,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-g++",
      "pid": 283158,
      "ppid": 283156,
      "root_cargo_pid": 282276,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "src",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-D_GNU_SOURCE",
        "src/esaxx.cpp",
        "-quiet",
        "-dumpbase",
        "esaxx.cpp",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "-std=c++11",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 283156,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
      "pid": 283187,
      "ppid": 283158,
      "root_cargo_pid": 282276,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-I",
        "src",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o",
        "/tmp/ccC3S2vg.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 283156,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 283433,
      "ppid": 283158,
      "root_cargo_pid": 282276,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cq",
        "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/src/esaxx.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 283156,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 283452,
      "ppid": 283156,
      "root_cargo_pid": 282276,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "s",
        "/target/aarch64-unknown-linux-gnu/debug/build/esaxx-rs-2e57fd001aae553a/out/libesaxx.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 283156,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 283464,
      "ppid": 283156,
      "root_cargo_pid": 282276,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "bsrun:2ebdc03c5a2acb3f:d2cbd9eb7f36ae5e:094a542f6f4ffc0f",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "out_dir": "/target/debug/build/libc-8a12625678126bc3/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
      "success": true,
      "target": null,
      "version": "0.2.148",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "esaxx-rs",
      "cwd": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "event_id": "bsrun:aec4a6297808479c:58c8166d76a53504:5698292d0e3f3d21",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
      "out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
      "success": true,
      "target": null,
      "version": "0.1.10",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-aarch64-3fcccqnl/src/esaxx-rs-0.1.10",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 282509,
      "build_script_target_dir": "libc-8a12625678126bc3",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 282510,
      "ppid": 282509,
      "root_cargo_pid": 282276,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 1361,
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "crate_id": "250592",
    "version_id": "916920",
    "downloads": 13464958,
    "cumulative_downloads": 95446591387,
    "cumulative_share_of_global": 0.3568527707953331,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "build.rs",
    "build_script_exists": true,
    "package_build_field": null,
    "build_script_reason": "default_build_rs_exists",
    "download_source": "local"
  }
}
```
