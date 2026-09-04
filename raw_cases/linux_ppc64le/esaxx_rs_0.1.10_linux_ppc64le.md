# `esaxx-rs` `0.1.10`

Platform: Linux ppc64le

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a`

Owner: `esaxx-rs` `0.1.10`

### Source files

* `/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10/src/esaxx.cpp`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "src/esaxx.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "esaxx.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "src": "src/esaxx.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1265110,
  "ppid": 1265109,
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 1264998,
  "build_script_root_pid": 1265107,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
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
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1265112,
  "ppid": 1265107,
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 1264998,
  "build_script_root_pid": 1265107,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "workspace_root": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
      "name": "esaxx-rs",
      "version": "0.1.10",
      "manifest_path": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
  "pid": 1265013,
  "ppid": 1265005,
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
  "event_id": "used:cc:018871c2723b82d0:d1311fa20c1e8759:3e55491827d9b9d7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "path": "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
  "pid": 1265013,
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
  "pid": 1265013,
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
  "pid": 1265013,
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
  "pid": 1265013,
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
  "context_path": "/tmp/native-trace-1264970-1784008689277/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1264970-1784008689277/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1265013,
  "ppid": 1265005,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY",
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
      "directory": "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY",
      "kind": "object",
      "path": "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-1265013-1784008691329213895.map",
  "pid": 1265013,
  "ppid": 1265005,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1265013-1784008691329213895.map"
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1265086,
  "ppid": 1265072,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:4f8c33a91d5ad79f:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
  "pid": 1265086,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:189e8454c3391c3d:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
  "pid": 1265086,
  "sha256": "da4cdaa5f9bf68e86ddf79323d671dd7149d7f8e73b66accc1f90ff00ccc478e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:6230161b80d9cdb1:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
  "pid": 1265086,
  "sha256": "b09f18e91e035a49307badc75b12cd43b5e45a188f0e5abaa66e74bbc08826ea",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:2a0650f3dd54318c:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
  "pid": 1265086,
  "sha256": "54089b4d7d056c8c3f03fcd896352711fdf1e15b9cdf05c063ceb7739130264b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:0d579079be1f410c:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
  "pid": 1265086,
  "sha256": "e93c6f136f9bdc9b5f7e532879673e37430da2cdea4c3022b43454cd383b0ef2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:dec1d142d2544414:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
  "pid": 1265086,
  "sha256": "1b06fe388696d5de059bbf6f4f49aed60f6adc32e8768c98235a3ad5473316bf",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:0153ef72a221eef5:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
  "pid": 1265086,
  "sha256": "b8d98c732c2bd55cb7e09344319d738e72cf0a4e6f432c67ed5582d55fdbfe30",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:3aa5328482ead32b:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
  "pid": 1265086,
  "sha256": "4144219b842c290a9b73432481f59579275ac3eca183b491091723a766a730fa",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:2576b5ca980e1ee0:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
  "pid": 1265086,
  "sha256": "98a8ce0101e4f7c8f18af5310bc3f1d0efe65bd409e9a889005c8ea590093fef",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:a092f80f36ce1bfd:dc841ac53285d264:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
  "pid": 1265086,
  "sha256": "b5d70f58226e48020baead62f879a65339ae344afe36358deccd208d1c4137a6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "context_path": "/tmp/native-trace-1264970-1784008689277/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1264970-1784008689277/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1265086,
  "ppid": 1265072,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG",
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
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1265086-1784008692275596123.map",
  "pid": 1265086,
  "ppid": 1265072,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1265086-1784008692275596123.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
  "parsed_event_count": 44,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 45,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "0.088   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            1264998 1264970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n0.097   rustc            1264999 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.128   rustc            1265005 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.223   cc               1265013 1265005   0 /tmp/native-trace-1264970-1784008689277/shims/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.223   cc               1265014 1265013   0 /usr/bin/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.226   collect2         1265015 1265014   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3CVdmB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.227   ld.lld           1265016 1265015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3CVdmB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3 ...\n0.228   rust-lld         1265016 1265015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3CVdmB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.269   build-script-bu  1265034 1264998   0 /target/debug/build/libc-8a12625678126bc3/build-script-build\n0.270   rustc            1265035 1265034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n0.281   rustc            1265040 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.737   rustc            1265047 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=18831150b9e7f196 ...\n1.136   rustc            1265072 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n1.169   cc               1265086 1265072   0 /tmp/native-trace-1264970-1784008689277/shims/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.169   cc               1265087 1265086   0 /usr/bin/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.172   collect2         1265088 1265087   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPrMAA7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.173   ld.lld           1265089 1265088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPrMAA7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c ...\n1.174   rust-lld         1265089 1265088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPrMAA7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.222   build-script-bu  1265107 1264998   0 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build\n1.224   powerpc64le-lin  1265109 1265107   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src -Wall -Wextra -std=c++11 -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -c src/esaxx.cpp\n1.225   cc1plus          1265110 1265109   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I src -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE src/esaxx.cpp -msecure-plt -quiet -dumpbase esaxx.cpp -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -gdwarf-4 -O0 -Wall -Wextra ...\n1.469   as               1265111 1265109   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I src -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o /tmp/cc6dpcOP.s\n1.482   powerpc64le-lin  1265112 1265107   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o\n1.485   powerpc64le-lin  1265113 1265107   0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a\n1.489   rustc            1265115 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name esaxx_rs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n3.265   sh               1265164 2147557   0 /bin/sh -c which ps\n3.266   which            1265164 2147557   0 /usr/bin/which ps\n3.269   sh               1265165 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.270   ps               1265165 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.295   sh               1265166 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n3.297   cpuUsage.sh      1265166 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539\n3.298   sed              1265167 1265166   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.302   cat              1265168 1265166   0 /usr/bin/cat /proc/2240539/stat\n3.304   sleep            1265169 1265166   0 /usr/bin/sleep 1\n3.864   runc             1265170 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process4025996817 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n3.869   exe              1265177 1265170   0 /proc/self/exe init\n3.887   curl             1265180 1265170   0 /usr/bin/curl -f http://localhost:9091/healthz\n4.306   sed              1265187 1265166   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.309   cat              1265188 1265166   0 /usr/bin/cat /proc/2240539/stat\n8.043   16               1265190 1        0 /proc/self/fd/16 --deserialize 127 --log-level info --log-target journal-or-kmsg\n8.059   frpc             1265190 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n14.889  runc             1265196 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process3762375829 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n14.895  exe              1265204 1265196   0 /proc/self/exe init\n14.927  curl             1265206 1265196   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n"
}
```

#### Record 26

```json
{
  "argv": [
    "/target/debug/build/libc-8a12625678126bc3/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1265034,
  "build_script_target_dir": "libc-8a12625678126bc3",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
  "pid": 1265034,
  "ppid": 1264998,
  "root_cargo_pid": 1264998,
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
  "build_script_root_pid": 1265034,
  "build_script_target_dir": "libc-8a12625678126bc3",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 1265035,
  "ppid": 1265034,
  "root_cargo_pid": 1264998,
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
  "build_script_root_pid": 1265107,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
  "pid": 1265107,
  "ppid": 1264998,
  "root_cargo_pid": 1264998,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out"
}
```

#### Record 29

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
    "-c",
    "src/esaxx.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1265107,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 1265109,
  "ppid": 1265107,
  "root_cargo_pid": 1264998,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "src/esaxx.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "esaxx.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1265107,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 1265110,
  "ppid": 1265109,
  "root_cargo_pid": 1264998,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 31

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "src",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
    "/tmp/cc6dpcOP.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1265107,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 1265111,
  "ppid": 1265109,
  "root_cargo_pid": 1264998,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 32

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1265107,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 1265112,
  "ppid": 1265107,
  "root_cargo_pid": 1264998,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "s",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1265107,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 1265113,
  "ppid": 1265107,
  "root_cargo_pid": 1264998,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "event_id": "bsrun:1cfc38ae44e3b5f7:58c8166d76a53504:5698292d0e3f3d21",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
  "success": true,
  "target": null,
  "version": "0.1.10",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
  "build_script_root_pid": 1265034,
  "build_script_target_dir": "libc-8a12625678126bc3",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 1265035,
  "ppid": 1265034,
  "root_cargo_pid": 1264998,
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
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "src",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "src/esaxx.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "esaxx.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "..."
  ],
  "src": "src/esaxx.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1265110,
  "ppid": 1265109,
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 1264998,
  "build_script_root_pid": 1265107,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 38

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1265112,
  "ppid": 1265107,
  "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 1264998,
  "build_script_root_pid": 1265107,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T05:58:30.042467+00:00",
  "crate": "esaxx-rs",
  "version": "0.1.10",
  "architecture": "ppc64le",
  "duration_seconds": 21.32788459584117,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "manifest_path": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "workspace_root": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
          "name": "esaxx-rs",
          "version": "0.1.10",
          "manifest_path": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
      "pid": 1265013,
      "ppid": 1265005,
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
      "event_id": "used:cc:018871c2723b82d0:d1311fa20c1e8759:3e55491827d9b9d7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "path": "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
      "pid": 1265013,
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
      "pid": 1265013,
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
      "pid": 1265013,
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
      "pid": 1265013,
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
      "context_path": "/tmp/native-trace-1264970-1784008689277/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1264970-1784008689277/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1265013,
      "ppid": 1265005,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/raw-dylibs",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY",
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
          "directory": "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY",
          "kind": "object",
          "path": "/target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-1265013-1784008691329213895.map",
      "pid": 1265013,
      "ppid": 1265005,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1265013-1784008691329213895.map"
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1265086,
      "ppid": 1265072,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:4f8c33a91d5ad79f:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
      "pid": 1265086,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:189e8454c3391c3d:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
      "pid": 1265086,
      "sha256": "da4cdaa5f9bf68e86ddf79323d671dd7149d7f8e73b66accc1f90ff00ccc478e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:6230161b80d9cdb1:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
      "pid": 1265086,
      "sha256": "b09f18e91e035a49307badc75b12cd43b5e45a188f0e5abaa66e74bbc08826ea",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:2a0650f3dd54318c:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
      "pid": 1265086,
      "sha256": "54089b4d7d056c8c3f03fcd896352711fdf1e15b9cdf05c063ceb7739130264b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:0d579079be1f410c:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
      "pid": 1265086,
      "sha256": "e93c6f136f9bdc9b5f7e532879673e37430da2cdea4c3022b43454cd383b0ef2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:dec1d142d2544414:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
      "pid": 1265086,
      "sha256": "1b06fe388696d5de059bbf6f4f49aed60f6adc32e8768c98235a3ad5473316bf",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:0153ef72a221eef5:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
      "pid": 1265086,
      "sha256": "b8d98c732c2bd55cb7e09344319d738e72cf0a4e6f432c67ed5582d55fdbfe30",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:3aa5328482ead32b:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
      "pid": 1265086,
      "sha256": "4144219b842c290a9b73432481f59579275ac3eca183b491091723a766a730fa",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:2576b5ca980e1ee0:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
      "pid": 1265086,
      "sha256": "98a8ce0101e4f7c8f18af5310bc3f1d0efe65bd409e9a889005c8ea590093fef",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:a092f80f36ce1bfd:dc841ac53285d264:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
      "pid": 1265086,
      "sha256": "b5d70f58226e48020baead62f879a65339ae344afe36358deccd208d1c4137a6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "context_path": "/tmp/native-trace-1264970-1784008689277/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1264970-1784008689277/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1265086,
      "ppid": 1265072,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG",
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
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1265086-1784008692275596123.map",
      "pid": 1265086,
      "ppid": 1265072,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1265086-1784008692275596123.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
      "parsed_event_count": 44,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 45,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "0.088   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            1264998 1264970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n0.097   rustc            1264999 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.128   rustc            1265005 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.223   cc               1265013 1265005   0 /tmp/native-trace-1264970-1784008689277/shims/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.223   cc               1265014 1265013   0 /usr/bin/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcB8EtZY/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.226   collect2         1265015 1265014   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3CVdmB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.227   ld.lld           1265016 1265015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3CVdmB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3 ...\n0.228   rust-lld         1265016 1265015   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3CVdmB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.269   build-script-bu  1265034 1264998   0 /target/debug/build/libc-8a12625678126bc3/build-script-build\n0.270   rustc            1265035 1265034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n0.281   rustc            1265040 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.737   rustc            1265047 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=18831150b9e7f196 ...\n1.136   rustc            1265072 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n1.169   cc               1265086 1265072   0 /tmp/native-trace-1264970-1784008689277/shims/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.169   cc               1265087 1265086   0 /usr/bin/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustcXkqggG/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.0f0ezlj.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.0f0ezlj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.172   collect2         1265088 1265087   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPrMAA7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.173   ld.lld           1265089 1265088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPrMAA7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c ...\n1.174   rust-lld         1265089 1265088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPrMAA7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.222   build-script-bu  1265107 1264998   0 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build\n1.224   powerpc64le-lin  1265109 1265107   0 /usr/bin/powerpc64le-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I src -Wall -Wextra -std=c++11 -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -c src/esaxx.cpp\n1.225   cc1plus          1265110 1265109   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus -quiet -I src -imultiarch powerpc64le-linux-gnu -D_GNU_SOURCE src/esaxx.cpp -msecure-plt -quiet -dumpbase esaxx.cpp -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o -gdwarf-4 -O0 -Wall -Wextra ...\n1.469   as               1265111 1265109   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I src -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o /tmp/cc6dpcOP.s\n1.482   powerpc64le-lin  1265112 1265107   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o\n1.485   powerpc64le-lin  1265113 1265107   0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a\n1.489   rustc            1265115 1264998   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name esaxx_rs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n3.265   sh               1265164 2147557   0 /bin/sh -c which ps\n3.266   which            1265164 2147557   0 /usr/bin/which ps\n3.269   sh               1265165 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.270   ps               1265165 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.295   sh               1265166 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n3.297   cpuUsage.sh      1265166 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539\n3.298   sed              1265167 1265166   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.302   cat              1265168 1265166   0 /usr/bin/cat /proc/2240539/stat\n3.304   sleep            1265169 1265166   0 /usr/bin/sleep 1\n3.864   runc             1265170 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process4025996817 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n3.869   exe              1265177 1265170   0 /proc/self/exe init\n3.887   curl             1265180 1265170   0 /usr/bin/curl -f http://localhost:9091/healthz\n4.306   sed              1265187 1265166   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.309   cat              1265188 1265166   0 /usr/bin/cat /proc/2240539/stat\n8.043   16               1265190 1        0 /proc/self/fd/16 --deserialize 127 --log-level info --log-target journal-or-kmsg\n8.059   frpc             1265190 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n14.889  runc             1265196 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process3762375829 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n14.895  exe              1265204 1265196   0 /proc/self/exe init\n14.927  curl             1265206 1265196   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-8a12625678126bc3/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1265034,
      "build_script_target_dir": "libc-8a12625678126bc3",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
      "pid": 1265034,
      "ppid": 1264998,
      "root_cargo_pid": 1264998,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1265034,
      "build_script_target_dir": "libc-8a12625678126bc3",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 1265035,
      "ppid": 1265034,
      "root_cargo_pid": 1264998,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1265107,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
      "pid": 1265107,
      "ppid": 1264998,
      "root_cargo_pid": 1264998,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-std=c++11",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
        "-c",
        "src/esaxx.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1265107,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 1265109,
      "ppid": 1265107,
      "root_cargo_pid": 1264998,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "src",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "src/esaxx.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "esaxx.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1265107,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 1265110,
      "ppid": 1265109,
      "root_cargo_pid": 1264998,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "src",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o",
        "/tmp/cc6dpcOP.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1265107,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 1265111,
      "ppid": 1265109,
      "root_cargo_pid": 1264998,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cq",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/src/esaxx.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1265107,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 1265112,
      "ppid": 1265107,
      "root_cargo_pid": 1264998,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "s",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/esaxx-rs-1d775fcd601f33ce/out/libesaxx.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1265107,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 1265113,
      "ppid": 1265107,
      "root_cargo_pid": 1264998,
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
      "cwd": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "event_id": "bsrun:1cfc38ae44e3b5f7:58c8166d76a53504:5698292d0e3f3d21",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
      "out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
      "success": true,
      "target": null,
      "version": "0.1.10",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-ppc64le-xsl7vlps/src/esaxx-rs-0.1.10",
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
      "build_script_root_pid": 1265034,
      "build_script_target_dir": "libc-8a12625678126bc3",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 1265035,
      "ppid": 1265034,
      "root_cargo_pid": 1264998,
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
